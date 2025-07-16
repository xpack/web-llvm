---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/support/cbindingwrapping-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `CBindingWrapping.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">llvm-c/Types.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
</div>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65c769c08fa9fee7f298ad9c9eee5e05">DEFINE_SIMPLE_CONVERSION_FUNCTIONS</a>(ty, ref)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cd2e0ce785a05f5b2f2338453640df4">DEFINE_ISA_CONVERSION_FUNCTIONS</a>(ty, ref)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0856bab1c65467280bf8c2062de4e3d5">DEFINE_STDCXX_CONVERSION_FUNCTIONS</a>(ty, ref)&nbsp;&nbsp;&nbsp;...</td>
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

### DEFINE\_ISA\_CONVERSION\_FUNCTIONS {#a3cd2e0ce785a05f5b2f2338453640df4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEFINE_ISA_CONVERSION_FUNCTIONS(ty, ref)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#a65c769c08fa9fee7f298ad9c9eee5e05">DEFINE_SIMPLE_CONVERSION_FUNCTIONS</a>(ty, ref)           \
                                                        \
  template&lt;typename T&gt;                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a46ccdc20c42bb5ae5b9d313e12a68421">inline</a> T *<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp/#aba1a87b77adec4b08ab725bf1b4d990d">unwrap</a>(ref <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>) {                             \
    return cast&lt;T&gt;(<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp/#aba1a87b77adec4b08ab725bf1b4d990d">unwrap</a>(<a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>));                          \
  }
</div>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/cbindingwrapping-h">CBindingWrapping.h</a>.</p>

</div>
</div>

### DEFINE\_SIMPLE\_CONVERSION\_FUNCTIONS {#a65c769c08fa9fee7f298ad9c9eee5e05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEFINE_SIMPLE_CONVERSION_FUNCTIONS(ty, ref)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a46ccdc20c42bb5ae5b9d313e12a68421">inline</a> ty *<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp/#aba1a87b77adec4b08ab725bf1b4d990d">unwrap</a>(ref <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>) {                            \
    return reinterpret_cast&lt;ty*&gt;(<a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>);                    \
  }                                                     \
                                                        \
  <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a46ccdc20c42bb5ae5b9d313e12a68421">inline</a> ref <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp/#a5fe4041db3281600b33fbb1bde23f0d2">wrap</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ty *<a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>) {                        \
    return reinterpret_cast&lt;ref&gt;(const_cast&lt;ty*&gt;(<a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>));   \
  }
</div>
</dd>
</dl>

<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/cbindingwrapping-h">CBindingWrapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp/#a1f991d7177fd58c1f932dd20720a31e5">DEFINE_SIMPLE_CONVERSION_FUNCTIONS</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp/#a873362f34641cf0997c3be3f122839ef">DEFINE_SIMPLE_CONVERSION_FUNCTIONS</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp/#add1ae3cf3ab8a6bd87d0f1ddef30a2ed">DEFINE_SIMPLE_CONVERSION_FUNCTIONS</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp/#afbdbe166656b2ef8d57585b03bf7334a">DEFINE_SIMPLE_CONVERSION_FUNCTIONS</a>.</p>

</div>
</div>

### DEFINE\_STDCXX\_CONVERSION\_FUNCTIONS {#a0856bab1c65467280bf8c2062de4e3d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEFINE_STDCXX_CONVERSION_FUNCTIONS(ty, ref)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#a65c769c08fa9fee7f298ad9c9eee5e05">DEFINE_SIMPLE_CONVERSION_FUNCTIONS</a>(ty, ref)           \
                                                        \
  template&lt;typename T&gt;                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a46ccdc20c42bb5ae5b9d313e12a68421">inline</a> T *<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp/#aba1a87b77adec4b08ab725bf1b4d990d">unwrap</a>(ref <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>) {                             \
    T *Q = (T*)<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp/#aba1a87b77adec4b08ab725bf1b4d990d">unwrap</a>(<a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>);                               \
    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>(Q &amp;&amp; "Invalid cast!");                       \
    return Q;                                           \
  }
</div>
</dd>
</dl>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/cbindingwrapping-h">CBindingWrapping.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
