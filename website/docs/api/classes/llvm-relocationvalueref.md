---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/relocationvalueref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RelocationValueRef` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::RelocationValueRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">ExecutionEngine/RuntimeDyld/RuntimeDyldImpl.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86595d3f1067a50a38fbd112d9b9d860">operator==</a> (const RelocationValueRef &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b5a84e06517267a6fe59728089675e3">operator&lt;</a> (const RelocationValueRef &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af46f2a8319e7835a38b0b2baaccf13c9">SectionID</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56635022517d81457f74c036897231b8">Offset</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a2be52a18ce9abea53f265b748a4504">Addend</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0830c7b6d0eb10532252bec66b6a02b9">SymbolName</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebfd492d2cce608177afc356fd1f41ff">IsStubThumb</a> = false</td>
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


<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#a0b5a84e06517267a6fe59728089675e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RelocationValueRef::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a> &amp; Other)</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>References <a href="#a0a2be52a18ce9abea53f265b748a4504">Addend</a>, <a href="#aebfd492d2cce608177afc356fd1f41ff">IsStubThumb</a>, <a href="#a56635022517d81457f74c036897231b8">Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#af46f2a8319e7835a38b0b2baaccf13c9">SectionID</a> and <a href="#a0830c7b6d0eb10532252bec66b6a02b9">SymbolName</a>.</p>

</div>
</div>

### operator==() {#a86595d3f1067a50a38fbd112d9b9d860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RelocationValueRef::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a> &amp; Other)</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>References <a href="#a0a2be52a18ce9abea53f265b748a4504">Addend</a>, <a href="#aebfd492d2cce608177afc356fd1f41ff">IsStubThumb</a>, <a href="#a56635022517d81457f74c036897231b8">Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#af46f2a8319e7835a38b0b2baaccf13c9">SectionID</a> and <a href="#a0830c7b6d0eb10532252bec66b6a02b9">SymbolName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Addend {#a0a2be52a18ce9abea53f265b748a4504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::RelocationValueRef::Addend = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a7c59308f5da9f18a578d5dfaed1285a1">llvm::RuntimeDyldCOFFAArch64::generateRelocationStub</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#ae5595d78c0d45afeec52fccb70b1b209">llvm::RuntimeDyldCOFFX86_64::generateRelocationStub</a>, <a href="#a0b5a84e06517267a6fe59728089675e3">operator&lt;</a>, <a href="#a86595d3f1067a50a38fbd112d9b9d860">operator==</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>.</p>

</div>
</div>

### IsStubThumb {#aebfd492d2cce608177afc356fd1f41ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RelocationValueRef::IsStubThumb = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#a0b5a84e06517267a6fe59728089675e3">operator&lt;</a> and <a href="#a86595d3f1067a50a38fbd112d9b9d860">operator==</a>.</p>

</div>
</div>

### Offset {#a56635022517d81457f74c036897231b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::RelocationValueRef::Offset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a7c59308f5da9f18a578d5dfaed1285a1">llvm::RuntimeDyldCOFFAArch64::generateRelocationStub</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#ae5595d78c0d45afeec52fccb70b1b209">llvm::RuntimeDyldCOFFX86_64::generateRelocationStub</a>, <a href="#a0b5a84e06517267a6fe59728089675e3">operator&lt;</a> and <a href="#a86595d3f1067a50a38fbd112d9b9d860">operator==</a>.</p>

</div>
</div>

### SectionID {#af46f2a8319e7835a38b0b2baaccf13c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RelocationValueRef::SectionID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a7c59308f5da9f18a578d5dfaed1285a1">llvm::RuntimeDyldCOFFAArch64::generateRelocationStub</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#ae5595d78c0d45afeec52fccb70b1b209">llvm::RuntimeDyldCOFFX86_64::generateRelocationStub</a>, <a href="#a0b5a84e06517267a6fe59728089675e3">operator&lt;</a>, <a href="#a86595d3f1067a50a38fbd112d9b9d860">operator==</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>.</p>

</div>
</div>

### SymbolName {#a0830c7b6d0eb10532252bec66b6a02b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::RelocationValueRef::SymbolName = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a7c59308f5da9f18a578d5dfaed1285a1">llvm::RuntimeDyldCOFFAArch64::generateRelocationStub</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#ae5595d78c0d45afeec52fccb70b1b209">llvm::RuntimeDyldCOFFX86_64::generateRelocationStub</a>, <a href="#a0b5a84e06517267a6fe59728089675e3">operator&lt;</a> and <a href="#a86595d3f1067a50a38fbd112d9b9d860">operator==</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
