---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/runtimedyldchecker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RuntimeDyldChecker` Class

<p><a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> invariant checker for verifying that <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> has correctly applied relocations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RuntimeDyldChecker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyldchecker-h">llvm/ExecutionEngine/RuntimeDyldChecker.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3690573990ceae5a6f5649052411a137">IsSymbolValidFunction</a> = std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Symbol)&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acac2cbf39dcc3dc95565848db4aed7d8">GetSymbolInfoFunction</a> = std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyldchecker/memoryregioninfo">MemoryRegionInfo</a> &gt;(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SymbolName)&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ed34fdb356b0ece4cc9ee4fab9f9d45">GetSectionInfoFunction</a> = std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyldchecker/memoryregioninfo">MemoryRegionInfo</a> &gt;( <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="/web-llvm/docs/api/structs/llvm/sectionname">SectionName</a>)&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae675538cb55438dbe6a1e0de6d138319">GetStubInfoFunction</a> = std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyldchecker/memoryregioninfo">MemoryRegionInfo</a> &gt;( <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> StubContainer, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TargetName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> StubKindFilter)&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac568a27a9bc46c1935208f0ad86465c1">GetGOTInfoFunction</a> = std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyldchecker/memoryregioninfo">MemoryRegionInfo</a> &gt;( <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> GOTContainer, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TargetName)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b297e0c7523c287aebe0034aeb9925f">RuntimeDyldChecker</a> (IsSymbolValidFunction IsSymbolValid, GetSymbolInfoFunction GetSymbolInfo, GetSectionInfoFunction GetSectionInfo, GetStubInfoFunction GetStubInfo, GetGOTInfoFunction GetGOTInfo, llvm::endianness Endianness, Triple TT, StringRef CPU, SubtargetFeatures TF, raw_ostream &amp;ErrStream)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59095f9a013dc2a067cc3a445a70cfdf">~RuntimeDyldChecker</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f80a79a080da41548ad0dcd28eb36e1">check</a> (StringRef CheckExpr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> a single expression against the attached <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> instance. <a href="#a2f80a79a080da41548ad0dcd28eb36e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f3ab46a78d6f16381bb41f1cd07a6da">checkAllRulesInBuffer</a> (StringRef RulePrefix, MemoryBuffer *MemBuf) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan the given memory buffer for lines beginning with the string in RulePrefix. <a href="#a0f3ab46a78d6f16381bb41f1cd07a6da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint64_t, std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bf07d240bbd005ee53b0b6c058763de">getSectionAddr</a> (StringRef FileName, StringRef SectionName, bool LocalAddress)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the address of the requested section (or an error message in the second element of the pair if the address cannot be found). <a href="#a0bf07d240bbd005ee53b0b6c058763de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c637d434ed8085ef9e1169aca122384">getSectionLoadAddress</a> (void *LocalAddress) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If there is a section at the given local address, return its load address, otherwise return std::nullopt. <a href="#a7c637d434ed8085ef9e1169aca122384">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcheckerimpl">RuntimeDyldCheckerImpl</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec305360bf8d59d2c5f49ec0c7e63f42">Impl</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> invariant checker for verifying that <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> has correctly applied relocations.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/runtimedyldchecker">RuntimeDyldChecker</a> class evaluates expressions against an attached <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> instance to verify that relocations have been applied correctly.</p>


<p>The expression language supports basic pointer arithmetic and bit-masking, and has limited disassembler integration for accessing instruction operands and the next PC (program counter) address for each instruction.</p>


<p>The language syntax is:</p>


<p>check = expr '=' expr</p>


<p>expr = binary_expr | sliceable_expr</p>


<p>sliceable_expr = '*{' number '}' load_addr_expr [slice] | '(' expr ')' [slice] | ident_expr [slice] | number [slice]</p>


<p>slice = '[' high-bit-index ':' low-bit-index ']'</p>


<p>load_addr_expr = symbol | '(' symbol '+' number ')' | '(' symbol '-' number ')'</p>


<p>ident_expr = 'decode_operand' '(' symbol ',' operand-index ')' | 'next_pc' '(' symbol ')' | 'stub_addr' '(' stub-container-name ',' symbol ')' | 'got_addr' '(' stub-container-name ',' symbol ')' | 'section_addr' '(' stub-container-name ',' symbol ')' | symbol</p>


<p>binary_expr = expr '+' expr | expr '-' expr | expr '&amp;' expr | expr '|' expr | expr '&lt;&lt;' expr | expr '&gt;&gt;' expr</p>


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyldchecker-h">RuntimeDyldChecker.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### GetGOTInfoFunction {#ac568a27a9bc46c1935208f0ad86465c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RuntimeDyldChecker::GetGOTInfoFunction =  std::function&lt;Expected&lt;MemoryRegionInfo&gt;(
      StringRef GOTContainer, StringRef TargetName)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyldchecker-h">RuntimeDyldChecker.h</a>.</p>

</div>
</div>

### GetSectionInfoFunction {#a5ed34fdb356b0ece4cc9ee4fab9f9d45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RuntimeDyldChecker::GetSectionInfoFunction =  std::function&lt;Expected&lt;MemoryRegionInfo&gt;(
      StringRef FileName, StringRef SectionName)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyldchecker-h">RuntimeDyldChecker.h</a>.</p>

</div>
</div>

### GetStubInfoFunction {#ae675538cb55438dbe6a1e0de6d138319}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RuntimeDyldChecker::GetStubInfoFunction =  std::function&lt;Expected&lt;MemoryRegionInfo&gt;(
      StringRef StubContainer, StringRef TargetName, StringRef StubKindFilter)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyldchecker-h">RuntimeDyldChecker.h</a>.</p>

</div>
</div>

### GetSymbolInfoFunction {#acac2cbf39dcc3dc95565848db4aed7d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RuntimeDyldChecker::GetSymbolInfoFunction = 
      std::function&lt;Expected&lt;MemoryRegionInfo&gt;(StringRef SymbolName)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyldchecker-h">RuntimeDyldChecker.h</a>.</p>

</div>
</div>

### IsSymbolValidFunction {#a3690573990ceae5a6f5649052411a137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RuntimeDyldChecker::IsSymbolValidFunction =  std::function&lt;bool(StringRef Symbol)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyldchecker-h">RuntimeDyldChecker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RuntimeDyldChecker() {#a7b297e0c7523c287aebe0034aeb9925f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeDyldChecker::RuntimeDyldChecker (<a href="#a3690573990ceae5a6f5649052411a137">IsSymbolValidFunction</a> IsSymbolValid, <a href="#acac2cbf39dcc3dc95565848db4aed7d8">GetSymbolInfoFunction</a> GetSymbolInfo, <a href="#a5ed34fdb356b0ece4cc9ee4fab9f9d45">GetSectionInfoFunction</a> GetSectionInfo, <a href="#ae675538cb55438dbe6a1e0de6d138319">GetStubInfoFunction</a> GetStubInfo, <a href="#ac568a27a9bc46c1935208f0ad86465c1">GetGOTInfoFunction</a> GetGOTInfo, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> Endianness, <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures">SubtargetFeatures</a> TF, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; ErrStream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyldchecker-h">RuntimeDyldChecker.h</a>, definition at line 1034 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldchecker-cpp">RuntimeDyldChecker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RuntimeDyldChecker() {#a59095f9a013dc2a067cc3a445a70cfdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeDyldChecker::~RuntimeDyldChecker ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyldchecker-h">RuntimeDyldChecker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### check() {#a2f80a79a080da41548ad0dcd28eb36e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RuntimeDyldChecker::check (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CheckExpr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> a single expression against the attached <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> instance.</p>

<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyldchecker-h">RuntimeDyldChecker.h</a>, definition at line 1047 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldchecker-cpp">RuntimeDyldChecker.cpp</a>.</p>

</div>
</div>

### checkAllRulesInBuffer() {#a0f3ab46a78d6f16381bb41f1cd07a6da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RuntimeDyldChecker::checkAllRulesInBuffer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RulePrefix, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> * MemBuf)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan the given memory buffer for lines beginning with the string in RulePrefix.</p>


<p>The remainder of the line is passed to the check method to be evaluated as an expression.</p>


<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyldchecker-h">RuntimeDyldChecker.h</a>, definition at line 1051 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldchecker-cpp">RuntimeDyldChecker.cpp</a>.</p>

</div>
</div>

### getSectionAddr() {#a0bf07d240bbd005ee53b0b6c058763de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint64_t, std::string &gt; RuntimeDyldChecker::getSectionAddr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName, bool LocalAddress)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the address of the requested section (or an error message in the second element of the pair if the address cannot be found).</p>


<p>if 'LocalAddress' is true, this returns the address of the section within the linker's memory. If 'LocalAddress' is false it returns the address within the target process (i.e. the load address).</p>


<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyldchecker-h">RuntimeDyldChecker.h</a>, definition at line 1057 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldchecker-cpp">RuntimeDyldChecker.cpp</a>.</p>

</div>
</div>

### getSectionLoadAddress() {#a7c637d434ed8085ef9e1169aca122384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::RuntimeDyldChecker::getSectionLoadAddress (void * LocalAddress)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If there is a section at the given local address, return its load address, otherwise return std::nullopt.</p>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyldchecker-h">RuntimeDyldChecker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Impl {#aec305360bf8d59d2c5f49ec0c7e63f42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;RuntimeDyldCheckerImpl&gt; llvm::RuntimeDyldChecker::Impl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyldchecker-h">RuntimeDyldChecker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyldchecker-h">RuntimeDyldChecker.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldchecker-cpp">RuntimeDyldChecker.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
