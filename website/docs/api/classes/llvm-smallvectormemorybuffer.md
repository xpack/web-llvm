---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/smallvectormemorybuffer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SmallVectorMemoryBuffer` Class

<p>SmallVector-backed <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> instance. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SmallVectorMemoryBuffer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smallvectormemorybuffer-h">llvm/Support/SmallVectorMemoryBuffer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This interface provides simple read-only access to a block of memory, and provides simple methods for reading files and standard input into a memory buffer. <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a080828fd48f19aa1b021094452ee6e96">SmallVectorMemoryBuffer</a> (SmallVectorImpl&lt; char &gt; &amp;&amp;SV, bool RequiresNullTerminator=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/smallvectormemorybuffer">SmallVectorMemoryBuffer</a> from the given <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> r-value. <a href="#a080828fd48f19aa1b021094452ee6e96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a446025d445ca22ed2295d2bc8f9ce590">SmallVectorMemoryBuffer</a> (SmallVectorImpl&lt; char &gt; &amp;&amp;SV, StringRef Name, bool RequiresNullTerminator=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a named <a href="/web-llvm/docs/api/classes/llvm/smallvectormemorybuffer">SmallVectorMemoryBuffer</a> from the given <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> r-value and <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>. <a href="#a446025d445ca22ed2295d2bc8f9ce590">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94853a3e4cea0f1f2d206b641fc584ac">~SmallVectorMemoryBuffer</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3111d181cc182d31f331f9bb298c1012">getBufferIdentifier</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an identifier for this buffer, typically the filename it was read from. <a href="#a3111d181cc182d31f331f9bb298c1012">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a13d3f2713d567f925cb4efecf94d2101">BufferKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8460e7a2e8cc86f3e038371961438c17">getBufferKind</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return information on the memory mechanism used to support the <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>. <a href="#a8460e7a2e8cc86f3e038371961438c17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; char, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fbbe5d00f38db90fb2f70f442ebec9a">SV</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9790bdac9d1b07bdbf96266b99a97873">BufferName</a></td>
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

<p>SmallVector-backed <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> instance.</p>


<p>This class enables efficient construction of MemoryBuffers from <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> instances. This is useful for <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> and Orc, where object files are streamed into SmallVectors, then inspected using <a href="/web-llvm/docs/api/classes/llvm/objectfile">ObjectFile</a> (which takes a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>).</p>


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smallvectormemorybuffer-h">SmallVectorMemoryBuffer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SmallVectorMemoryBuffer() {#a080828fd48f19aa1b021094452ee6e96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVectorMemoryBuffer::SmallVectorMemoryBuffer (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp;&amp; SV, bool RequiresNullTerminator=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/smallvectormemorybuffer">SmallVectorMemoryBuffer</a> from the given <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> r-value.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smallvectormemorybuffer-h">SmallVectorMemoryBuffer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a080828fd48f19aa1b021094452ee6e96">SmallVectorMemoryBuffer</a>.</p>


<p>Referenced by <a href="#a080828fd48f19aa1b021094452ee6e96">SmallVectorMemoryBuffer</a>.</p>

</div>
</div>

### SmallVectorMemoryBuffer() {#a446025d445ca22ed2295d2bc8f9ce590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVectorMemoryBuffer::SmallVectorMemoryBuffer (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp;&amp; SV, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool RequiresNullTerminator=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Construct a named <a href="/web-llvm/docs/api/classes/llvm/smallvectormemorybuffer">SmallVectorMemoryBuffer</a> from the given <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> r-value and <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smallvectormemorybuffer-h">SmallVectorMemoryBuffer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a57bdc0595208acb83e6b715bbed8e331">llvm::MemoryBuffer::init</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SmallVectorMemoryBuffer() {#a94853a3e4cea0f1f2d206b641fc584ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorMemoryBuffer::~SmallVectorMemoryBuffer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smallvectormemorybuffer-h">SmallVectorMemoryBuffer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBufferIdentifier() {#a3111d181cc182d31f331f9bb298c1012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::SmallVectorMemoryBuffer::getBufferIdentifier ()</td>
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

<p>Return an identifier for this buffer, typically the filename it was read from.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smallvectormemorybuffer-h">SmallVectorMemoryBuffer.h</a>.</p>

</div>
</div>

### getBufferKind() {#a8460e7a2e8cc86f3e038371961438c17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BufferKind llvm::SmallVectorMemoryBuffer::getBufferKind ()</td>
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

<p>Return information on the memory mechanism used to support the <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smallvectormemorybuffer-h">SmallVectorMemoryBuffer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a13d3f2713d567f925cb4efecf94d2101a04490e92687f2131e16c8d340ce01930">llvm::MemoryBuffer::MemoryBuffer_Malloc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BufferName {#a9790bdac9d1b07bdbf96266b99a97873}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::SmallVectorMemoryBuffer::BufferName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smallvectormemorybuffer-h">SmallVectorMemoryBuffer.h</a>.</p>

</div>
</div>

### SV {#a4fbbe5d00f38db90fb2f70f442ebec9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;char, 0&gt; llvm::SmallVectorMemoryBuffer::SV</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smallvectormemorybuffer-h">SmallVectorMemoryBuffer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smallvectormemorybuffer-h">SmallVectorMemoryBuffer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
