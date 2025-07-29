---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `LVSupport.h` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">llvm/ADT/SmallBitVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">llvm/DebugInfo/LogicalView/Core/LVStringPool.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cctype&gt;
#include &lt;map&gt;
#include &lt;sstream&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview">logicalview</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvproperties">LVProperties&lt;T&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdoublemap">LVDoubleMap&lt;FirstKeyType, SecondKeyType, ValueType&gt;</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca35368ffeb8c0d88ba060a3086574c0">BOOL_BIT</a>(FAMILY, ENUM, FIELD)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1290ab565fd9e742f769da8c86e3ceaa">BOOL_BIT_1</a>(FAMILY, ENUM, FIELD, F1)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16c6594a0c1da8a9c73654445f864ad4">BOOL_BIT_2</a>(FAMILY, ENUM, FIELD, F1, F2)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf11146dd3ae61a137e3908d402ffe29">BOOL_BIT_3</a>(FAMILY, ENUM, FIELD, F1, F2, F3)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3117bc185aabb586105cf16196851932">PROPERTY</a>(ENUM, FIELD)&nbsp;&nbsp;&nbsp;<a href="#aca35368ffeb8c0d88ba060a3086574c0">BOOL_BIT</a>(Properties, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60fbb6453990ed25de0cfc4acf33b423">PROPERTY_1</a>(ENUM, FIELD, F1)&nbsp;&nbsp;&nbsp;<a href="#a1290ab565fd9e742f769da8c86e3ceaa">BOOL_BIT_1</a>(Properties, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>, F1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8af3bedbbdb5549839ddcdd05c7ffcf">PROPERTY_2</a>(ENUM, FIELD, F1, F2)&nbsp;&nbsp;&nbsp;  <a href="#a16c6594a0c1da8a9c73654445f864ad4">BOOL_BIT_2</a>(Properties, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>, F1, F2)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9038efeee492b6a81061c09affa16277">PROPERTY_3</a>(ENUM, FIELD, F1, F2, F3)&nbsp;&nbsp;&nbsp;  <a href="#abf11146dd3ae61a137e3908d402ffe29">BOOL_BIT_3</a>(Properties, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>, F1, F2, F3)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fe94e4721fb2c4dfc05937e4c71aa2c">KIND</a>(ENUM, FIELD)&nbsp;&nbsp;&nbsp;<a href="#aca35368ffeb8c0d88ba060a3086574c0">BOOL_BIT</a>(Kinds, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b0a67b92c20a22b09b972a062c33eb1">KIND_1</a>(ENUM, FIELD, F1)&nbsp;&nbsp;&nbsp;<a href="#a1290ab565fd9e742f769da8c86e3ceaa">BOOL_BIT_1</a>(Kinds, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>, F1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a976a2ad068927192d6b441fc74b6cc">KIND_2</a>(ENUM, FIELD, F1, F2)&nbsp;&nbsp;&nbsp;<a href="#a16c6594a0c1da8a9c73654445f864ad4">BOOL_BIT_2</a>(Kinds, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>, F1, F2)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7540897f2d5ff2ddc535701e3ed7fdda">KIND_3</a>(ENUM, FIELD, F1, F2, F3)&nbsp;&nbsp;&nbsp;  <a href="#abf11146dd3ae61a137e3908d402ffe29">BOOL_BIT_3</a>(Kinds, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>, F1, F2, F3)</td>
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


<div class="doxySectionDef">

## Macro Definitions

### BOOL\_BIT {#aca35368ffeb8c0d88ba060a3086574c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define BOOL_BIT(FAMILY, ENUM, FIELD)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  bool get##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>() <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> { return FAMILY.get(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">ENUM::FIELD</a>); }                  \
  void set##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>() { FAMILY.set(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">ENUM::FIELD</a>); }                               \
  void reset##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>() { FAMILY.reset(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">ENUM::FIELD</a>); }
</div>
</dd>
</dl>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h">LVSupport.h</a>.</p>

</div>
</div>

### BOOL\_BIT\_1 {#a1290ab565fd9e742f769da8c86e3ceaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define BOOL_BIT_1(FAMILY, ENUM, FIELD, F1)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  bool get##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>() <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> { return FAMILY.get(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">ENUM::FIELD</a>); }                  \
  void set##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>() {                                                          \
    FAMILY.set(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">ENUM::FIELD</a>);                                                   \
    set##F1();                                                                 \
  }                                                                            \
  void reset##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>() { FAMILY.reset(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">ENUM::FIELD</a>); }
</div>
</dd>
</dl>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h">LVSupport.h</a>.</p>

</div>
</div>

### BOOL\_BIT\_2 {#a16c6594a0c1da8a9c73654445f864ad4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define BOOL_BIT_2(FAMILY, ENUM, FIELD, F1, F2)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  bool get##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>() <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> { return FAMILY.get(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">ENUM::FIELD</a>); }                  \
  void set##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>() {                                                          \
    FAMILY.set(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">ENUM::FIELD</a>);                                                   \
    set##F1();                                                                 \
    set##F2();                                                                 \
  }                                                                            \
  void reset##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>() { FAMILY.reset(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">ENUM::FIELD</a>); }
</div>
</dd>
</dl>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h">LVSupport.h</a>.</p>

</div>
</div>

### BOOL\_BIT\_3 {#abf11146dd3ae61a137e3908d402ffe29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define BOOL_BIT_3(FAMILY, ENUM, FIELD, F1, F2, F3)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  bool get##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>() <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> { return FAMILY.get(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">ENUM::FIELD</a>); }                  \
  void set##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>() {                                                          \
    FAMILY.set(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">ENUM::FIELD</a>);                                                   \
    set##F1();                                                                 \
    set##F2();                                                                 \
    set##F3();                                                                 \
  }                                                                            \
  void reset##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>() { FAMILY.reset(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">ENUM::FIELD</a>); }
</div>
</dd>
</dl>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h">LVSupport.h</a>.</p>

</div>
</div>

### KIND {#a0fe94e4721fb2c4dfc05937e4c71aa2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define KIND(ENUM, FIELD)&nbsp;&nbsp;&nbsp;<a href="#aca35368ffeb8c0d88ba060a3086574c0">BOOL_BIT</a>(Kinds, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h">LVSupport.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#ad0ea28d901a2351fedec9ef3deec2663">GetCodeName</a>.</p>

</div>
</div>

### KIND\_1 {#a7b0a67b92c20a22b09b972a062c33eb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define KIND_1(ENUM, FIELD, F1)&nbsp;&nbsp;&nbsp;<a href="#a1290ab565fd9e742f769da8c86e3ceaa">BOOL_BIT_1</a>(Kinds, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>, F1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h">LVSupport.h</a>.</p>

</div>
</div>

### KIND\_2 {#a2a976a2ad068927192d6b441fc74b6cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define KIND_2(ENUM, FIELD, F1, F2)&nbsp;&nbsp;&nbsp;<a href="#a16c6594a0c1da8a9c73654445f864ad4">BOOL_BIT_2</a>(Kinds, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>, F1, F2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h">LVSupport.h</a>.</p>

</div>
</div>

### KIND\_3 {#a7540897f2d5ff2ddc535701e3ed7fdda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define KIND_3(ENUM, FIELD, F1, F2, F3)&nbsp;&nbsp;&nbsp;  <a href="#abf11146dd3ae61a137e3908d402ffe29">BOOL_BIT_3</a>(Kinds, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>, F1, F2, F3)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h">LVSupport.h</a>.</p>

</div>
</div>

### PROPERTY {#a3117bc185aabb586105cf16196851932}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PROPERTY(ENUM, FIELD)&nbsp;&nbsp;&nbsp;<a href="#aca35368ffeb8c0d88ba060a3086574c0">BOOL_BIT</a>(Properties, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h">LVSupport.h</a>.</p>

</div>
</div>

### PROPERTY\_1 {#a60fbb6453990ed25de0cfc4acf33b423}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PROPERTY_1(ENUM, FIELD, F1)&nbsp;&nbsp;&nbsp;<a href="#a1290ab565fd9e742f769da8c86e3ceaa">BOOL_BIT_1</a>(Properties, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>, F1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h">LVSupport.h</a>.</p>

</div>
</div>

### PROPERTY\_2 {#ae8af3bedbbdb5549839ddcdd05c7ffcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PROPERTY_2(ENUM, FIELD, F1, F2)&nbsp;&nbsp;&nbsp;  <a href="#a16c6594a0c1da8a9c73654445f864ad4">BOOL_BIT_2</a>(Properties, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>, F1, F2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h">LVSupport.h</a>.</p>

</div>
</div>

### PROPERTY\_3 {#a9038efeee492b6a81061c09affa16277}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PROPERTY_3(ENUM, FIELD, F1, F2, F3)&nbsp;&nbsp;&nbsp;  <a href="#abf11146dd3ae61a137e3908d402ffe29">BOOL_BIT_3</a>(Properties, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetinfo-h/#a0b071325da18642641def02588eb7a2d">FIELD</a>, F1, F2, F3)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h">LVSupport.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
