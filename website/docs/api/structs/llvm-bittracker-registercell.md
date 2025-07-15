---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/bittracker/registercell
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RegisterCell` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::BitTracker::RegisterCell { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">Target/Hexagon/BitTracker.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8320d1f380f10d66b6c2325e138b4849">BitValueList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue">BitValue</a>, DefaultBitN &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a125f77300db175faeae41d9a628194d6">operator&lt;&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade4e536d21151ec1516845f0a6d6ac89">RegisterCell</a> (uint16_t Width=DefaultBitN)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue">BitValue</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cd20ee15cb9c93777b1ee3ec5c39bdc">operator[]</a> (uint16_t BitN) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue">BitValue</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b73bd6a1040929fe96ce52965e5bf9a">operator[]</a> (uint16_t BitN)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab599ca7f603b5faf8d74dfe154e978ab">operator==</a> (const RegisterCell &amp;RC) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d7f03dba2648288309073b55d251b4f">operator!=</a> (const RegisterCell &amp;RC) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56acc95a5fa4a319c87879ce52766595">width</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8767a2aae4c035e715b572ce4b4c5acd">meet</a> (const RegisterCell &amp;RC, Register SelfR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab436b1402523817d32ee31d1d7eb7a0c">insert</a> (const RegisterCell &amp;RC, const BitMask &amp;M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a900f393e2eebd18ebe5696a0b5d309e5">extract</a> (const BitMask &amp;M) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae272af7a7e6e5254fca24ec9fc2ed91c">rol</a> (uint16_t Sh)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79b7d643ade1a355ff1b560a6d86a5c3">fill</a> (uint16_t B, uint16_t E, const BitValue &amp;V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1385460950e6fe590c5913ba8c9dbe90">cat</a> (const RegisterCell &amp;RC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9770ab6f8b5455a3a84789a4ef8e94d">cl</a> (bool B) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3fa9c47bf9d313125b4dbe582b2eaad">ct</a> (bool B) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6e2cfce750a7dddf5e3bc60ad55f1b1">regify</a> (unsigned R)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">BitValueList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec64a10873f270edcbf62780f8306039">Bits</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b372ece8559169470a7fcfb471c2302">self</a> (unsigned Reg, uint16_t Width)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab51d511c99890c779e2853504511f7d7">top</a> (uint16_t Width)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e73984cdacfb5cd24df684bbe6af7a7">ref</a> (const RegisterCell &amp;C)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe573749c131acb1c25025fbe01b0384">DefaultBitN</a> = 32</td>
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


<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BitValueList {#a8320d1f380f10d66b6c2325e138b4849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BitTracker::RegisterCell::BitValueList =  SmallVector&lt;BitValue, DefaultBitN&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### operator&lt;&lt; {#a125f77300db175faeae41d9a628194d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; RC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitref/#ab66cddedf2717fe3649ae4aecc6232c5">llvm::BitTracker::BitRef::Pos</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a6430b3f9e35d7d7e83399a565cfd143e">llvm::BitTracker::BitValue::RefI</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitref/#a40e257127c0ff61f7ce778d68468096c">llvm::BitTracker::BitRef::Reg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a093eda80cf560688e6c3578e8b7fd674">llvm::BitTracker::BitValue::Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RegisterCell() {#ade4e536d21151ec1516845f0a6d6ac89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitTracker::RegisterCell::RegisterCell (uint16_t Width=DefaultBitN)</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>Referenced by <a href="#a1385460950e6fe590c5913ba8c9dbe90">cat</a>, <a href="#a900f393e2eebd18ebe5696a0b5d309e5">extract</a>, <a href="#a8767a2aae4c035e715b572ce4b4c5acd">meet</a>, <a href="#a2d7f03dba2648288309073b55d251b4f">operator!=</a>, <a href="#ab599ca7f603b5faf8d74dfe154e978ab">operator==</a>, <a href="#a4e73984cdacfb5cd24df684bbe6af7a7">ref</a>, <a href="#ae272af7a7e6e5254fca24ec9fc2ed91c">rol</a>, <a href="#a4b372ece8559169470a7fcfb471c2302">self</a> and <a href="#ab51d511c99890c779e2853504511f7d7">top</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a2d7f03dba2648288309073b55d251b4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitTracker::RegisterCell::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; RC)</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/mergedfunctionsinfo-cpp/#ad5db311411b09e79fcad62e7cee12e6b">operator==</a> and <a href="#ade4e536d21151ec1516845f0a6d6ac89">RegisterCell</a>.</p>

</div>
</div>

### operator\[\]() {#a5cd20ee15cb9c93777b1ee3ec5c39bdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BitValue &amp; llvm::BitTracker::RegisterCell::operator[] (uint16_t BitN)</td>
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



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### operator\[\]() {#a3b73bd6a1040929fe96ce52965e5bf9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitValue &amp; llvm::BitTracker::RegisterCell::operator[] (uint16_t BitN)</td>
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



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### operator==() {#ab599ca7f603b5faf8d74dfe154e978ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BT::RegisterCell::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="#ade4e536d21151ec1516845f0a6d6ac89">RegisterCell</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### cat() {#a1385460950e6fe590c5913ba8c9dbe90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell &amp; BT::RegisterCell::cat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="#ade4e536d21151ec1516845f0a6d6ac89">RegisterCell</a> and <a href="#a56acc95a5fa4a319c87879ce52766595">width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### cl() {#ad9770ab6f8b5455a3a84789a4ef8e94d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t BT::RegisterCell::cl (bool B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a56acc95a5fa4a319c87879ce52766595">width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a6a2e09403daa9d3a9d40a68895e90aa9">llvm::BitTracker::MachineEvaluator::eCLB</a>.</p>

</div>
</div>

### ct() {#ab3fa9c47bf9d313125b4dbe582b2eaad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t BT::RegisterCell::ct (bool B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a56acc95a5fa4a319c87879ce52766595">width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a8fa571f010447594afbfb0dd92cdb917">llvm::BitTracker::MachineEvaluator::eCTB</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a6032f746ffa25df648aa38680d1e891e">llvm::BitTracker::MachineEvaluator::eMLS</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a518631233431d2324f15075cf91ffab2">llvm::BitTracker::MachineEvaluator::eMLU</a>.</p>

</div>
</div>

### extract() {#a900f393e2eebd18ebe5696a0b5d309e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::RegisterCell::extract (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitmask">BitMask</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ade4e536d21151ec1516845f0a6d6ac89">RegisterCell</a> and <a href="#a56acc95a5fa4a319c87879ce52766595">width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#aefa1e921dff52ae9ac378bf26a32b4d2">llvm::BitTracker::MachineEvaluator::eXTR</a>.</p>

</div>
</div>

### fill() {#a79b7d643ade1a355ff1b560a6d86a5c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell &amp; BT::RegisterCell::fill (uint16_t B, uint16_t E, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue">BitValue</a> &amp; V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a86f3525b5df439dd04caea2c1d4f567d">llvm::BitTracker::MachineEvaluator::eASL</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a83c32395e0a0c8e1d12e4dbdc5483928">llvm::BitTracker::MachineEvaluator::eASR</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a4d418e3defa1322e8e55b020eef30475">llvm::BitTracker::MachineEvaluator::eLSR</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a6032f746ffa25df648aa38680d1e891e">llvm::BitTracker::MachineEvaluator::eMLS</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a518631233431d2324f15075cf91ffab2">llvm::BitTracker::MachineEvaluator::eMLU</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#ac2da26c1aaa137602b14f3b3da367f61">llvm::BitTracker::MachineEvaluator::eSXT</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a1366c4865d7c8ca31dcf403406e3b291">llvm::BitTracker::MachineEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a57424565b80f4f8fef7b5a8e11735f34">llvm::BitTracker::MachineEvaluator::eZXT</a>.</p>

</div>
</div>

### insert() {#ab436b1402523817d32ee31d1d7eb7a0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell &amp; BT::RegisterCell::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; RC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitmask">BitMask</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#a56acc95a5fa4a319c87879ce52766595">width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#aceb7efc236b586c36f36b047db000db9">llvm::BitTracker::MachineEvaluator::eINS</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a1366c4865d7c8ca31dcf403406e3b291">llvm::BitTracker::MachineEvaluator::evaluate</a> and <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### meet() {#a8767a2aae4c035e715b572ce4b4c5acd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BT::RegisterCell::meet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; RC, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SelfR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a> and <a href="#ade4e536d21151ec1516845f0a6d6ac89">RegisterCell</a>.</p>

</div>
</div>

### regify() {#aa6e2cfce750a7dddf5e3bc60ad55f1b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell &amp; BT::RegisterCell::regify (unsigned R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a8e191c51f58f07f7efa53510f3bdda94a92811673861e6cd90e002880ed0ea153">llvm::BitTracker::BitValue::Ref</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a6430b3f9e35d7d7e83399a565cfd143e">llvm::BitTracker::BitValue::RefI</a> and <a href="#a56acc95a5fa4a319c87879ce52766595">width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a8944fc547212f985ad3f9706eb5b8725">llvm::BitTracker::MachineEvaluator::putCell</a>.</p>

</div>
</div>

### rol() {#ae272af7a7e6e5254fca24ec9fc2ed91c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell &amp; BT::RegisterCell::rol (uint16_t Sh)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="#ade4e536d21151ec1516845f0a6d6ac89">RegisterCell</a> and <a href="#a56acc95a5fa4a319c87879ce52766595">width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a86f3525b5df439dd04caea2c1d4f567d">llvm::BitTracker::MachineEvaluator::eASL</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a83c32395e0a0c8e1d12e4dbdc5483928">llvm::BitTracker::MachineEvaluator::eASR</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a4d418e3defa1322e8e55b020eef30475">llvm::BitTracker::MachineEvaluator::eLSR</a>.</p>

</div>
</div>

### width() {#a56acc95a5fa4a319c87879ce52766595}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::BitTracker::RegisterCell::width ()</td>
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



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>Referenced by <a href="#a1385460950e6fe590c5913ba8c9dbe90">cat</a>, <a href="#ad9770ab6f8b5455a3a84789a4ef8e94d">cl</a>, <a href="#ab3fa9c47bf9d313125b4dbe582b2eaad">ct</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#adbf082422e6f7a82cea21dfa3273811d">llvm::BitTracker::MachineEvaluator::eADD</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#ab4b48cf5ad86cd432b03b6f5b254f227">llvm::BitTracker::MachineEvaluator::eAND</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a86f3525b5df439dd04caea2c1d4f567d">llvm::BitTracker::MachineEvaluator::eASL</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a83c32395e0a0c8e1d12e4dbdc5483928">llvm::BitTracker::MachineEvaluator::eASR</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a6a2e09403daa9d3a9d40a68895e90aa9">llvm::BitTracker::MachineEvaluator::eCLB</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a13d0509a1380fb9679b433c16d4688a1">llvm::BitTracker::MachineEvaluator::eCLR</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a8fa571f010447594afbfb0dd92cdb917">llvm::BitTracker::MachineEvaluator::eCTB</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#aceb7efc236b586c36f36b047db000db9">llvm::BitTracker::MachineEvaluator::eINS</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a4d418e3defa1322e8e55b020eef30475">llvm::BitTracker::MachineEvaluator::eLSR</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a6032f746ffa25df648aa38680d1e891e">llvm::BitTracker::MachineEvaluator::eMLS</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a518631233431d2324f15075cf91ffab2">llvm::BitTracker::MachineEvaluator::eMLU</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a4aa1e4c6871a0b6056bba979f7c546bb">llvm::BitTracker::MachineEvaluator::eNOT</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#abe57eebc5c101a825f3c31712fdd617b">llvm::BitTracker::MachineEvaluator::eORL</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#aff2732336b8dfd24292c6db1fa6a64e2">llvm::BitTracker::MachineEvaluator::eSET</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#add47c55cf111a92da1ded367147668eb">llvm::BitTracker::MachineEvaluator::eSUB</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#ac2da26c1aaa137602b14f3b3da367f61">llvm::BitTracker::MachineEvaluator::eSXT</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a2c519d1784e4a4beee0fd668ed8d3900">llvm::BitTracker::MachineEvaluator::eXOR</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#aefa1e921dff52ae9ac378bf26a32b4d2">llvm::BitTracker::MachineEvaluator::eXTR</a>, <a href="#a900f393e2eebd18ebe5696a0b5d309e5">extract</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a57424565b80f4f8fef7b5a8e11735f34">llvm::BitTracker::MachineEvaluator::eZXT</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#aaee53452baac84a9ca49c3eda557ba3d">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::getConst</a>, <a href="#ab436b1402523817d32ee31d1d7eb7a0c">insert</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#a62d9e4418ce8d131f3288e8081a8f339">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::isZero</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registercellbitcomparesel/#a84cc1d6a5986314555b55ebc9d35f7a8">anonymous{HexagonGenInsert.cpp}::RegisterCellBitCompareSel::operator()</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registercelllexcompare/#a36f88ad65b49a76df81fd5aaeeda61e1">anonymous{HexagonGenInsert.cpp}::RegisterCellLexCompare::operator()</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/constgeneration/#ad75859c9c313d495322193cbaece6246">anonymous{HexagonBitSimplify.cpp}::ConstGeneration::processBlock</a>, <a href="#aa6e2cfce750a7dddf5e3bc60ad55f1b1">regify</a>, <a href="#ae272af7a7e6e5254fca24ec9fc2ed91c">rol</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/#aa073e141f102376e7e3965f39436c70f">llvm::BitTracker::subst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Bits {#aec64a10873f270edcbf62780f8306039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitValueList llvm::BitTracker::RegisterCell::Bits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### ref() {#a4e73984cdacfb5cd24df684bbe6af7a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitTracker::RegisterCell llvm::BitTracker::RegisterCell::ref (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; C)</td>
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



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a701348c13b6afb4d3ee38ec978ea0e49">llvm::BitTracker::BitValue::ref</a> and <a href="#ade4e536d21151ec1516845f0a6d6ac89">RegisterCell</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a86f3525b5df439dd04caea2c1d4f567d">llvm::BitTracker::MachineEvaluator::eASL</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a83c32395e0a0c8e1d12e4dbdc5483928">llvm::BitTracker::MachineEvaluator::eASR</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a13d0509a1380fb9679b433c16d4688a1">llvm::BitTracker::MachineEvaluator::eCLR</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#aceb7efc236b586c36f36b047db000db9">llvm::BitTracker::MachineEvaluator::eINS</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a4d418e3defa1322e8e55b020eef30475">llvm::BitTracker::MachineEvaluator::eLSR</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#aff2732336b8dfd24292c6db1fa6a64e2">llvm::BitTracker::MachineEvaluator::eSET</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#ac2da26c1aaa137602b14f3b3da367f61">llvm::BitTracker::MachineEvaluator::eSXT</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a1366c4865d7c8ca31dcf403406e3b291">llvm::BitTracker::MachineEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#aefa1e921dff52ae9ac378bf26a32b4d2">llvm::BitTracker::MachineEvaluator::eXTR</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a57424565b80f4f8fef7b5a8e11735f34">llvm::BitTracker::MachineEvaluator::eZXT</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a12f55884970b0bcf4c909891e891225b">llvm::BitTracker::MachineEvaluator::getRef</a>.</p>

</div>
</div>

### self() {#a4b372ece8559169470a7fcfb471c2302}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitTracker::RegisterCell llvm::BitTracker::RegisterCell::self (unsigned Reg, uint16_t Width)</td>
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



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="#ade4e536d21151ec1516845f0a6d6ac89">RegisterCell</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#ad20a19c881ef4af1b3a270bf06fa8d89">llvm::BitTracker::BitValue::self</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a6a2e09403daa9d3a9d40a68895e90aa9">llvm::BitTracker::MachineEvaluator::eCLB</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a8fa571f010447594afbfb0dd92cdb917">llvm::BitTracker::MachineEvaluator::eCTB</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a9a70d4969d8d43a9c9b324f692bc8ecd">llvm::BitTracker::MachineEvaluator::getCell</a>.</p>

</div>
</div>

### top() {#ab51d511c99890c779e2853504511f7d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitTracker::RegisterCell llvm::BitTracker::RegisterCell::top (uint16_t Width)</td>
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



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="#ade4e536d21151ec1516845f0a6d6ac89">RegisterCell</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a8e191c51f58f07f7efa53510f3bdda94ac09b1529fd94175201a6edddd3a27c37">llvm::BitTracker::BitValue::Top</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a9a70d4969d8d43a9c9b324f692bc8ecd">llvm::BitTracker::MachineEvaluator::getCell</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### DefaultBitN {#afe573749c131acb1c25025fbe01b0384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::BitTracker::RegisterCell::DefaultBitN = 32</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
