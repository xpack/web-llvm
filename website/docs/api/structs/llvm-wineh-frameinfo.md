---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/wineh/frameinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `FrameInfo` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::WinEH::FrameInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">llvm/MC/MCWinEH.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99b4d65fed17643004aef30de74b6f3a">FrameInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad577ef9f001f4eec9cb8434c04e1d956">FrameInfo</a> (const MCSymbol *Function, const MCSymbol *BeginFuncEHLabel)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae68026479697de730a34557441d2d53a">FrameInfo</a> (const MCSymbol *Function, const MCSymbol *BeginFuncEHLabel, const FrameInfo *ChainedParent)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03525ff768a7ec69a2baf044fc08e997">empty</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add6c47bdc7646fede29dd8261f2bd5b7">Begin</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a903feaabd8052ae8912489b117410c0b">End</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dbf869e6530d63af83a9670c54d5988">FuncletOrFuncEnd</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedf13f4ef70fa51f00bb5630a614a3a2">ExceptionHandler</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22c0c4f7c23db94945872dfe14fa32bc">Function</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61dd603885e6fe75a133f68362c82c2d">PrologEnd</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61cf7c2aab4a6985807c42686899ae11">Symbol</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b99476d993dc06160c03b820cc94b11">TextSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4ce38e457009b1f214c63454c08958a">PackedInfo</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7afd01679ade4abb228236918b841fd7">PrologCodeBytes</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b87fca779478e43ebc01beea784f589">HandlesUnwind</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17e287f93ec6896736889b79ee26fe5c">HandlesExceptions</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5823df1f97d15c85da77a30f3b71b79">EmitAttempted</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3776ac8b64dde3227ee94d7901096cfb">Fragment</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34ce7a08ba73569d91074067557badcb">LastFrameInst</a> = -1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">FrameInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3a22752aee826b818d5551d6e8223f8">ChainedParent</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">Instruction</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10bcb4d81ba20e479977a46859383c93">Instructions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/epilog">Epilog</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7364f28eaaef25fb43890373f3792a01">EpilogMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/segment">Segment</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16603099b2a10291380ad0d6f4c27500">Segments</a></td>
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


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FrameInfo() {#a99b4d65fed17643004aef30de74b6f3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WinEH::FrameInfo::FrameInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>Referenced by <a href="#ae68026479697de730a34557441d2d53a">FrameInfo</a>.</p>

</div>
</div>

### FrameInfo() {#ad577ef9f001f4eec9cb8434c04e1d956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WinEH::FrameInfo::FrameInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Function, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * BeginFuncEHLabel)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>References <a href="#add6c47bdc7646fede29dd8261f2bd5b7">Begin</a> and <a href="#a22c0c4f7c23db94945872dfe14fa32bc">Function</a>.</p>

</div>
</div>

### FrameInfo() {#ae68026479697de730a34557441d2d53a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WinEH::FrameInfo::FrameInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Function, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * BeginFuncEHLabel, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">FrameInfo</a> * ChainedParent)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>References <a href="#add6c47bdc7646fede29dd8261f2bd5b7">Begin</a>, <a href="#ad3a22752aee826b818d5551d6e8223f8">ChainedParent</a>, <a href="#a99b4d65fed17643004aef30de74b6f3a">FrameInfo</a> and <a href="#a22c0c4f7c23db94945872dfe14fa32bc">Function</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### empty() {#a03525ff768a7ec69a2baf044fc08e997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WinEH::FrameInfo::empty ()</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a7364f28eaaef25fb43890373f3792a01">EpilogMap</a> and <a href="#a10bcb4d81ba20e479977a46859383c93">Instructions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Begin {#add6c47bdc7646fede29dd8261f2bd5b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol* llvm::WinEH::FrameInfo::Begin = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>Referenced by <a href="#ad577ef9f001f4eec9cb8434c04e1d956">FrameInfo</a> and <a href="#ae68026479697de730a34557441d2d53a">FrameInfo</a>.</p>

</div>
</div>

### ChainedParent {#ad3a22752aee826b818d5551d6e8223f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FrameInfo* llvm::WinEH::FrameInfo::ChainedParent = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9b6d232a4258f0dd9f16ee5b4f558633">llvm::MCStreamer::emitWinCFIEndChained</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9d158c6b4a4302d51fd73aac4075086d">llvm::MCStreamer::emitWinCFIEndProc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aac38128831e5c5377b98fd32d4f53fc9">llvm::MCStreamer::emitWinCFIFuncletOrFuncEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a26b51b14a3b7ce5cd6abe0c45872dd60">llvm::MCStreamer::emitWinEHHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a4e42517f705e57c03ce078fcac4e8f19">llvm::MCStreamer::emitWinEHHandlerData</a> and <a href="#ae68026479697de730a34557441d2d53a">FrameInfo</a>.</p>

</div>
</div>

### EmitAttempted {#af5823df1f97d15c85da77a30f3b71b79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WinEH::FrameInfo::EmitAttempted = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>

</div>
</div>

### End {#a903feaabd8052ae8912489b117410c0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol* llvm::WinEH::FrameInfo::End = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9b6d232a4258f0dd9f16ee5b4f558633">llvm::MCStreamer::emitWinCFIEndChained</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9d158c6b4a4302d51fd73aac4075086d">llvm::MCStreamer::emitWinCFIEndProc</a>.</p>

</div>
</div>

### EpilogMap {#a7364f28eaaef25fb43890373f3792a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;MCSymbol *, Epilog&gt; llvm::WinEH::FrameInfo::EpilogMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetwincoffstreamer/#a393a06808d7164ea609545fb512d9e58">llvm::AArch64TargetWinCOFFStreamer::emitARM64WinCFIEpilogEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-armwincoffstreamer-cpp-/armtargetwincoffstreamer/#ab470d8aa53480de68554a22812342ca7">anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::emitARMWinCFIEpilogEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-armwincoffstreamer-cpp-/armtargetwincoffstreamer/#a3c29f346d739538a5d4d77e4f3820cdf">anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::emitARMWinCFIEpilogStart</a> and <a href="#a03525ff768a7ec69a2baf044fc08e997">empty</a>.</p>

</div>
</div>

### ExceptionHandler {#aedf13f4ef70fa51f00bb5630a614a3a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol* llvm::WinEH::FrameInfo::ExceptionHandler = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a26b51b14a3b7ce5cd6abe0c45872dd60">llvm::MCStreamer::emitWinEHHandler</a>.</p>

</div>
</div>

### Fragment {#a3776ac8b64dde3227ee94d7901096cfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WinEH::FrameInfo::Fragment = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armwincoffstreamer-cpp-/armtargetwincoffstreamer/#a0a5b841afcea044cefa812e4cd4b30d5">anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::emitARMWinCFIPrologEnd</a>.</p>

</div>
</div>

### FuncletOrFuncEnd {#a7dbf869e6530d63af83a9670c54d5988}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol* llvm::WinEH::FrameInfo::FuncletOrFuncEnd = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9d158c6b4a4302d51fd73aac4075086d">llvm::MCStreamer::emitWinCFIEndProc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aac38128831e5c5377b98fd32d4f53fc9">llvm::MCStreamer::emitWinCFIFuncletOrFuncEnd</a>.</p>

</div>
</div>

### Function {#a22c0c4f7c23db94945872dfe14fa32bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol* llvm::WinEH::FrameInfo::Function = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armwincoffstreamer-cpp-/armtargetwincoffstreamer/#ab470d8aa53480de68554a22812342ca7">anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::emitARMWinCFIEpilogEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af4abf3b216995cecfbe8fcbc05d5b128">llvm::MCStreamer::emitWinCFIStartChained</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a27ab1f18a7bff8a82c03e03302227f0d">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinEHHandlerData</a>, <a href="#ad577ef9f001f4eec9cb8434c04e1d956">FrameInfo</a> and <a href="#ae68026479697de730a34557441d2d53a">FrameInfo</a>.</p>

</div>
</div>

### HandlesExceptions {#a17e287f93ec6896736889b79ee26fe5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WinEH::FrameInfo::HandlesExceptions = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a26b51b14a3b7ce5cd6abe0c45872dd60">llvm::MCStreamer::emitWinEHHandler</a>.</p>

</div>
</div>

### HandlesUnwind {#a7b87fca779478e43ebc01beea784f589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WinEH::FrameInfo::HandlesUnwind = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a26b51b14a3b7ce5cd6abe0c45872dd60">llvm::MCStreamer::emitWinEHHandler</a>.</p>

</div>
</div>

### Instructions {#a10bcb4d81ba20e479977a46859383c93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Instruction&gt; llvm::WinEH::FrameInfo::Instructions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetwincoffstreamer/#a24c3ab65df16c2db885c7f0e89ce53ee">llvm::AArch64TargetWinCOFFStreamer::emitARM64WinCFIPrologEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-armwincoffstreamer-cpp-/armtargetwincoffstreamer/#a0a5b841afcea044cefa812e4cd4b30d5">anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::emitARMWinCFIPrologEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ad9bb2bc90c804c28497604ae91e27bd7">llvm::MCStreamer::emitWinCFIAllocStack</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a4c579bc3d70f8f348c3ddf8224a31220">llvm::MCStreamer::emitWinCFIPushFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a1d0c21ad8ad54697f00aab2c37d77e25">llvm::MCStreamer::emitWinCFIPushReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9a30cc0783819b780c3e357162b90aec">llvm::MCStreamer::emitWinCFISaveReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a5755faab671780e6c1abcaa95f05fe0b">llvm::MCStreamer::emitWinCFISaveXMM</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acd1f092159870d525f916e3296341d92">llvm::MCStreamer::emitWinCFISetFrame</a> and <a href="#a03525ff768a7ec69a2baf044fc08e997">empty</a>.</p>

</div>
</div>

### LastFrameInst {#a34ce7a08ba73569d91074067557badcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::WinEH::FrameInfo::LastFrameInst = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acd1f092159870d525f916e3296341d92">llvm::MCStreamer::emitWinCFISetFrame</a>.</p>

</div>
</div>

### PackedInfo {#ac4ce38e457009b1f214c63454c08958a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::WinEH::FrameInfo::PackedInfo = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>

</div>
</div>

### PrologCodeBytes {#a7afd01679ade4abb228236918b841fd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::WinEH::FrameInfo::PrologCodeBytes = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>

</div>
</div>

### PrologEnd {#a61dd603885e6fe75a133f68362c82c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol* llvm::WinEH::FrameInfo::PrologEnd = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetwincoffstreamer/#a24c3ab65df16c2db885c7f0e89ce53ee">llvm::AArch64TargetWinCOFFStreamer::emitARM64WinCFIPrologEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-armwincoffstreamer-cpp-/armtargetwincoffstreamer/#a0a5b841afcea044cefa812e4cd4b30d5">anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::emitARMWinCFIPrologEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9b9f4aa69270161dc91d76e3080e6dd2">llvm::MCStreamer::emitWinCFIEndProlog</a>.</p>

</div>
</div>

### Segments {#a16603099b2a10291380ad0d6f4c27500}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Segment&gt; llvm::WinEH::FrameInfo::Segments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>

</div>
</div>

### Symbol {#a61cf7c2aab4a6985807c42686899ae11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol* llvm::WinEH::FrameInfo::Symbol = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>

</div>
</div>

### TextSection {#a4b99476d993dc06160c03b820cc94b11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::WinEH::FrameInfo::TextSection = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9d158c6b4a4302d51fd73aac4075086d">llvm::MCStreamer::emitWinCFIEndProc</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
