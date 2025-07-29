---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-machineverifier-cpp-/filteringvregset
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FilteringVRegSet` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{MachineVerifier.cpp}::FilteringVRegSet { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7cb2f79244da02874e36f4a74ab3ab5">const_iterator</a> = decltype(VRegs)<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">::const_iterator</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename RegSetT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16c3feb6db6da66b21ef930c5c0b8be8">addToFilter</a> (const RegSetT &amp;RS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename RegSetT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab6fe7bf6104a726f38b2e4e8ddd56f94">add</a> (const RegSetT &amp;RS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af7cb2f79244da02874e36f4a74ab3ab5">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d09760d8a3d3fddeb70626ecf13981a">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af7cb2f79244da02874e36f4a74ab3ab5">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a677ad556efd74ab5cf5fbc31561db63b">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73059040c7a782968f6211ce82bbc778">size</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/vregfilter">VRegFilter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd99d54dfcc442ef65cc6eaba15a50e6">Filter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c020fc459afead0ca284f704cceaebf">VRegs</a></td>
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


<p>Definition at line 3230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#af7cb2f79244da02874e36f4a74ab3ab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{MachineVerifier.cpp}::FilteringVRegSet::const_iterator =  decltype(VRegs)::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3247 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#ab6fe7bf6104a726f38b2e4e8ddd56f94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RegSetT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineVerifier.cpp}::FilteringVRegSet::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RegSetT &amp; RS)</td>
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



<p>Definition at line 3242 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a990694380bae24a3a5b09b9a12f2e333">anonymous{MachineVerifier.cpp}::MachineVerifier::calcRegsPassed</a>.</p>

</div>
</div>

### addToFilter() {#a16c3feb6db6da66b21ef930c5c0b8be8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RegSetT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MachineVerifier.cpp}::FilteringVRegSet::addToFilter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RegSetT &amp; RS)</td>
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



<p>Definition at line 3237 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a990694380bae24a3a5b09b9a12f2e333">anonymous{MachineVerifier.cpp}::MachineVerifier::calcRegsPassed</a>.</p>

</div>
</div>

### begin() {#a4d09760d8a3d3fddeb70626ecf13981a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator anonymous{MachineVerifier.cpp}::FilteringVRegSet::begin ()</td>
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



<p>Definition at line 3248 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a990694380bae24a3a5b09b9a12f2e333">anonymous{MachineVerifier.cpp}::MachineVerifier::calcRegsPassed</a>.</p>

</div>
</div>

### end() {#a677ad556efd74ab5cf5fbc31561db63b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator anonymous{MachineVerifier.cpp}::FilteringVRegSet::end ()</td>
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



<p>Definition at line 3249 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a990694380bae24a3a5b09b9a12f2e333">anonymous{MachineVerifier.cpp}::MachineVerifier::calcRegsPassed</a>.</p>

</div>
</div>

### size() {#a73059040c7a782968f6211ce82bbc778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{MachineVerifier.cpp}::FilteringVRegSet::size ()</td>
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



<p>Definition at line 3250 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a990694380bae24a3a5b09b9a12f2e333">anonymous{MachineVerifier.cpp}::MachineVerifier::calcRegsPassed</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Filter {#acd99d54dfcc442ef65cc6eaba15a50e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VRegFilter anonymous{MachineVerifier.cpp}::FilteringVRegSet::Filter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3231 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>

</div>
</div>

### VRegs {#a3c020fc459afead0ca284f704cceaebf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Register, 0&gt; anonymous{MachineVerifier.cpp}::FilteringVRegSet::VRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3232 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
