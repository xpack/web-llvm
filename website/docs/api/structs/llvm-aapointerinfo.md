---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/aapointerinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AAPointerInfo` Struct Reference

<p>An abstract interface for struct information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AAPointerInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">llvm/Transforms/IPO/Attributor.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base struct for all "concrete attribute" deductions. <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/statewrapper">StateWrapper&lt;StateTy, BaseType, Ts&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to tie a abstract state implementation to an abstract attribute. <a href="/web-llvm/docs/api/structs/llvm/statewrapper/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bd5350ba0828a918b5459f90ac037c4">OffsetBinsTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/aa/rangety">AA::RangeTy</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; unsigned, 4 &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e84a44b3b77bd1e127e7eca539393d7">const_bin_iterator</a> = OffsetBinsTy::const_iterator</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AccessKind { <a href="#a78c4e7148167329c362738ab01ebdda1">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1d0686143c13ac3502bf10cd9e32aad">AAPointerInfo</a> (const IRPosition &amp;IRP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9702a0df8e3f5ca698eaedd9c028105">getName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a7d84d85c6cb8cc16db41d83859096256">AbstractAttribute::getName()</a> <a href="#ab9702a0df8e3f5ca698eaedd9c028105">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d5a551181f96e0e64742f5bff23681a">getIdAddr</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#afb1ae982372c7bd88717c53d8f8e5470">AbstractAttribute::getIdAddr()</a> <a href="#a4d5a551181f96e0e64742f5bff23681a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3e84a44b3b77bd1e127e7eca539393d7">const_bin_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5673f3b8ca891f85c918452765baccfd">begin</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3e84a44b3b77bd1e127e7eca539393d7">const_bin_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8de692a55ce3b994535f992df8f190d7">end</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae59c3441fee38eb5c5917caf1e0b5781">numOffsetBins</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a178f1ef05dd148af35b47b60f01c5ab6">reachesReturn</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ffbaabec427f3e4a97d6a5f73261ba7">addReturnedOffsetsTo</a> (OffsetInfo &amp;) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e074b029fa7e785f9836fdc15ef50e2">forallInterferingAccesses</a> (AA::RangeTy Range, function_ref&lt; bool(const Access &amp;, bool)&gt; CB) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call <span class="doxyComputerOutput">CB</span> on all accesses that might interfere with <span class="doxyComputerOutput">Range</span> and return true if all such accesses were known and the callback returned true for all of them, false otherwise. <a href="#a7e074b029fa7e785f9836fdc15ef50e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fc4e79b3bc9fd157cd7a6d30ab9d131">forallInterferingAccesses</a> (Attributor &amp;A, const AbstractAttribute &amp;QueryingAA, Instruction &amp;I, bool FindInterferingWrites, bool FindInterferingReads, function_ref&lt; bool(const Access &amp;, bool)&gt; CB, bool &amp;HasBeenWrittenTo, AA::RangeTy &amp;Range, function_ref&lt; bool(const Access &amp;)&gt; SkipCB=nullptr) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call <span class="doxyComputerOutput">CB</span> on all accesses that might interfere with <span class="doxyComputerOutput">I</span> and return true if all such accesses were known and the callback returned true for all of them, false otherwise. <a href="#a1fc4e79b3bc9fd157cd7a6d30ab9d131">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07bee2e824c483aa3d14d1d3aeacd7f3">isValidIRPositionForInit</a> (Attributor &amp;A, const IRPosition &amp;IRP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a0b23d1cedd8202d1b786e1ab43313084">AbstractAttribute::isValidIRPositionForInit</a>. <a href="#a07bee2e824c483aa3d14d1d3aeacd7f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo">AAPointerInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51f4e749de90e7db3a83c68ee08896ed">createForPosition</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an abstract attribute view for the position <span class="doxyComputerOutput">IRP</span>. <a href="#a51f4e749de90e7db3a83c68ee08896ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38b5effb3f749dc2a249c2ab3c96bcc2">classof</a> (const AbstractAttribute *AA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function should return true if the type of the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a></span> is <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo">AAPointerInfo</a>. <a href="#a38b5effb3f749dc2a249c2ab3c96bcc2">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a36782a6cc5e2ac495b3e2d2ff974c">ID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unique ID (due to the unique address) <a href="#ac1a36782a6cc5e2ac495b3e2d2ff974c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An abstract interface for struct information.</p>

<p>Definition at line 5763 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_bin\_iterator {#a3e84a44b3b77bd1e127e7eca539393d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AAPointerInfo::const_bin_iterator =  OffsetBinsTy::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 6176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### OffsetBinsTy {#a6bd5350ba0828a918b5459f90ac037c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AAPointerInfo::OffsetBinsTy =  DenseMap&lt;AA::RangeTy, SmallSet&lt;unsigned, 4&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 6175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### AccessKind {#a78c4e7148167329c362738ab01ebdda1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AAPointerInfo::AccessKind </td>
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
<td class="doxyEnumItemName">AK_MUST<a id="a78c4e7148167329c362738ab01ebdda1a54020ed18b5ad8c231c81baa173aad83"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AK_MAY<a id="a78c4e7148167329c362738ab01ebdda1a1e154051f64c29dc28598977dc56ae92"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AK_R<a id="a78c4e7148167329c362738ab01ebdda1a3dd50dec5233b17dc99e213fa2368431"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AK_W<a id="a78c4e7148167329c362738ab01ebdda1a7006125de3a586d539eaa6abfba0b83f"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AK_RW<a id="a78c4e7148167329c362738ab01ebdda1addc8a1504a2cac4a232e96beafb0bd5e"></a></td>
<td class="doxyEnumItemDescription"> (= AK_R | AK_W)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AK_ASSUMPTION<a id="a78c4e7148167329c362738ab01ebdda1aebade1d780c0c4b8813b15177e7c5724"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 4) | AK_MUST)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AK_MAY_READ<a id="a78c4e7148167329c362738ab01ebdda1a0abfed97806477a750c49a735a122d47"></a></td>
<td class="doxyEnumItemDescription"> (= AK_MAY | AK_R)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AK_MAY_WRITE<a id="a78c4e7148167329c362738ab01ebdda1a914ddd376261c63cf37261b6d077583e"></a></td>
<td class="doxyEnumItemDescription"> (= AK_MAY | AK_W)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AK_MAY_READ_WRITE<a id="a78c4e7148167329c362738ab01ebdda1aadbc7239a48d28033f3d83a4484686e4"></a></td>
<td class="doxyEnumItemDescription"> (= AK_MAY | AK_R | AK_W)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AK_MUST_READ<a id="a78c4e7148167329c362738ab01ebdda1aa554ef836e2edbc38d5f3b86fb4a5c1a"></a></td>
<td class="doxyEnumItemDescription"> (= AK_MUST | AK_R)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AK_MUST_WRITE<a id="a78c4e7148167329c362738ab01ebdda1afe8a47570ee003ad1847ae7c2470e48c"></a></td>
<td class="doxyEnumItemDescription"> (= AK_MUST | AK_W)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AK_MUST_READ_WRITE<a id="a78c4e7148167329c362738ab01ebdda1a6273ea05bff344a96d47e5a3a46613b1"></a></td>
<td class="doxyEnumItemDescription"> (= AK_MUST | AK_R | AK_W)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 5773 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AAPointerInfo() {#ad1d0686143c13ac3502bf10cd9e32aad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AAPointerInfo::AAPointerInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP)</td>
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



<p>Definition at line 5764 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#acff34214cf426db8b010a1d977bd2899">llvm::AbstractAttribute::AbstractAttribute</a>.</p>


<p>Referenced by <a href="#a51f4e749de90e7db3a83c68ee08896ed">createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#afa9d4327193a1cc24ab70233ec67af82">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::translateAndAddState</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a42a2b649b3ebe7e9cf882d260685c9d0">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::translateAndAddStateFromCallee</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addReturnedOffsetsTo() {#a2ffbaabec427f3e4a97d6a5f73261ba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::AAPointerInfo::addReturnedOffsetsTo (<a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/offsetinfo">OffsetInfo</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 6181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### begin() {#a5673f3b8ca891f85c918452765baccfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const_bin_iterator llvm::AAPointerInfo::begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 6177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaallocationinfoimpl/#ae66a50449dec20c1a137f704e5e2c949">anonymous{AttributorAttributes.cpp}::AAAllocationInfoImpl::updateImpl</a>.</p>

</div>
</div>

### end() {#a8de692a55ce3b994535f992df8f190d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const_bin_iterator llvm::AAPointerInfo::end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 6178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### forallInterferingAccesses() {#a7e074b029fa7e785f9836fdc15ef50e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AAPointerInfo::forallInterferingAccesses (<a href="/web-llvm/docs/api/structs/llvm/aa/rangety">AA::RangeTy</a> Range, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access">Access</a> &amp;, bool)&gt; CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Call <span class="doxyComputerOutput">CB</span> on all accesses that might interfere with <span class="doxyComputerOutput">Range</span> and return true if all such accesses were known and the callback returned true for all of them, false otherwise.</p>


<p>An access interferes with an offset-size pair if it might read or write that memory region.</p>


<p>Definition at line 6187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

### forallInterferingAccesses() {#a1fc4e79b3bc9fd157cd7a6d30ab9d131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AAPointerInfo::forallInterferingAccesses (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, bool FindInterferingWrites, bool FindInterferingReads, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access">Access</a> &amp;, bool)&gt; CB, bool &amp; HasBeenWrittenTo, <a href="/web-llvm/docs/api/structs/llvm/aa/rangety">AA::RangeTy</a> &amp; Range, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access">Access</a> &amp;)&gt; SkipCB=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Call <span class="doxyComputerOutput">CB</span> on all accesses that might interfere with <span class="doxyComputerOutput">I</span> and return true if all such accesses were known and the callback returned true for all of them, false otherwise.</p>


<p>In contrast to forallInterferingAccesses this function will perform reasoning to exclude write accesses that cannot affect the load even if they on the surface look as if they would. The flag <span class="doxyComputerOutput">HasBeenWrittenTo</span> will be set to true if we know that <span class="doxyComputerOutput">I</span> does not read the initial value of the underlying memory. If <span class="doxyComputerOutput">SkipCB</span> is given and returns false for a potentially interfering access, that access is not checked for actual interference.</p>


<p>Definition at line 6199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#acff34214cf426db8b010a1d977bd2899">llvm::AbstractAttribute::AbstractAttribute</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

### getIdAddr() {#a4d5a551181f96e0e64742f5bff23681a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::AAPointerInfo::getIdAddr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#afb1ae982372c7bd88717c53d8f8e5470">AbstractAttribute::getIdAddr()</a></p>

<p>Definition at line 6173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#ac1a36782a6cc5e2ac495b3e2d2ff974c">ID</a>.</p>

</div>
</div>

### getName() {#ab9702a0df8e3f5ca698eaedd9c028105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string llvm::AAPointerInfo::getName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a7d84d85c6cb8cc16db41d83859096256">AbstractAttribute::getName()</a></p>

<p>Definition at line 6170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### numOffsetBins() {#ae59c3441fee38eb5c5917caf1e0b5781}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int64_t llvm::AAPointerInfo::numOffsetBins ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 6179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaallocationinfoimpl/#ae66a50449dec20c1a137f704e5e2c949">anonymous{AttributorAttributes.cpp}::AAAllocationInfoImpl::updateImpl</a>.</p>

</div>
</div>

### reachesReturn() {#a178f1ef05dd148af35b47b60f01c5ab6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AAPointerInfo::reachesReturn ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 6180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaallocationinfoimpl/#ae66a50449dec20c1a137f704e5e2c949">anonymous{AttributorAttributes.cpp}::AAAllocationInfoImpl::updateImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a38b5effb3f749dc2a249c2ab3c96bcc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAPointerInfo::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> * AA)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function should return true if the type of the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a></span> is <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo">AAPointerInfo</a>.</p>

<p>Definition at line 6207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#acff34214cf426db8b010a1d977bd2899">llvm::AbstractAttribute::AbstractAttribute</a> and <a href="#ac1a36782a6cc5e2ac495b3e2d2ff974c">ID</a>.</p>

</div>
</div>

### createForPosition() {#a51f4e749de90e7db3a83c68ee08896ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAPointerInfo &amp; llvm::AAPointerInfo::createForPosition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>Create an abstract attribute view for the position <span class="doxyComputerOutput">IRP</span>.</p>

<p>Definition at line 6167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#ad1d0686143c13ac3502bf10cd9e32aad">AAPointerInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>.</p>

</div>
</div>

### isValidIRPositionForInit() {#a07bee2e824c483aa3d14d1d3aeacd7f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAPointerInfo::isValidIRPositionForInit (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a0b23d1cedd8202d1b786e1ab43313084">AbstractAttribute::isValidIRPositionForInit</a>.</p>

<p>Definition at line 5767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a6a0e4ff765ad5ab3c9a53c917f3cf1cd">llvm::IRPosition::getAssociatedType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ab03652069eab17006c51f00c261a6a44">llvm::Type::isPtrOrPtrVectorTy</a> and <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a0b23d1cedd8202d1b786e1ab43313084">llvm::AbstractAttribute::isValidIRPositionForInit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#ac1a36782a6cc5e2ac495b3e2d2ff974c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char AAPointerInfo::ID = 0</td>
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

<p>Unique ID (due to the unique address)</p>

<p>Definition at line 6212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="#a38b5effb3f749dc2a249c2ab3c96bcc2">classof</a>, <a href="#a4d5a551181f96e0e64742f5bff23681a">getIdAddr</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuattributor-cpp-/#a54acd54cc3db43b11d42ebf210d08cf7">anonymous{AMDGPUAttributor.cpp}::runImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
