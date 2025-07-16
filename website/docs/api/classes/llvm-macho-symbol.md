---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/macho/symbol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Symbol` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MachO::Symbol { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">llvm/TextAPI/Symbol.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cb68a6738fcaa9edfd47055cab9bf3a">const_target_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aa11b903431c1931920939bac6b5293a2">TargetList::const_iterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d51d76494265bde81e9367afc256271">const_target_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">llvm::iterator_range</a>&lt; <a href="#a4cb68a6738fcaa9edfd47055cab9bf3a">const_target_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a645ffe74af11c4c44a76d198c72d3704">const_filtered_target_iterator</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a34dde99f929971dfc4e50bb63dd7aecb">llvm::filter_iterator</a>&lt; <a href="#a4cb68a6738fcaa9edfd47055cab9bf3a">const_target_iterator</a>, std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a> &amp;)&gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a511ecd005cd555a167b1f8e9d1785179">const_filtered_target_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">llvm::iterator_range</a>&lt; <a href="#a645ffe74af11c4c44a76d198c72d3704">const_filtered_target_iterator</a> &gt;</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab30fcca34b584692adb971098d5b7f10">Symbol</a> (EncodeKind Kind, StringRef Name, TargetList Targets, SymbolFlags Flags)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78c2924252433caabd839e89dcbcf0e9">operator==</a> (const Symbol &amp;O) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eb58e1049f6417956bb936efe6bfb0b">operator!=</a> (const Symbol &amp;O) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a519bd05f24100c47b87ca582312aee61">operator&lt;</a> (const Symbol &amp;O) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09eccc83be227a51e00cfd2bfc08c903">addTarget</a> (Target InputTarget)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09ad">EncodeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adff05f497bb6eb5011699a6e9532078a">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8d607765ca383036fe04f640728be0f">getName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/architectureset">ArchitectureSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa2e0c294eb23a41c3490a6cd1cb657b">getArchitectures</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4">SymbolFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3416b4c43641068805c06a658a235f93">getFlags</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34316d3e86024e41a84c08239a65405d">isWeakDefined</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae25e6461883a31fe9dc9868b1af23213">isWeakReferenced</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc768914ca9b9790e825cf96cf701f1">isThreadLocalValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4958630033c0184bc5c6d56ae9be419b">isUndefined</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd877b36d1cab51878cc3c5d29eee69c">isReexported</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05978ef58f3565e7e40ea202098c4caf">isData</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad526f1e4f52f0ed3992733045fc2e088">isText</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39b8dba7bccde15f5e47e50ba5156c1d">hasArchitecture</a> (Architecture Arch) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac91a6307b67f12f0b8224fadb7ee41ab">hasTarget</a> (const Target &amp;Targ) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7d51d76494265bde81e9367afc256271">const_target_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ef249b80cc8eafc8a084608c8c1da19">targets</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a511ecd005cd555a167b1f8e9d1785179">const_filtered_target_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ae31734e36e7d641b8f0645f18c792f">targets</a> (ArchitectureSet architectures) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47fe98cf137102b99ab4844c2860af47">dump</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00c79e2106b482c0f56d9b55ef325348">dump</a> () const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b023543fea6bb6882d944387713b2b">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac089ad7e9e01c5183ce6ba196ed6a9ba">TargetList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf26ebb5674f59ebdb3fff5c87e04c0c">Targets</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09ad">EncodeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8c7fad5b5f0a495b525d39e8298d833">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4">SymbolFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82c8de9a3e68d067a80c29fda81ca940">Flags</a></td>
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


<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_filtered\_target\_iterator {#a645ffe74af11c4c44a76d198c72d3704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachO::Symbol::const_filtered_target_iterator = 
      llvm::filter_iterator&lt;const_target_iterator,
                            std::function&lt;bool(const Target &amp;)&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>

</div>
</div>

### const\_filtered\_target\_range {#a511ecd005cd555a167b1f8e9d1785179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachO::Symbol::const_filtered_target_range = 
      llvm::iterator_range&lt;const_filtered_target_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>

</div>
</div>

### const\_target\_iterator {#a4cb68a6738fcaa9edfd47055cab9bf3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachO::Symbol::const_target_iterator =  TargetList::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>

</div>
</div>

### const\_target\_range {#a7d51d76494265bde81e9367afc256271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachO::Symbol::const_target_range =  llvm::iterator_range&lt;const_target_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Symbol() {#ab30fcca34b584692adb971098d5b7f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::Symbol::Symbol (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09ad">EncodeKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac089ad7e9e01c5183ce6ba196ed6a9ba">TargetList</a> Targets, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4">SymbolFlags</a> Flags)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="#a9eb58e1049f6417956bb936efe6bfb0b">operator!=</a>, <a href="#a519bd05f24100c47b87ca582312aee61">operator&lt;</a> and <a href="#a78c2924252433caabd839e89dcbcf0e9">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a9eb58e1049f6417956bb936efe6bfb0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Symbol::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/symbol">Symbol</a> &amp; O)</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>Reference <a href="#ab30fcca34b584692adb971098d5b7f10">Symbol</a>.</p>

</div>
</div>

### operator&lt;() {#a519bd05f24100c47b87ca582312aee61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Symbol::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/symbol">Symbol</a> &amp; O)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>Reference <a href="#ab30fcca34b584692adb971098d5b7f10">Symbol</a>.</p>

</div>
</div>

### operator==() {#a78c2924252433caabd839e89dcbcf0e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Symbol::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/symbol">Symbol</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/symbol-cpp">Symbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4af6068daa29dbb05a7ead1e3b5a48bbee">llvm::MachO::Data</a>, <a href="#a05978ef58f3565e7e40ea202098c4caf">isData</a>, <a href="#ad526f1e4f52f0ed3992733045fc2e088">isText</a>, <a href="#ab30fcca34b584692adb971098d5b7f10">Symbol</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a9dffbf69ffba8bc38bc4e01abf4b1675">llvm::MachO::Text</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addTarget() {#a09eccc83be227a51e00cfd2bfc08c903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::Symbol::addTarget (<a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a> InputTarget)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a30589972136a4ca44da46ea0045de43d">llvm::MachO::addEntry</a>.</p>

</div>
</div>

### dump() {#a47fe98cf137102b99ab4844c2860af47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void llvm::MachO::Symbol::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/symbol-cpp">Symbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09adac49f2966d60d1973e56e22359e377e68">llvm::MachO::GlobalSymbol</a>, <a href="#a7cc768914ca9b9790e825cf96cf701f1">isThreadLocalValue</a>, <a href="#a4958630033c0184bc5c6d56ae9be419b">isUndefined</a>, <a href="#a34316d3e86024e41a84c08239a65405d">isWeakDefined</a>, <a href="#ae25e6461883a31fe9dc9868b1af23213">isWeakReferenced</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09adabadb331c797ea02208fed9025369cfb1">llvm::MachO::ObjectiveCClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09ada54da6ac4046a5d0d1b4c31bc3dc43247">llvm::MachO::ObjectiveCClassEHType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09ada305fbf91fddce55318beefeb7170a5af">llvm::MachO::ObjectiveCInstanceVariable</a>.</p>

</div>
</div>

### dump() {#a00c79e2106b482c0f56d9b55ef325348}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::Symbol::dump ()</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>References <a href="#a00c79e2106b482c0f56d9b55ef325348">dump</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>.</p>


<p>Referenced by <a href="#a00c79e2106b482c0f56d9b55ef325348">dump</a>.</p>

</div>
</div>

### getArchitectures() {#aaa2e0c294eb23a41c3490a6cd1cb657b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArchitectureSet llvm::MachO::Symbol::getArchitectures ()</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae7b7b478eaa922bb6b4e353e02beb273">llvm::MachO::mapToArchitectureSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits/normalizedtbd-454a2a2b1a47ec9d4c922b4916225c88/#a206ea5b904d2878c644bcf2c3ce32110">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::NormalizedTBD::NormalizedTBD</a>.</p>

</div>
</div>

### getFlags() {#a3416b4c43641068805c06a658a235f93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolFlags llvm::MachO::Symbol::getFlags ()</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a0bf6fb10c8a68470e3b84ab25d8e5c59">accumulateLocs</a>.</p>

</div>
</div>

### getKind() {#adff05f497bb6eb5011699a6e9532078a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EncodeKind llvm::MachO::Symbol::getKind ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits/normalizedtbd-454a2a2b1a47ec9d4c922b4916225c88/#a206ea5b904d2878c644bcf2c3ce32110">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::NormalizedTBD::NormalizedTBD</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits/normalizedtbd-v4-266563df95186142f944822c118e1d06/#af4e0a994d0feae8ef45c2bdb1c16ead2">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::NormalizedTBD_V4::NormalizedTBD_V4</a>.</p>

</div>
</div>

### getName() {#ab8d607765ca383036fe04f640728be0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MachO::Symbol::getName ()</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a0bf6fb10c8a68470e3b84ab25d8e5c59">accumulateLocs</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits/normalizedtbd-454a2a2b1a47ec9d4c922b4916225c88/#a206ea5b904d2878c644bcf2c3ce32110">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::NormalizedTBD::NormalizedTBD</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits/normalizedtbd-v4-266563df95186142f944822c118e1d06/#af4e0a994d0feae8ef45c2bdb1c16ead2">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::NormalizedTBD_V4::NormalizedTBD_V4</a>.</p>

</div>
</div>

### hasArchitecture() {#a39b8dba7bccde15f5e47e50ba5156c1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Symbol::hasArchitecture (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a70477e3fc02b7dbfd59604af47d88397">Architecture</a> Arch)</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/macho/architectureset/#a93801a3e0055a049cfd51bbb389ee8d2">llvm::MachO::ArchitectureSet::contains</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae7b7b478eaa922bb6b4e353e02beb273">llvm::MachO::mapToArchitectureSet</a>.</p>

</div>
</div>

### hasTarget() {#ac91a6307b67f12f0b8224fadb7ee41ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Symbol::hasTarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a> &amp; Targ)</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>

</div>
</div>

### isData() {#a05978ef58f3565e7e40ea202098c4caf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Symbol::isData ()</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4af6068daa29dbb05a7ead1e3b5a48bbee">llvm::MachO::Data</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a> and <a href="#a78c2924252433caabd839e89dcbcf0e9">operator==</a>.</p>

</div>
</div>

### isReexported() {#afd877b36d1cab51878cc3c5d29eee69c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Symbol::isReexported ()</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a6994917dfcfb9ef55fc6bce4b454f9a4">llvm::MachO::Rexported</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/symbolset/#af76f0fcf4226d6022d1681ae205c3d9d">llvm::MachO::SymbolSet::exports</a> and <a href="/web-llvm/docs/api/classes/llvm/macho/symbolset/#adac2aff39455cd2fbcff6b2b42ae9c1b">llvm::MachO::SymbolSet::reexports</a>.</p>

</div>
</div>

### isText() {#ad526f1e4f52f0ed3992733045fc2e088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Symbol::isText ()</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a9dffbf69ffba8bc38bc4e01abf4b1675">llvm::MachO::Text</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a> and <a href="#a78c2924252433caabd839e89dcbcf0e9">operator==</a>.</p>

</div>
</div>

### isThreadLocalValue() {#a7cc768914ca9b9790e825cf96cf701f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Symbol::isThreadLocalValue ()</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a4514e0ecc0bca43f5fa805abf7d7f1da">llvm::MachO::ThreadLocalValue</a>.</p>


<p>Referenced by <a href="#a47fe98cf137102b99ab4844c2860af47">dump</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits/normalizedtbd-454a2a2b1a47ec9d4c922b4916225c88/#a206ea5b904d2878c644bcf2c3ce32110">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::NormalizedTBD::NormalizedTBD</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits/normalizedtbd-v4-266563df95186142f944822c118e1d06/#af4e0a994d0feae8ef45c2bdb1c16ead2">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::NormalizedTBD_V4::NormalizedTBD_V4</a>.</p>

</div>
</div>

### isUndefined() {#a4958630033c0184bc5c6d56ae9be419b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Symbol::isUndefined ()</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4aec0fc0100c4fc1ce4eea230c3dc10360">llvm::MachO::Undefined</a>.</p>


<p>Referenced by <a href="#a47fe98cf137102b99ab4844c2860af47">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/symbolset/#af76f0fcf4226d6022d1681ae205c3d9d">llvm::MachO::SymbolSet::exports</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a7a3ba7cd94762ae7f243367830320ca2">getFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/macho/symbolset/#ac05d508e1d549e9a85a442746965b79c">llvm::MachO::SymbolSet::undefineds</a>.</p>

</div>
</div>

### isWeakDefined() {#a34316d3e86024e41a84c08239a65405d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Symbol::isWeakDefined ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a97a89195303306e8a5bacadf960312a9">llvm::MachO::WeakDefined</a>.</p>


<p>Referenced by <a href="#a47fe98cf137102b99ab4844c2860af47">dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a7a3ba7cd94762ae7f243367830320ca2">getFlags</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits/normalizedtbd-454a2a2b1a47ec9d4c922b4916225c88/#a206ea5b904d2878c644bcf2c3ce32110">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::NormalizedTBD::NormalizedTBD</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits/normalizedtbd-v4-266563df95186142f944822c118e1d06/#af4e0a994d0feae8ef45c2bdb1c16ead2">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::NormalizedTBD_V4::NormalizedTBD_V4</a>.</p>

</div>
</div>

### isWeakReferenced() {#ae25e6461883a31fe9dc9868b1af23213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Symbol::isWeakReferenced ()</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a7c73b1797e3f46eb2dcb9d8d2d75805b">llvm::MachO::WeakReferenced</a>.</p>


<p>Referenced by <a href="#a47fe98cf137102b99ab4844c2860af47">dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a7a3ba7cd94762ae7f243367830320ca2">getFlags</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits/normalizedtbd-454a2a2b1a47ec9d4c922b4916225c88/#a206ea5b904d2878c644bcf2c3ce32110">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::NormalizedTBD::NormalizedTBD</a>.</p>

</div>
</div>

### targets() {#a6ef249b80cc8eafc8a084608c8c1da19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_target_range llvm::MachO::Symbol::targets ()</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits/normalizedtbd-v4-266563df95186142f944822c118e1d06/#af4e0a994d0feae8ef45c2bdb1c16ead2">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::NormalizedTBD_V4::NormalizedTBD_V4</a>.</p>

</div>
</div>

### targets() {#a4ae31734e36e7d641b8f0645f18c792f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol::const_filtered_target_range llvm::MachO::Symbol::targets (<a href="/web-llvm/docs/api/classes/llvm/macho/architectureset">ArchitectureSet</a> architectures)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/symbol-cpp">Symbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/macho/target/#aee9dc737c9effa286ef632263cd45696">llvm::MachO::Target::Arch</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/architectureset/#a76b67e4256ae13907721adbb0762ab78">llvm::MachO::ArchitectureSet::has</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a898e9304cf2baf908f4e9b8e32a5f6c3">llvm::make_filter_range</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Flags {#a82c8de9a3e68d067a80c29fda81ca940}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolFlags llvm::MachO::Symbol::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>

</div>
</div>

### Kind {#ac8c7fad5b5f0a495b525d39e8298d833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EncodeKind llvm::MachO::Symbol::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>

</div>
</div>

### Name {#a05b023543fea6bb6882d944387713b2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MachO::Symbol::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>

</div>
</div>

### Targets {#adf26ebb5674f59ebdb3fff5c87e04c0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetList llvm::MachO::Symbol::Targets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">Symbol.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/textapi/symbol-cpp">Symbol.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
