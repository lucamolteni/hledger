# Download

## I want to download and run
<!-- <sub>(If the download is out of date or doesn't run on my system, I might troubleshoot or donate to fund improvements)</sub> -->

<table>
<tr valign="top">
<td width="50%">
**I'm on Debian or Ubuntu**\
`apt-get install hledger hledger-web`

**I'm on Gentoo**\
`emerge hledger hledger-web`

**I'm on Red Hat/Fedora/CentOS**\
`yum install hledger hledger-web`

**I'm on NixOS**\
`nix-env -iA nixpkgs.haskellPackages.hledger nixpkgs.haskellPackages.hledgerWeb`

<!--
**I'm on another GNU/Linux\<small>(or can run Linux binaries)</small>**
[hledger.linux-32.zip]()
[hledger-web.linux-32.zip]()
[hledger.linux-64.zip]()
[hledger-web.linux-64.zip]()
Use cabal
-->
[Release Notes](release-notes.html)

</td>
<td width="50%">
 <table border=0 cellspacing=0 cellpadding=0>
 <tr valign=top>
 <td width="50%">

 **I'm on Windows**\
 <!-- [windows install guide](windows-install.html)\ -->
 Download, unzip, and run:\
 [hledger-0.23.3.win32.zip](http://hledger.org/downloads/hledger-0.23.3-windows-intel32.exe.zip)\
 [hledger-web-0.23.3.win32.zip](http://hledger.org/downloads/hledger-web-0.23.3-windows-intel32.exe.zip)

 </td>
 <td width="25%">

 **I'm on Mac**\
 <!-- [mac install guide](mac-install.html)\ -->
 <!-- [hledger.mac.zip]()\ -->
 <!-- [hledger-web.mac.zip]()\ -->
 Use cabal (see below)

 </td>
 </tr>
 <tr>
 <td colspan="2" style="padding-left:1em;padding-right:2em;">

 <div style="margin-left:1em; float:right;">
 **[Gittip](https://www.gittip.com/simonmichael/)**,
 <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=5J33NLXYXCYAY"><img border=0 src="https://www.paypal.com/en_US/i/btn/x-click-but04.gif" alt="paypal"></a>
 </div>
 Building and supporting Windows and Mac binaries is costly, so
 it's demand-driven - you can indicate demand by making a project
 donation of any size. Binaries funded in this way will be linked here.
 This is a quick way to help the project and your fellow users!

 </td>
 </tr>
 </table>
</td>
</tr>
</table>

## I want to build the [latest release](http://hackage.haskell.org/package/hledger-web) with [GHC](http://haskell.org/ghc) and [cabal](http://haskell.org/cabal/download.html)

`cabal sandbox init; cabal update; cabal install hledger-web`\
<!-- [cabal install guide](cabal-install.html) -->

Or just cabal install `hledger` if you don't need the web interface.
The [Installation Guide](installing.html) describes how to install using cabal in more detail.

## I want to build the [latest development code](http://hledger.org/code)

`git clone https://github.com/simonmichael/hledger; cd hledger; make sandbox install`
