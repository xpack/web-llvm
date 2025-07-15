---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/align/logvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LogValue` Struct Reference

<p>A trivial type to allow construction of constexpr <a href="/web-llvm/docs/api/structs/llvm/align">Align</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::Align::LogValue { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a929fc0518f9db382aa2116717abf697d">Log</a></td>
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

## Description {#details}

<p>A trivial type to allow construction of constexpr <a href="/web-llvm/docs/api/structs/llvm/align">Align</a>.</p>


<p>This is currently needed to workaround a bug in GCC 5.3 which prevents definition of constexpr assign operators. <a href="https://stackoverflow.com/questions/46756288/explicitly-defaulted-function-cannot-be-declared-as-constexpr-because-the-implic">https://stackoverflow.com/questions/46756288/explicitly-defaulted-function-cannot-be-declared-as-constexpr-because-the-implic</a> FIXME: Remove this, make all assign operators constexpr and introduce user defined literals when we don't have to support GCC 5.3 anymore. <a href="https://llvm.org/docs/GettingStarted.html#getting-a-modern-host-c-toolchain">https://llvm.org/docs/GettingStarted.html#getting-a-modern-host-c-toolchain</a></p>


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Log {#a929fc0518f9db382aa2116717abf697d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::Align::LogValue::Log</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
