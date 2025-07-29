---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/mc/mccontext-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `MCContext.h` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmap-h">llvm/ADT/StringMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">llvm/BinaryFormat/XCOFF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">llvm/MC/MCAsmMacro.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">llvm/MC/MCDwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">llvm/MC/MCPseudoProbe.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">llvm/MC/MCSection.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymboltableentry-h">llvm/MC/MCSymbolTableEntry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">llvm/MC/SectionKind.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">llvm/Support/Allocator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">llvm/Support/MD5.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/stringsaver-h">llvm/Support/StringSaver.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;functional&gt;
#include &lt;map&gt;
#include &lt;memory&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/wasm">wasm</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Context object for machine code objects. <a href="/web-llvm/docs/api/classes/llvm/mccontext/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mccontext/coffsectionkey">COFFSectionKey</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mccontext/wasmsectionkey">WasmSectionKey</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mccontext/xcoffsectionkey">XCOFFSectionKey</a></td>
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

## Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8739ede42a4f9778b67d666086b9d96">operator new</a> (size_t Bytes, llvm::MCContext &amp;C, size_t Alignment=8) noexcept</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Placement new for using the MCContext's allocator. <a href="#ae8739ede42a4f9778b67d666086b9d96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7df3c98b36215141b42b0a6ec782ddfa">operator delete</a> (void *Ptr, llvm::MCContext &amp;C, size_t) noexcept</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Placement delete companion to the new above. <a href="#a7df3c98b36215141b42b0a6ec782ddfa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8002ed4c7e4b8a9a1177ec9fbd7826b3">operator new[]</a> (size_t Bytes, llvm::MCContext &amp;C, size_t Alignment=8) noexcept</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This placement form of operator new[] uses the MCContext's allocator for obtaining memory. <a href="#a8002ed4c7e4b8a9a1177ec9fbd7826b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1c29b9bc4e1c8d6db326cfd2a80c7b2">operator delete[]</a> (void *Ptr, llvm::MCContext &amp;C) noexcept</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Placement delete[] companion to the new[] above. <a href="#ad1c29b9bc4e1c8d6db326cfd2a80c7b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Operators

### operator delete() {#a7df3c98b36215141b42b0a6ec782ddfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void operator delete (void * Ptr, <a href="/web-llvm/docs/api/classes/llvm/mccontext">llvm::MCContext</a> &amp; C, size_t)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Placement delete companion to the new above.</p>


<p>This operator is just a companion to the new above. There is no way of invoking it directly; see the new operator for more details. This operator is called implicitly by the compiler if a placement new expression using the MCContext throws in the object constructor.</p>


<p>Definition at line 883 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a1960c14773241d6a238d2db593abe552">C</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### operator delete\[\]() {#ad1c29b9bc4e1c8d6db326cfd2a80c7b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void operator delete[] (void * Ptr, <a href="/web-llvm/docs/api/classes/llvm/mccontext">llvm::MCContext</a> &amp; C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Placement delete[] companion to the new[] above.</p>


<p>This operator is just a companion to the new[] above. There is no way of invoking it directly; see the new[] operator for more details. This operator is called implicitly by the compiler if a placement new[] expression using the MCContext throws in the object constructor.</p>


<p>Definition at line 917 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a1960c14773241d6a238d2db593abe552">C</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### operator new() {#ae8739ede42a4f9778b67d666086b9d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * operator new (size_t Bytes, <a href="/web-llvm/docs/api/classes/llvm/mccontext">llvm::MCContext</a> &amp; C, size_t Alignment=8)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Placement new for using the MCContext's allocator.</p>


<p>This placement form of operator new uses the MCContext's allocator for obtaining memory. It is a non-throwing new, which means that it returns null on error. (If that is what the allocator does. The current does, so if this ever changes, this operator will have to be changed, too.) Usage looks like this (assuming there's an MCContext 'Context' in scope):</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">// Default alignment (8)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">IntegerLiteral *Ex = new (Context) IntegerLiteral(arguments);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">// Specific alignment</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">IntegerLiteral *Ex2 = new (Context, 4) IntegerLiteral(arguments);</span></span></div>

</div>


<p>Please note that you cannot use delete on the pointer; it must be deallocated using an explicit destructor call followed by <span class="doxyComputerOutput">Context.Deallocate(Ptr)</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Bytes</td>
<td class="doxyParamItemDescription"><p>The number of bytes to allocate. Calculated by the compiler.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">C</td>
<td class="doxyParamItemDescription"><p>The MCContext that provides the allocator.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Alignment</td>
<td class="doxyParamItemDescription"><p>The alignment of the allocated memory (if the underlying allocator supports it).</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The allocated memory. Could be NULL.</p></dd>
</dl>


<p>Definition at line 873 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a1960c14773241d6a238d2db593abe552">C</a>.</p>

</div>
</div>

### operator new\[\]() {#a8002ed4c7e4b8a9a1177ec9fbd7826b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * operator new[] (size_t Bytes, <a href="/web-llvm/docs/api/classes/llvm/mccontext">llvm::MCContext</a> &amp; C, size_t Alignment=8)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This placement form of operator new[] uses the MCContext's allocator for obtaining memory.</p>


<p>It is a non-throwing new[], which means that it returns null on error. Usage looks like this (assuming there's an MCContext 'Context' in scope):</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">// Default alignment (8)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">char *data = new (Context) char[10];</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">// Specific alignment</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">char *data = new (Context, 4) char[10];</span></span></div>

</div>


<p>Please note that you cannot use delete on the pointer; it must be deallocated using an explicit destructor call followed by <span class="doxyComputerOutput">Context.Deallocate(Ptr)</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Bytes</td>
<td class="doxyParamItemDescription"><p>The number of bytes to allocate. Calculated by the compiler.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">C</td>
<td class="doxyParamItemDescription"><p>The MCContext that provides the allocator.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Alignment</td>
<td class="doxyParamItemDescription"><p>The alignment of the allocated memory (if the underlying allocator supports it).</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The allocated memory. Could be NULL.</p></dd>
</dl>


<p>Definition at line 906 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a1960c14773241d6a238d2db593abe552">C</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
