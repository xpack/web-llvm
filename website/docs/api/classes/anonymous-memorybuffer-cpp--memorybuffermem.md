---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-memorybuffer-cpp-/memorybuffermem
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MemoryBufferMem` Class Template

<p><a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermem">MemoryBufferMem</a> - Named <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> pointing to a block of memory. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename MB&gt;
class anonymous{MemoryBuffer.cpp}::MemoryBufferMem&lt;MB&gt; { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/mb">MB</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ad093e9036111f8dae17691a756eae14f">MemoryBufferMem</a> (StringRef InputData, bool RequiresNullTerminator)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a0b1dac8e1aa44289a5f34fe089f2bb">operator delete</a> (void *p)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable sized deallocation for <a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermem">MemoryBufferMem</a>, because it has tail-allocated data. <a href="#a7a0b1dac8e1aa44289a5f34fe089f2bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a36371e22b7197ba1646285b0d85fc987">getBufferIdentifier</a> () const override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a13d3f2713d567f925cb4efecf94d2101">MemoryBuffer::BufferKind</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad8920560ff9f2dac735c47c138727c0f">getBufferKind</a> () const override</td>
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

<p><a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermem">MemoryBufferMem</a> - Named <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> pointing to a block of memory.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MemoryBufferMem() {#ad093e9036111f8dae17691a756eae14f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MemoryBuffer.cpp}::MemoryBufferMem&lt; MB &gt;::MemoryBufferMem (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InputData, bool RequiresNullTerminator)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a> and <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a57bdc0595208acb83e6b715bbed8e331">llvm::MemoryBuffer::init</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator delete() {#a7a0b1dac8e1aa44289a5f34fe089f2bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemoryBuffer.cpp}::MemoryBufferMem&lt; MB &gt;::operator delete (void * p)</td>
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

<p>Disable sized deallocation for <a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermem">MemoryBufferMem</a>, because it has tail-allocated data.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBufferIdentifier() {#a36371e22b7197ba1646285b0d85fc987}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{MemoryBuffer.cpp}::MemoryBufferMem&lt; MB &gt;::getBufferIdentifier ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>

</div>
</div>

### getBufferKind() {#ad8920560ff9f2dac735c47c138727c0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryBuffer::BufferKind anonymous{MemoryBuffer.cpp}::MemoryBufferMem&lt; MB &gt;::getBufferKind ()</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a13d3f2713d567f925cb4efecf94d2101a04490e92687f2131e16c8d340ce01930">llvm::MemoryBuffer::MemoryBuffer_Malloc</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
