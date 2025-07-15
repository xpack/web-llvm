---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vfs/redirectingfilesystem
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RedirectingFileSystem` Class Reference

<p>A virtual file system parsed from a YAML file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::vfs::RedirectingFileSystem { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">llvm/Support/VirtualFileSystem.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/rttiextends">RTTIExtends&lt;ThisT, ParentT, ParentTs&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inheritance utility for extensible RTTI. <a href="/web-llvm/docs/api/classes/llvm/rttiextends/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">EntryKind { <a href="#a9507b40bcb88580411b40aaf59c105ae">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NameKind { <a href="#a837bbd43fe03a47cfafb99d47a9fa042">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RedirectKind { <a href="#a63bec507dd571ea0302cd27827af81c0">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type of redirection to perform. <a href="#a63bec507dd571ea0302cd27827af81c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RootRelativeKind { <a href="#a09f22a5612ee3a09f13d4641d5017f2d">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type of relative path used by Roots. <a href="#a09f22a5612ee3a09f13d4641d5017f2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97b4b51c367a6158df7ec96b2faf0ed2">RedirectingFSDirIterImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a341937336432d0819c602220545628e5">RedirectingFileSystemParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a540b5d6fddce2f91f2e43fa18e81fb79">RedirectingFileSystem</a> (IntrusiveRefCntPtr&lt; FileSystem &gt; ExternalFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vfs/redirectingfilesystem/lookupresult">LookupResult</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f8600aa879b6d745a7f94e5b0ffaffd">lookupPath</a> (StringRef Path) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks up <span class="doxyComputerOutput">Path</span> in <span class="doxyComputerOutput">Roots</span> and returns a <a href="/web-llvm/docs/api/structs/llvm/vfs/redirectingfilesystem/lookupresult">LookupResult</a> giving the matched entry and, if the entry was a <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/fileentry">FileEntry</a> or <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/directoryremapentry">DirectoryRemapEntry</a>, the path it redirects to in the external file system. <a href="#a5f8600aa879b6d745a7f94e5b0ffaffd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/status">Status</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a041113ae9c86afaf78aca845b270af82">status</a> (const Twine &amp;Path) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the status of the entry at <span class="doxyComputerOutput">Path</span>, if one exists. <a href="#a041113ae9c86afaf78aca845b270af82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a4a25ca3fa9ef5bb3246ca2162f4f96">exists</a> (const Twine &amp;Path) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether <span class="doxyComputerOutput">Path</span> exists. <a href="#a0a4a25ca3fa9ef5bb3246ca2162f4f96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/file">File</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a756f82cf24e75f443c6f032253d84dba">openFileForRead</a> (const Twine &amp;Path) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/vfs/file">File</a></span> object for the text file at <span class="doxyComputerOutput">Path</span>, if one exists. <a href="#a756f82cf24e75f443c6f032253d84dba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a716fd28e6537ab39f3d930edfb00dc66">getRealPath</a> (const Twine &amp;Path, SmallVectorImpl&lt; char &gt; &amp;Output) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets real path of <span class="doxyComputerOutput">Path</span> e.g. <a href="#a716fd28e6537ab39f3d930edfb00dc66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">llvm::ErrorOr</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a820eac46902b52ddd3ab17be3313e410">getCurrentWorkingDirectory</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the working directory of this file system. <a href="#a820eac46902b52ddd3ab17be3313e410">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aade7a1732e7a6faf95b10e4c084c19da">setCurrentWorkingDirectory</a> (const Twine &amp;Path) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the working directory. <a href="#aade7a1732e7a6faf95b10e4c084c19da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a927f391dc40ec58157bc3456784ab726">isLocal</a> (const Twine &amp;Path, bool &amp;Result) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is the file mounted on a local filesystem? <a href="#a927f391dc40ec58157bc3456784ab726">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34121aca2e132eb1499ce67598c87c1b">makeAbsolute</a> (SmallVectorImpl&lt; char &gt; &amp;Path) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make <em>Path</em> an absolute path. <a href="#a34121aca2e132eb1499ce67598c87c1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/directory-iterator">directory_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5edc743f072765fe8146c1f597d4bb37">dir_begin</a> (const Twine &amp;Dir, std::error_code &amp;EC) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a <a href="/web-llvm/docs/api/classes/llvm/vfs/directory-iterator">directory_iterator</a> for <span class="doxyComputerOutput">Dir</span>. <a href="#a5edc743f072765fe8146c1f597d4bb37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f03c0aad8c4b61df40be450082ed1b5">setOverlayFileDir</a> (StringRef PrefixDir)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add3401ac1a6c10fb58b66c92b64b0c45">getOverlayFileDir</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bd51073acd1e6304294ab7153610175">setFallthrough</a> (bool Fallthrough)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the redirection kind to <span class="doxyComputerOutput">Fallthrough</span> if true or <span class="doxyComputerOutput">RedirectOnly</span> otherwise. <a href="#a6bd51073acd1e6304294ab7153610175">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c3c0f2215ac02029211cd0f4046ecf2">setRedirection</a> (RedirectingFileSystem::RedirectKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4327c6f3162138e889dc61ccde683b85">getRoots</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6179e2be01a39ae871447534cd8638f">hasBeenUsed</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5f94a31e3b200b44d7474e77974b4cb">clearHasBeenUsed</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0116b538ab0138e93e0c9ed5d9e04c07">setUsageTrackingActive</a> (bool Active)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4447c8eb1acebfa76ee7b580ccf93cc">printEntry</a> (raw_ostream &amp;OS, Entry *E, unsigned IndentLevel=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15ce8d2f492ee147cf4875bf7b8c24e3">printImpl</a> (raw_ostream &amp;OS, PrintType Type, unsigned IndentLevel) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f20eb73a275b0fd618ce145f565a262">visitChildFileSystems</a> (VisitCallbackTy Callback) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bc1af828e7c570098c13a761733836c">makeCanonicalForLookup</a> (SmallVectorImpl&lt; char &gt; &amp;Path) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Canonicalize path by removing ".", "..", "./", components. <a href="#a2bc1af828e7c570098c13a761733836c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/status">Status</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3332f5925aec0b0166c5f5085d866b57">getExternalStatus</a> (const Twine &amp;LookupPath, const Twine &amp;OriginalPath) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/vfs/file">File</a> status, or error, from the underlying external file system. <a href="#a3332f5925aec0b0166c5f5085d866b57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99b517aebffadc4c834aad6a559171bc">makeAbsolute</a> (StringRef WorkingDir, SmallVectorImpl&lt; char &gt; &amp;Path) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make <em>Path</em> an absolute path. <a href="#a99b517aebffadc4c834aad6a559171bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6b7e7203bbae0bc91a7324e343675e3">pathComponentMatches</a> (llvm::StringRef lhs, llvm::StringRef rhs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vfs/redirectingfilesystem/lookupresult">LookupResult</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a625d69f2c0e7664560f0cb6360a84bcc">lookupPathImpl</a> (llvm::sys::path::const_iterator Start, llvm::sys::path::const_iterator End, Entry *From, llvm::SmallVectorImpl&lt; Entry * &gt; &amp;Entries) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks up the path <span class="doxyComputerOutput">[Start, End)</span> in <span class="doxyComputerOutput">From</span>, possibly recursing into the contents of <span class="doxyComputerOutput">From</span> if it is a directory. <a href="#a625d69f2c0e7664560f0cb6360a84bcc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/status">Status</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1118af80c15ddaa69d5a7ca25e184a8">status</a> (const Twine &amp;LookupPath, const Twine &amp;OriginalPath, const LookupResult &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the status for a path with the provided <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/vfs/redirectingfilesystem/lookupresult">LookupResult</a></span>. <a href="#af1118af80c15ddaa69d5a7ca25e184a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry">Entry</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3290a380f493d79438fdeab078c91725">Roots</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The root(s) of the virtual file system. <a href="#a3290a380f493d79438fdeab078c91725">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53c086dfbfbb7efb7eb10b7b58a0f86c">WorkingDirectory</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current working directory of the file system. <a href="#a53c086dfbfbb7efb7eb10b7b58a0f86c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">FileSystem</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba283723052667bb7a31283bd2b05549">ExternalFS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The file system to use for external references. <a href="#aba283723052667bb7a31283bd2b05549">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d515e4c2b6cbd1ffc127a8f75e44d24">OverlayFileDir</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This represents the directory path that the YAML file is located. <a href="#a3d515e4c2b6cbd1ffc127a8f75e44d24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem">RedirectingFileSystem</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f274211d8e2baf7f13ec1e030e09de6">create</a> (std::unique_ptr&lt; MemoryBuffer &gt; Buffer, SourceMgr::DiagHandlerTy DiagHandler, StringRef YAMLFilePath, void *DiagContext, IntrusiveRefCntPtr&lt; FileSystem &gt; ExternalFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses <span class="doxyComputerOutput">Buffer</span>, which is expected to be in YAML format and returns a virtual file system representing its contents. <a href="#a9f274211d8e2baf7f13ec1e030e09de6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem">RedirectingFileSystem</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1889d01b571d20008558e46cea63f435">create</a> (ArrayRef&lt; std::pair&lt; std::string, std::string &gt; &gt; RemappedFiles, bool UseExternalNames, FileSystem &amp;ExternalFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Redirect each of the remapped files from first to second. <a href="#a1889d01b571d20008558e46cea63f435">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa40459111845179e104abb274985ec7">ID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Configuration Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39656e314338ee73adb1149cd31a81fd">CaseSensitive</a> = is_style_posix(<a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">sys::path::Style::native</a>)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether to perform case-sensitive comparisons. <a href="#a39656e314338ee73adb1149cd31a81fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ad1c648e9b0c12589d7718f90ebf4b3">IsRelativeOverlay</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsRelativeOverlay marks whether a OverlayFileDir path must be prefixed in every 'external-contents' when reading from YAML files. <a href="#a8ad1c648e9b0c12589d7718f90ebf4b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abafea9a6b5142571e005c225c491ddae">UseExternalNames</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether to use to use the value of 'external-contents' for the names of files. <a href="#abafea9a6b5142571e005c225c491ddae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade22860baa85296ff5062249e2600493">HasBeenUsed</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this FS has redirected a lookup. <a href="#ade22860baa85296ff5062249e2600493">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e7914bd413b3fabf9090208a94e70a0">UsageTrackingActive</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to enable or disable updating <span class="doxyComputerOutput">HasBeenUsed</span>. <a href="#a6e7914bd413b3fabf9090208a94e70a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a63bec507dd571ea0302cd27827af81c0">RedirectKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31de67b17a61a111b4c48f22bfdd04b1">Redirection</a> = <a href="#a63bec507dd571ea0302cd27827af81c0a5d562a226f723ccf02b8c640f15f354b">RedirectKind::Fallthrough</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determines the lookups to perform, as well as their order. <a href="#a31de67b17a61a111b4c48f22bfdd04b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a09f22a5612ee3a09f13d4641d5017f2d">RootRelativeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8073c0af6b6171550c623664671fdbb1">RootRelative</a> = <a href="#a09f22a5612ee3a09f13d4641d5017f2dae2523df869c463690e853798ddc82f28">RootRelativeKind::CWD</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the prefix directory if the roots are relative paths. <a href="#a8073c0af6b6171550c623664671fdbb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A virtual file system parsed from a YAML file.</p>


<p>Currently, this class allows creating virtual files and directories. Virtual files map to existing external files in <span class="doxyComputerOutput">ExternalFS</span>, and virtual directories may either map to existing directories in <span class="doxyComputerOutput">ExternalFS</span> or list their contents in the form of other virtual directories and/or files.</p>


<p>The basic structure of the parsed file is:</p>



<pre><code>/// {
///   'version': &lt;version number&gt;,
///   &lt;optional configuration&gt;
///   'roots': [
///              &lt;directory entries&gt;
///            ]
/// }
///
</code></pre>


<p>The roots may be absolute or relative. If relative they will be made absolute against either current working directory or the directory where the Overlay YAML file is located, depending on the 'root-relative' configuration.</p>


<p>All configuration options are optional. 'case-sensitive': &lt;boolean, default=(true for Posix, false for Windows)&gt; 'use-external-names': &lt;boolean, default=true&gt; 'root-relative': &lt;string, one of 'cwd' or 'overlay-dir', default='cwd'&gt; 'overlay-relative': &lt;boolean, default=false&gt; 'fallthrough': &lt;boolean, default=true, deprecated - use 'redirecting-with' instead&gt; 'redirecting-with': &lt;string, one of 'fallthrough', 'fallback', or 'redirect-only', default='fallthrough'&gt;</p>


<p>To clarify, 'root-relative' option will prepend the current working directory, or the overlay directory to the 'roots-&gt;name' field only if 'roots-&gt;name' is a relative path. On the other hand, when 'overlay-relative' is set to 'true', external paths will always be prepended with the overlay directory, even if external paths are not relative paths. The 'root-relative' option has no interaction with the 'overlay-relative' option.</p>


<p>Virtual directories that list their contents are represented as</p>



<pre><code>/// {
///   'type': 'directory',
///   'name': &lt;string&gt;,
///   'contents': [ &lt;file or directory entries&gt; ]
/// }
///
</code></pre>


<p>The default attributes for such virtual directories are:</p>



<pre><code>/// MTime = now() when created
/// Perms = 0777
/// User = Group = 0
/// Size = 0
/// UniqueID = unspecified unique value
///
</code></pre>


<p>When a path prefix matches such a directory, the next component in the path is matched against the entries in the 'contents' array.</p>


<p>Re-mapped directories, on the other hand, are represented as ///</p>



<pre><code>/// {
///   'type': 'directory-remap',
///   'name': &lt;string&gt;,
///   'use-external-name': &lt;boolean&gt;, # Optional
///   'external-contents': &lt;path to external directory&gt;
/// }
///
</code></pre>


<p>and inherit their attributes from the external directory. When a path prefix matches such an entry, the unmatched components are appended to the 'external-contents' path, and the resulting path is looked up in the external file system instead.</p>


<p>Re-mapped files are represented as</p>



<pre><code>/// {
///   'type': 'file',
///   'name': &lt;string&gt;,
///   'use-external-name': &lt;boolean&gt;, # Optional
///   'external-contents': &lt;path to external file&gt;
/// }
///
</code></pre>


<p>Their attributes and file contents are determined by looking up the file at their 'external-contents' path in the external file system.</p>


<p>For 'file', 'directory' and 'directory-remap' entries the 'name' field may contain multiple path components (e.g. /path/to/file). However, any directory in such a path that contains more than one child must be uniquely represented by a 'directory' entry.</p>


<p>When the 'use-external-name' field is set, calls to <em><a href="/web-llvm/docs/api/classes/llvm/vfs/file/#a42e50c531aa6b96228eed7c6b885fcaf">vfs::File::status()</a></em> give the external (remapped) filesystem name instead of the name the file was accessed by. This is an intentional leak through the <em><a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem">RedirectingFileSystem</a></em> abstraction layer. It enables clients to discover (and use) the external file location when communicating with users or tools that don't use the same VFS overlay.</p>


<p>FIXME: 'use-external-name' causes behaviour that's inconsistent with how "real" filesystems behave. Maybe there should be a separate channel for this information.</p>


<p>Definition at line 777 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### EntryKind {#a9507b40bcb88580411b40aaf59c105ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::vfs::RedirectingFileSystem::EntryKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EK_Directory<a id="a9507b40bcb88580411b40aaf59c105aea53dd0141cf4c202d8b1167608b16368e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EK_DirectoryRemap<a id="a9507b40bcb88580411b40aaf59c105aea2c13f4e113c2d83046295f95a17aa19d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EK_File<a id="a9507b40bcb88580411b40aaf59c105aea03e8d48c99b4e6a894fb7651aee0c727"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### NameKind {#a837bbd43fe03a47cfafb99d47a9fa042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::vfs::RedirectingFileSystem::NameKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NK_NotSet<a id="a837bbd43fe03a47cfafb99d47a9fa042ad999c8c10cab1f4c45fbb748c6592ebd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NK_External<a id="a837bbd43fe03a47cfafb99d47a9fa042a89b3ca06f9a5f78465654ab19f83fbad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NK_Virtual<a id="a837bbd43fe03a47cfafb99d47a9fa042a1a039623fd4526d60bde1baa877d46fa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 782 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### RedirectKind {#a63bec507dd571ea0302cd27827af81c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::vfs::RedirectingFileSystem::RedirectKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type of redirection to perform.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Fallthrough<a id="a63bec507dd571ea0302cd27827af81c0a5d562a226f723ccf02b8c640f15f354b"></a></td>
<td class="doxyEnumItemDescription">Lookup the redirected path first (ie</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Fallback<a id="a63bec507dd571ea0302cd27827af81c0a882277bdf25efaeb8295e842ebcb3d11"></a></td>
<td class="doxyEnumItemDescription">Lookup the provided path first and if that fails, "fallback" to a lookup of the redirected path</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RedirectOnly<a id="a63bec507dd571ea0302cd27827af81c0ad1329fb446b085c1ef41002bc84a510f"></a></td>
<td class="doxyEnumItemDescription">Only lookup the redirected path, do not lookup the originally provided path</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### RootRelativeKind {#a09f22a5612ee3a09f13d4641d5017f2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::vfs::RedirectingFileSystem::RootRelativeKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type of relative path used by Roots.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CWD<a id="a09f22a5612ee3a09f13d4641d5017f2dae2523df869c463690e853798ddc82f28"></a></td>
<td class="doxyEnumItemDescription">The roots are relative to the current working directory</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OverlayDir<a id="a09f22a5612ee3a09f13d4641d5017f2da883fce724fbb5ef711e9860e56d2f4f9"></a></td>
<td class="doxyEnumItemDescription">The roots are relative to the directory where the Overlay YAML file</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### RedirectingFileSystemParser {#a341937336432d0819c602220545628e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystemparser">RedirectingFileSystemParser</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 946 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Reference <a href="#a341937336432d0819c602220545628e5">RedirectingFileSystemParser</a>.</p>


<p>Referenced by <a href="#a9f274211d8e2baf7f13ec1e030e09de6">create</a> and <a href="#a341937336432d0819c602220545628e5">RedirectingFileSystemParser</a>.</p>

</div>
</div>

### RedirectingFSDirIterImpl {#a97b4b51c367a6158df7ec96b2faf0ed2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfsdiriterimpl">RedirectingFSDirIterImpl</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 945 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Reference <a href="#a97b4b51c367a6158df7ec96b2faf0ed2">RedirectingFSDirIterImpl</a>.</p>


<p>Referenced by <a href="#a97b4b51c367a6158df7ec96b2faf0ed2">RedirectingFSDirIterImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### RedirectingFileSystem() {#a540b5d6fddce2f91f2e43fa18e81fb79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RedirectingFileSystem::RedirectingFileSystem (<a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">FileSystem</a> &gt; ExternalFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1032 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1257 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearHasBeenUsed() {#ad5f94a31e3b200b44d7474e77974b4cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::vfs::RedirectingFileSystem::clearHasBeenUsed ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1095 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### dir\_begin() {#a5edc743f072765fe8146c1f597d4bb37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">directory_iterator RedirectingFileSystem::dir_begin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Dir, std::error_code &amp; EC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a <a href="/web-llvm/docs/api/classes/llvm/vfs/directory-iterator">directory_iterator</a> for <span class="doxyComputerOutput">Dir</span>.</p>



:::info
<p>The 'end' iterator is directory_iterator().</p>
:::


<p>Declaration at line 1080 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1438 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a63bec507dd571ea0302cd27827af81c0a882277bdf25efaeb8295e842ebcb3d11">Fallback</a>, <a href="#a63bec507dd571ea0302cd27827af81c0a5d562a226f723ccf02b8c640f15f354b">Fallthrough</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a8300c72908f1845c931951ed4b2a2375">llvm::ErrorOr&lt; T &gt;::getError</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a5f8600aa879b6d745a7f94e5b0ffaffd">lookupPath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba2e70fc89b08f26fa3fc77694c91e8f7a">llvm::no_such_file_or_directory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba21e867ca95e1dfecff4701863547dcec">llvm::not_a_directory</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a63bec507dd571ea0302cd27827af81c0ad1329fb446b085c1ef41002bc84a510f">RedirectOnly</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#ae2cc7378ca67e19c45648f7800686933">llvm::Twine::toVector</a>.</p>

</div>
</div>

### exists() {#a0a4a25ca3fa9ef5bb3246ca2162f4f96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RedirectingFileSystem::exists (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether <span class="doxyComputerOutput">Path</span> exists.</p>


<p>By default this uses <span class="doxyComputerOutput">status()</span>, but filesystems may provide a more efficient implementation if available.</p>


<p>Declaration at line 1066 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 2464 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a63bec507dd571ea0302cd27827af81c0a882277bdf25efaeb8295e842ebcb3d11">Fallback</a>, <a href="#a63bec507dd571ea0302cd27827af81c0a5d562a226f723ccf02b8c640f15f354b">Fallthrough</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a5f8600aa879b6d745a7f94e5b0ffaffd">lookupPath</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#ae2cc7378ca67e19c45648f7800686933">llvm::Twine::toVector</a>.</p>


<p>Referenced by <a href="#aade7a1732e7a6faf95b10e4c084c19da">setCurrentWorkingDirectory</a>.</p>

</div>
</div>

### getCurrentWorkingDirectory() {#a820eac46902b52ddd3ab17be3313e410}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorOr&lt; std::string &gt; RedirectingFileSystem::getCurrentWorkingDirectory ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the working directory of this file system.</p>

<p>Declaration at line 1072 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1353 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>Referenced by <a href="#a34121aca2e132eb1499ce67598c87c1b">makeAbsolute</a>.</p>

</div>
</div>

### getOverlayFileDir() {#add3401ac1a6c10fb58b66c92b64b0c45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef RedirectingFileSystem::getOverlayFileDir ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1084 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1542 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### getRealPath() {#a716fd28e6537ab39f3d930edfb00dc66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code RedirectingFileSystem::getRealPath (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Output)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets real path of <span class="doxyComputerOutput">Path</span> e.g.</p>


<p>collapse all . and .. patterns, resolve symlinks. For real file system, this uses <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a2363fbfbd0a348f5d81fc3d3223ecae3">llvm::sys::fs::real_path</a></span>. This returns <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba8344b3d509942f035d5e303022f9b986">errc::operation_not_permitted</a> if not implemented by subclass.</p>


<p>Declaration at line 1069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 2614 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="#a63bec507dd571ea0302cd27827af81c0a882277bdf25efaeb8295e842ebcb3d11">Fallback</a>, <a href="#a63bec507dd571ea0302cd27827af81c0a5d562a226f723ccf02b8c640f15f354b">Fallthrough</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="#a5f8600aa879b6d745a7f94e5b0ffaffd">lookupPath</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#ae2cc7378ca67e19c45648f7800686933">llvm::Twine::toVector</a>.</p>

</div>
</div>

### getRoots() {#a4327c6f3162138e889dc61ccde683b85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; StringRef &gt; RedirectingFileSystem::getRoots ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1092 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1559 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### hasBeenUsed() {#aa6179e2be01a39ae871447534cd8638f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vfs::RedirectingFileSystem::hasBeenUsed ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1094 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### isLocal() {#a927f391dc40ec58157bc3456784ab726}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code RedirectingFileSystem::isLocal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path, bool &amp; Result)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is the file mounted on a local filesystem?</p>

<p>Declaration at line 1076 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1371 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/twine/#ae2cc7378ca67e19c45648f7800686933">llvm::Twine::toVector</a>.</p>

</div>
</div>

### lookupPath() {#a5f8600aa879b6d745a7f94e5b0ffaffd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; RedirectingFileSystem::LookupResult &gt; RedirectingFileSystem::lookupPath (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Looks up <span class="doxyComputerOutput">Path</span> in <span class="doxyComputerOutput">Roots</span> and returns a <a href="/web-llvm/docs/api/structs/llvm/vfs/redirectingfilesystem/lookupresult">LookupResult</a> giving the matched entry and, if the entry was a <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/fileentry">FileEntry</a> or <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/directoryremapentry">DirectoryRemapEntry</a>, the path it redirects to in the external file system.</p>

<p>Declaration at line 1051 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 2309 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a2798f80ce7d64ebc7049d1231e675137">llvm::sys::path::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ae6199e07e1f06cdaf0ad59b959045035">llvm::sys::path::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20e3e08c7de6a230cd66f9e4322c3fbe">llvm::make_error_code</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba2e70fc89b08f26fa3fc77694c91e8f7a">llvm::no_such_file_or_directory</a> and <a href="#a63bec507dd571ea0302cd27827af81c0ad1329fb446b085c1ef41002bc84a510f">RedirectOnly</a>.</p>


<p>Referenced by <a href="#a5edc743f072765fe8146c1f597d4bb37">dir_begin</a>, <a href="#a0a4a25ca3fa9ef5bb3246ca2162f4f96">exists</a>, <a href="#a716fd28e6537ab39f3d930edfb00dc66">getRealPath</a>, <a href="#a756f82cf24e75f443c6f032253d84dba">openFileForRead</a> and <a href="#a041113ae9c86afaf78aca845b270af82">status</a>.</p>

</div>
</div>

### makeAbsolute() {#a34121aca2e132eb1499ce67598c87c1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code RedirectingFileSystem::makeAbsolute (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Path)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make <em>Path</em> an absolute path.</p>


<p>Makes <em>Path</em> absolute using the current directory if it is not already. An empty <em>Path</em> will result in the current directory.</p>


<p>/absolute/path =&gt; /absolute/path relative/../path =&gt; &lt;current-directory&gt;/relative/../path</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Path</td>
<td class="doxyParamItemDescription"><p>A path that is modified to be an absolute path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>success if <em>path</em> has been made absolute, otherwise a platform-specific error_code.</p></dd>
</dl>


<p>Declaration at line 1078 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1382 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="#a820eac46902b52ddd3ab17be3313e410">getCurrentWorkingDirectory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ac35ec1dacb408d4c65d55249c0e02474">llvm::sys::path::is_absolute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49fa950616e5405e4ef51a87d384180e7aa1">llvm::sys::path::posix</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49fa20919b5752b40386cb56aff9b8f07723">llvm::sys::path::windows_backslash</a>.</p>

</div>
</div>

### openFileForRead() {#a756f82cf24e75f443c6f032253d84dba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; File &gt; &gt; RedirectingFileSystem::openFileForRead (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/vfs/file">File</a></span> object for the text file at <span class="doxyComputerOutput">Path</span>, if one exists.</p>

<p>Declaration at line 1067 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 2553 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a63bec507dd571ea0302cd27827af81c0a882277bdf25efaeb8295e842ebcb3d11">Fallback</a>, <a href="#a63bec507dd571ea0302cd27827af81c0a5d562a226f723ccf02b8c640f15f354b">Fallthrough</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp/#a8fc685edd229a3c37701f7520c54eb23">getRedirectedFileStatus</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/file/#a087eb20712ef755e7ff0bc36b722f789">llvm::vfs::File::getWithPath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="#a5f8600aa879b6d745a7f94e5b0ffaffd">lookupPath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20e3e08c7de6a230cd66f9e4322c3fbe">llvm::make_error_code</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#ae2cc7378ca67e19c45648f7800686933">llvm::Twine::toVector</a>.</p>

</div>
</div>

### printEntry() {#af4447c8eb1acebfa76ee7b580ccf93cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RedirectingFileSystem::printEntry (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry">Entry</a> * E, unsigned IndentLevel=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1099 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1584 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a9507b40bcb88580411b40aaf59c105aea53dd0141cf4c202d8b1167608b16368e">EK_Directory</a>, <a href="#a9507b40bcb88580411b40aaf59c105aea2c13f4e113c2d83046295f95a17aa19d">EK_DirectoryRemap</a>, <a href="#a9507b40bcb88580411b40aaf59c105aea03e8d48c99b4e6a894fb7651aee0c727">EK_File</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a837bbd43fe03a47cfafb99d47a9fa042a89b3ca06f9a5f78465654ab19f83fbad">NK_External</a>, <a href="#a837bbd43fe03a47cfafb99d47a9fa042ad999c8c10cab1f4c45fbb748c6592ebd">NK_NotSet</a>, <a href="#a837bbd43fe03a47cfafb99d47a9fa042a1a039623fd4526d60bde1baa877d46fa">NK_Virtual</a>, <a href="#af4447c8eb1acebfa76ee7b580ccf93cc">printEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem/#a8c7d80ced435a4f134fa61d5d92a9968">llvm::vfs::FileSystem::printIndent</a>.</p>


<p>Referenced by <a href="#af4447c8eb1acebfa76ee7b580ccf93cc">printEntry</a> and <a href="#a15ce8d2f492ee147cf4875bf7b8c24e3">printImpl</a>.</p>

</div>
</div>

### setCurrentWorkingDirectory() {#aade7a1732e7a6faf95b10e4c084c19da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code RedirectingFileSystem::setCurrentWorkingDirectory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the working directory.</p>


<p>This will affect all following operations on this file system and may propagate down for nested file systems.</p>


<p>Declaration at line 1074 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1358 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="#a0a4a25ca3fa9ef5bb3246ca2162f4f96">exists</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba2e70fc89b08f26fa3fc77694c91e8f7a">llvm::no_such_file_or_directory</a>.</p>

</div>
</div>

### setFallthrough() {#a6bd51073acd1e6304294ab7153610175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RedirectingFileSystem::setFallthrough (bool Fallthrough)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the redirection kind to <span class="doxyComputerOutput">Fallthrough</span> if true or <span class="doxyComputerOutput">RedirectOnly</span> otherwise.</p>


<p>Will removed in the future, use <span class="doxyComputerOutput">setRedirection</span> instead.</p>


<p>Declaration at line 1088 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1546 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="#a63bec507dd571ea0302cd27827af81c0a5d562a226f723ccf02b8c640f15f354b">Fallthrough</a> and <a href="#a63bec507dd571ea0302cd27827af81c0ad1329fb446b085c1ef41002bc84a510f">RedirectOnly</a>.</p>

</div>
</div>

### setOverlayFileDir() {#a7f03c0aad8c4b61df40be450082ed1b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RedirectingFileSystem::setOverlayFileDir (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PrefixDir)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1082 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1538 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>.</p>

</div>
</div>

### setRedirection() {#a8c3c0f2215ac02029211cd0f4046ecf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RedirectingFileSystem::setRedirection (<a href="#a63bec507dd571ea0302cd27827af81c0">RedirectingFileSystem::RedirectKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1090 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1554 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### setUsageTrackingActive() {#a0116b538ab0138e93e0c9ed5d9e04c07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::vfs::RedirectingFileSystem::setUsageTrackingActive (bool Active)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1097 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### status() {#a041113ae9c86afaf78aca845b270af82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; Status &gt; RedirectingFileSystem::status (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the status of the entry at <span class="doxyComputerOutput">Path</span>, if one exists.</p>

<p>Declaration at line 1065 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 2427 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="#a63bec507dd571ea0302cd27827af81c0a882277bdf25efaeb8295e842ebcb3d11">Fallback</a>, <a href="#a63bec507dd571ea0302cd27827af81c0a5d562a226f723ccf02b8c640f15f354b">Fallthrough</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a8300c72908f1845c931951ed4b2a2375">llvm::ErrorOr&lt; T &gt;::getError</a>, <a href="#a5f8600aa879b6d745a7f94e5b0ffaffd">lookupPath</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#ae2cc7378ca67e19c45648f7800686933">llvm::Twine::toVector</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### printImpl() {#a15ce8d2f492ee147cf4875bf7b8c24e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RedirectingFileSystem::printImpl (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem/#a18e26e37e377b73c564488e7b77424ec">PrintType</a> Type, unsigned IndentLevel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1567 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem/#a18e26e37e377b73c564488e7b77424ecac1df1da7a1ce305a3b60af9d5733ac1d">llvm::vfs::FileSystem::Contents</a>, <a href="#af4447c8eb1acebfa76ee7b580ccf93cc">printEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem/#a8c7d80ced435a4f134fa61d5d92a9968">llvm::vfs::FileSystem::printIndent</a> and <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem/#a18e26e37e377b73c564488e7b77424eca290612199861c31d1036b185b4e69b75">llvm::vfs::FileSystem::Summary</a>.</p>

</div>
</div>

### visitChildFileSystems() {#a6f20eb73a275b0fd618ce145f565a262}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RedirectingFileSystem::visitChildFileSystems (<a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem/#a043edde8f3c87c7869e5112c5ef954e6">VisitCallbackTy</a> Callback)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1620 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getExternalStatus() {#a3332f5925aec0b0166c5f5085d866b57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; Status &gt; RedirectingFileSystem::getExternalStatus (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; LookupPath, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; OriginalPath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/vfs/file">File</a> status, or error, from the underlying external file system.</p>


<p>This returns the status with the originally requested name, while looking up the entry using a potentially different path.</p>


<p>Declaration at line 956 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 2416 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### lookupPathImpl() {#a625d69f2c0e7664560f0cb6360a84bcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; RedirectingFileSystem::LookupResult &gt; RedirectingFileSystem::lookupPathImpl (<a href="/web-llvm/docs/api/classes/llvm/sys/path/const-iterator">llvm::sys::path::const_iterator</a> Start, <a href="/web-llvm/docs/api/classes/llvm/sys/path/const-iterator">llvm::sys::path::const_iterator</a> End, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry">Entry</a> * From, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">llvm::SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry">Entry</a> * &gt; &amp; Entries)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Looks up the path <span class="doxyComputerOutput">[Start, End)</span> in <span class="doxyComputerOutput">From</span>, possibly recursing into the contents of <span class="doxyComputerOutput">From</span> if it is a directory.</p>


<p>Returns a <a href="/web-llvm/docs/api/structs/llvm/vfs/redirectingfilesystem/lookupresult">LookupResult</a> giving the matched entry and, if that entry is a <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/fileentry">FileEntry</a> or <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/directoryremapentry">DirectoryRemapEntry</a>, the path it redirects to in the external file system.</p>


<p>Declaration at line 1039 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 2335 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### makeAbsolute() {#a99b517aebffadc4c834aad6a559171bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code RedirectingFileSystem::makeAbsolute (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> WorkingDir, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make <em>Path</em> an absolute path.</p>


<p>Makes <em>Path</em> absolute using the <em>WorkingDir</em> if it is not already.</p>


<p>/absolute/path =&gt; /absolute/path relative/../path =&gt; &lt;WorkingDir&gt;/relative/../path</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">WorkingDir</td>
<td class="doxyParamItemDescription"><p>A path that will be used as the base Dir if <em>Path</em> is not already absolute.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Path</td>
<td class="doxyParamItemDescription"><p>A path that is modified to be an absolute path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>success if <em>path</em> has been made absolute, otherwise a platform-specific error_code.</p></dd>
</dl>


<p>Declaration at line 971 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1400 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### makeCanonicalForLookup() {#a2bc1af828e7c570098c13a761733836c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code RedirectingFileSystem::makeCanonicalForLookup (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Canonicalize path by removing ".", "..", "./", components.</p>


<p>This is a VFS request, do not bother about symlinks in the path components but canonicalize in order to perform the correct entry search.</p>


<p>Declaration at line 951 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 2294 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### pathComponentMatches() {#ae6b7e7203bbae0bc91a7324e343675e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vfs::RedirectingFileSystem::pathComponentMatches (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> lhs, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> rhs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 979 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### status() {#af1118af80c15ddaa69d5a7ca25e184a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; Status &gt; RedirectingFileSystem::status (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; LookupPath, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; OriginalPath, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/vfs/redirectingfilesystem/lookupresult">LookupResult</a> &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the status for a path with the provided <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/vfs/redirectingfilesystem/lookupresult">LookupResult</a></span>.</p>

<p>Declaration at line 1044 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 2394 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ExternalFS {#aba283723052667bb7a31283bd2b05549}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrusiveRefCntPtr&lt;FileSystem&gt; llvm::vfs::RedirectingFileSystem::ExternalFS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The file system to use for external references.</p>

<p>Definition at line 992 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### OverlayFileDir {#a3d515e4c2b6cbd1ffc127a8f75e44d24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::vfs::RedirectingFileSystem::OverlayFileDir</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This represents the directory path that the YAML file is located.</p>


<p>This will be prefixed to each 'external-contents' if IsRelativeOverlay is set. This will also be prefixed to each 'roots-&gt;name' if RootRelative is set to <a href="#a09f22a5612ee3a09f13d4641d5017f2da883fce724fbb5ef711e9860e56d2f4f9">RootRelativeKind::OverlayDir</a> and the path is relative.</p>


<p>Definition at line 998 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### Roots {#a3290a380f493d79438fdeab078c91725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;Entry&gt; &gt; llvm::vfs::RedirectingFileSystem::Roots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The root(s) of the virtual file system.</p>

<p>Definition at line 986 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### WorkingDirectory {#a53c086dfbfbb7efb7eb10b7b58a0f86c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::vfs::RedirectingFileSystem::WorkingDirectory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The current working directory of the file system.</p>

<p>Definition at line 989 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a9f274211d8e2baf7f13ec1e030e09de6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; RedirectingFileSystem &gt; RedirectingFileSystem::create (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; Buffer, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#acf78be89ec851a45f37a776a5a58bfe8">SourceMgr::DiagHandlerTy</a> DiagHandler, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> YAMLFilePath, void * DiagContext, <a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">FileSystem</a> &gt; ExternalFS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parses <span class="doxyComputerOutput">Buffer</span>, which is expected to be in YAML format and returns a virtual file system representing its contents.</p>

<p>Declaration at line 1056 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 2176 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/stream/#a28a9f3738483f46eb7087f114ec3c074">llvm::yaml::Stream::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp/#aa9f07add63589fb3b28821d089f069a7">DiagHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/stream/#a19ac1ea26f1dc39bc0922145ebc30ed3">llvm::yaml::Stream::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a144ec9dcc77027317d16af9fc5fec1c8">llvm::sys::fs::make_absolute</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a5326427c87607b2364a1fcdf13fa0eea">llvm::sys::path::parent_path</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a5fb499d84f3af1286e8d508a760aa396">llvm::SourceMgr::PrintMessage</a>, <a href="#a341937336432d0819c602220545628e5">RedirectingFileSystemParser</a> and <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#ad324bef18696e3fcd110ffb2d33a2b58">llvm::SourceMgr::setDiagHandler</a>.</p>

</div>
</div>

### create() {#a1889d01b571d20008558e46cea63f435}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; RedirectingFileSystem &gt; RedirectingFileSystem::create (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; std::string, std::string &gt; &gt; RemappedFiles, bool UseExternalNames, <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">FileSystem</a> &amp; ExternalFS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Redirect each of the remapped files from first to second.</p>

<p>Declaration at line 1062 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 2218 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a2798f80ce7d64ebc7049d1231e675137">llvm::sys::path::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ae6199e07e1f06cdaf0ad59b959045035">llvm::sys::path::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aa56d25bb5127dd7a5831c25764f76cbe">llvm::sys::path::filename</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystemparser/#ac3b4d9a8bed01afc755fcbd6ecdee265">llvm::vfs::RedirectingFileSystemParser::lookupOrCreateEntry</a>, <a href="#a837bbd43fe03a47cfafb99d47a9fa042a89b3ca06f9a5f78465654ab19f83fbad">NK_External</a>, <a href="#a837bbd43fe03a47cfafb99d47a9fa042a1a039623fd4526d60bde1baa877d46fa">NK_Virtual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a5326427c87607b2364a1fcdf13fa0eea">llvm::sys::path::parent_path</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#aaa40459111845179e104abb274985ec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char RedirectingFileSystem::ID = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 780 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Configuration

### CaseSensitive {#a39656e314338ee73adb1149cd31a81fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vfs::RedirectingFileSystem::CaseSensitive = is_style_posix(<a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">sys::path::Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether to perform case-sensitive comparisons.</p>


<p>Currently, case-insensitive matching only works correctly with ASCII.</p>


<p>Definition at line 1006 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### HasBeenUsed {#ade22860baa85296ff5062249e2600493}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vfs::RedirectingFileSystem::HasBeenUsed = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this FS has redirected a lookup.</p>


<p>This does not include fallthrough.</p>


<p>Definition at line 1018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### IsRelativeOverlay {#a8ad1c648e9b0c12589d7718f90ebf4b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vfs::RedirectingFileSystem::IsRelativeOverlay = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IsRelativeOverlay marks whether a OverlayFileDir path must be prefixed in every 'external-contents' when reading from YAML files.</p>

<p>Definition at line 1010 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### Redirection {#a31de67b17a61a111b4c48f22bfdd04b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RedirectKind llvm::vfs::RedirectingFileSystem::Redirection = <a href="#a63bec507dd571ea0302cd27827af81c0a5d562a226f723ccf02b8c640f15f354b">RedirectKind::Fallthrough</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determines the lookups to perform, as well as their order.</p>


<p>See <span class="doxyComputerOutput"><a href="#a63bec507dd571ea0302cd27827af81c0">RedirectKind</a></span> for details.</p>


<p>Definition at line 1025 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### RootRelative {#a8073c0af6b6171550c623664671fdbb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RootRelativeKind llvm::vfs::RedirectingFileSystem::RootRelative = <a href="#a09f22a5612ee3a09f13d4641d5017f2dae2523df869c463690e853798ddc82f28">RootRelativeKind::CWD</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine the prefix directory if the roots are relative paths.</p>


<p>See <span class="doxyComputerOutput"><a href="#a09f22a5612ee3a09f13d4641d5017f2d">RootRelativeKind</a></span> for details.</p>


<p>Definition at line 1029 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### UsageTrackingActive {#a6e7914bd413b3fabf9090208a94e70a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vfs::RedirectingFileSystem::UsageTrackingActive = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to enable or disable updating <span class="doxyComputerOutput">HasBeenUsed</span>.</p>

<p>Definition at line 1021 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### UseExternalNames {#abafea9a6b5142571e005c225c491ddae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vfs::RedirectingFileSystem::UseExternalNames = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether to use to use the value of 'external-contents' for the names of files.</p>


<p>This global value is overridable on a per-file basis.</p>


<p>Definition at line 1014 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
