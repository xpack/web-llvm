---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/log-reader/tensorvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TensorValue` Class



## Declaration

<div class="doxyDeclaration">
class log_reader::TensorValue { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcc496977a6e3b6bc2d770a642900be1">__init__</a> (self, TensorSpec spec, bytes buffer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/log-reader/tensorspec">TensorSpec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3b6b311e0b847ba5f47e820de4834d4">spec</a> (self)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f335ccb49b7b41f58ea2d33b7e46814">__len__</a> (self)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a303866c5fd53e252f10c70499c55d3e6">__getitem__</a> (self, index)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/log-reader/tensorspec">TensorSpec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad75472a62a7fc52cdfd94edb3f07db7b">_spec</a> =  <a href="#ab3b6b311e0b847ba5f47e820de4834d4">spec</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08963649af5fd9c164ec1a4e2567873c">_buffer</a> =  buffer</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fc99d7b132a72919f095e32f437a5c7">_view</a> =  ctypes.cast(self._buffer, ctypes.POINTER(self._spec.element_type))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07f7c204d41022aeb99d9268aa303c0e">_len</a> =  math.prod(self._spec.shape)</td>
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


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/log-reader-py">log_reader.py</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### \_\_getitem\_\_() {#a303866c5fd53e252f10c70499c55d3e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">log_reader.TensorValue.__getitem__ (self self, index index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/log-reader-py">log_reader.py</a>.</p>


<p>References <a href="#a07f7c204d41022aeb99d9268aa303c0e">log_reader.TensorValue._len</a> and <a href="#a0fc99d7b132a72919f095e32f437a5c7">log_reader.TensorValue._view</a>.</p>

</div>
</div>

### \_\_init\_\_() {#afcc496977a6e3b6bc2d770a642900be1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">log_reader.TensorValue.__init__ (self self, <a href="/web-llvm/docs/api/classes/log-reader/tensorspec">TensorSpec</a> spec, bytes buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/log-reader-py">log_reader.py</a>.</p>

</div>
</div>

### \_\_len\_\_() {#a8f335ccb49b7b41f58ea2d33b7e46814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName"> int log_reader.TensorValue.__len__ (self self)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/log-reader-py">log_reader.py</a>.</p>


<p>Reference <a href="#a07f7c204d41022aeb99d9268aa303c0e">log_reader.TensorValue._len</a>.</p>

</div>
</div>

### spec() {#ab3b6b311e0b847ba5f47e820de4834d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName"> TensorSpec log_reader.TensorValue.spec (self self)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/log-reader-py">log_reader.py</a>.</p>


<p>Reference <a href="#ad75472a62a7fc52cdfd94edb3f07db7b">log_reader.TensorValue._spec</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### \_buffer {#a08963649af5fd9c164ec1a4e2567873c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">log_reader.TensorValue::_buffer =  buffer</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/log-reader-py">log_reader.py</a>.</p>

</div>
</div>

### \_len {#a07f7c204d41022aeb99d9268aa303c0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">log_reader.TensorValue::_len =  math.prod(self._spec.shape)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/log-reader-py">log_reader.py</a>.</p>


<p>Referenced by <a href="#a303866c5fd53e252f10c70499c55d3e6">log_reader.TensorValue.__getitem__</a> and <a href="#a8f335ccb49b7b41f58ea2d33b7e46814">log_reader.TensorValue.__len__</a>.</p>

</div>
</div>

### \_spec {#ad75472a62a7fc52cdfd94edb3f07db7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TensorSpec log_reader.TensorValue::_spec =  <a href="#ab3b6b311e0b847ba5f47e820de4834d4">spec</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/log-reader-py">log_reader.py</a>.</p>


<p>Referenced by <a href="#ab3b6b311e0b847ba5f47e820de4834d4">log_reader.TensorValue.spec</a>.</p>

</div>
</div>

### \_view {#a0fc99d7b132a72919f095e32f437a5c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">log_reader.TensorValue::_view =  ctypes.cast(self._buffer, ctypes.POINTER(self._spec.element_type))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/log-reader-py">log_reader.py</a>.</p>


<p>Referenced by <a href="#a303866c5fd53e252f10c70499c55d3e6">log_reader.TensorValue.__getitem__</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/log-reader-py">log_reader.py</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
