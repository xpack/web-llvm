---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-vfabidemangler-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{VFABIDemangler.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{VFABIDemangler.cpp} { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ParseRet { <a href="#a610bcac0ac7e242f391a34b91889dfa5">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utilities for the Vector <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> ABI name parser. <a href="#a610bcac0ac7e242f391a34b91889dfa5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a610bcac0ac7e242f391a34b91889dfa5">ParseRet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e256b3e261a7e37851be3f91173e6c0">tryParseISA</a> (StringRef &amp;MangledName, VFISAKind &amp;ISA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extracts the <span class="doxyComputerOutput">&lt;isa&gt;</span> information from the mangled string, and sets the <span class="doxyComputerOutput">ISA</span> accordingly. <a href="#a1e256b3e261a7e37851be3f91173e6c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a610bcac0ac7e242f391a34b91889dfa5">ParseRet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3af3ce355fb0d93f751694070efc4c1d">tryParseMask</a> (StringRef &amp;MangledName, bool &amp;IsMasked)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extracts the <span class="doxyComputerOutput">&lt;mask&gt;</span> information from the mangled string, and sets <span class="doxyComputerOutput">IsMasked</span> accordingly. <a href="#a3af3ce355fb0d93f751694070efc4c1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a610bcac0ac7e242f391a34b91889dfa5">ParseRet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14373b1995a870811ec0b24e8c7bb274">tryParseVLEN</a> (StringRef &amp;ParseString, VFISAKind ISA, std::pair&lt; unsigned, bool &gt; &amp;ParsedVF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the <span class="doxyComputerOutput">&lt;vlen&gt;</span> information from the mangled string, and sets <span class="doxyComputerOutput">ParsedVF</span> accordingly. <a href="#a14373b1995a870811ec0b24e8c7bb274">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a610bcac0ac7e242f391a34b91889dfa5">ParseRet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c267f75d0c944ac84dff96f8a4779f3">tryParseLinearTokenWithRuntimeStep</a> (StringRef &amp;ParseString, VFParamKind &amp;PKind, int &amp;Pos, const StringRef Token)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The function looks for the following strings at the beginning of the input string <span class="doxyComputerOutput">ParseString</span>: <a href="#a4c267f75d0c944ac84dff96f8a4779f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a610bcac0ac7e242f391a34b91889dfa5">ParseRet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57b4cf2441156c6d912e37e94a7c7a44">tryParseLinearWithRuntimeStep</a> (StringRef &amp;ParseString, VFParamKind &amp;PKind, int &amp;StepOrPos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The function looks for the following string at the beginning of the input string <span class="doxyComputerOutput">ParseString</span>: <a href="#a57b4cf2441156c6d912e37e94a7c7a44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a610bcac0ac7e242f391a34b91889dfa5">ParseRet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a856e22af4413a5ea9df66d623f35b824">tryParseCompileTimeLinearToken</a> (StringRef &amp;ParseString, VFParamKind &amp;PKind, int &amp;LinearStep, const StringRef Token)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The function looks for the following strings at the beginning of the input string <span class="doxyComputerOutput">ParseString</span>: <a href="#a856e22af4413a5ea9df66d623f35b824">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a610bcac0ac7e242f391a34b91889dfa5">ParseRet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5483a1f81120ebaec6d91e466a25c292">tryParseLinearWithCompileTimeStep</a> (StringRef &amp;ParseString, VFParamKind &amp;PKind, int &amp;StepOrPos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The function looks for the following strings at the beginning of the input string <span class="doxyComputerOutput">ParseString</span>: <a href="#a5483a1f81120ebaec6d91e466a25c292">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a610bcac0ac7e242f391a34b91889dfa5">ParseRet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71eadd5ab74bdb057ebcc6b916924f78">tryParseParameter</a> (StringRef &amp;ParseString, VFParamKind &amp;PKind, int &amp;StepOrPos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks into the &lt;parameters&gt; part of the mangled name in search for valid paramaters at the beginning of the string <span class="doxyComputerOutput">ParseString</span>. <a href="#a71eadd5ab74bdb057ebcc6b916924f78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a610bcac0ac7e242f391a34b91889dfa5">ParseRet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1381cfa5d5d20b2c0de03ce8f211c1cf">tryParseAlign</a> (StringRef &amp;ParseString, Align &amp;Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks into the &lt;parameters&gt; part of the mangled name in search of a valid 'aligned' clause. <a href="#a1381cfa5d5d20b2c0de03ce8f211c1cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d97ecc1d468027ddd95cb7399aaceb0">getElementCountForTy</a> (const VFISAKind ISA, const Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a09a1144b3dbb1ddc00f0ced5030522">getScalableECFromSignature</a> (const FunctionType *Signature, const VFISAKind ISA, const SmallVectorImpl&lt; VFParameter &gt; &amp;Params)</td>
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

## Enumerations

### ParseRet {#a610bcac0ac7e242f391a34b91889dfa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{VFABIDemangler.cpp}::ParseRet </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Utilities for the Vector <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> ABI name parser.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OK<a id="a610bcac0ac7e242f391a34b91889dfa5ae0aa021e21dddbd6d8cecec71e9cf564"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">None<a id="a610bcac0ac7e242f391a34b91889dfa5a6adf97f83acf6453d4a6a4b1070f3754"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Error<a id="a610bcac0ac7e242f391a34b91889dfa5a902b0d55fddef6f8d651fe1035b7d4bd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>Return types for the parser functions.</p>


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getElementCountForTy() {#a2d97ecc1d468027ddd95cb7399aaceb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ElementCount &gt; anonymous{VFABIDemangler.cpp}::getElementCountForTy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169c">VFISAKind</a> ISA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a1bddc4949ab247dd1474f79b9bc6e34e">llvm::ElementCount::getScalable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169ca2ce62e1cd502db9d1a7a8295164f6584">llvm::RVV</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169ca8a880ec3350518f78cffab1bd18e97ba">llvm::SVE</a>.</p>


<p>Referenced by <a href="#a0a09a1144b3dbb1ddc00f0ced5030522">getScalableECFromSignature</a>.</p>

</div>
</div>

### getScalableECFromSignature() {#a0a09a1144b3dbb1ddc00f0ced5030522}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ElementCount &gt; anonymous{VFABIDemangler.cpp}::getScalableECFromSignature (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * Signature, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169c">VFISAKind</a> ISA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vfparameter">VFParameter</a> &gt; &amp; Params)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad481eeaefb613122480457f521fa42a8">llvm::getContainedTypes</a>, <a href="#a2d97ecc1d468027ddd95cb7399aaceb0">getElementCountForTy</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a1e415dc42f391c1d0cfcc1c28c00b2f4">llvm::FunctionType::getParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#ad65790aa94dd4678a1d339d8304e1965">llvm::FunctionType::getReturnType</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a1bddc4949ab247dd1474f79b9bc6e34e">llvm::ElementCount::getScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a83e6442f8ebefccdb5e089732fe397ac">llvm::details::FixedOrScalableQuantity&lt; ElementCount, unsigned &gt;::isKnownLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a28db78be8569f9cabe49007baf76cff2">llvm::isUnpackedStructLiteral</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae8eaa0b4eeac52a2b2282cb1bfd981ae">llvm::Type::isVoidTy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">llvm::Vector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a46c9ccb087f925d00317f16577410a13">llvm::VFABI::tryDemangleForVFABI</a>.</p>

</div>
</div>

### tryParseAlign() {#a1381cfa5d5d20b2c0de03ce8f211c1cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseRet anonymous{VFABIDemangler.cpp}::tryParseAlign (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; ParseString, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp; Alignment)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Looks into the &lt;parameters&gt; part of the mangled name in search of a valid 'aligned' clause.</p>


<p>The function should be invoked after parsing a parameter via <span class="doxyComputerOutput">tryParseParameter</span>.</p>


<p>On success, it removes the parsed parameter from <span class="doxyComputerOutput">ParseString</span>, sets <span class="doxyComputerOutput">PKind</span> to the correspondent enum value, sets <span class="doxyComputerOutput">StepOrPos</span> accordingly, and return success. On a syntax error, it return a parsing error. If nothing is parsed, it returns std::nullopt.</p>


<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1643e7698ddbfd40fbd374a85f015846">llvm::StringRef::consumeInteger</a>, <a href="#a610bcac0ac7e242f391a34b91889dfa5a902b0d55fddef6f8d651fe1035b7d4bd">Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a>, <a href="#a610bcac0ac7e242f391a34b91889dfa5a6adf97f83acf6453d4a6a4b1070f3754">None</a> and <a href="#a610bcac0ac7e242f391a34b91889dfa5ae0aa021e21dddbd6d8cecec71e9cf564">OK</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a46c9ccb087f925d00317f16577410a13">llvm::VFABI::tryDemangleForVFABI</a>.</p>

</div>
</div>

### tryParseCompileTimeLinearToken() {#a856e22af4413a5ea9df66d623f35b824}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseRet anonymous{VFABIDemangler.cpp}::tryParseCompileTimeLinearToken (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; ParseString, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39">VFParamKind</a> &amp; PKind, int &amp; LinearStep, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Token)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The function looks for the following strings at the beginning of the input string <span class="doxyComputerOutput">ParseString</span>:</p>


<p>&lt;token&gt; {"n"} &lt;number&gt;</p>


<p>On success, it removes the parsed parameter from <span class="doxyComputerOutput">ParseString</span>, sets <span class="doxyComputerOutput">PKind</span> to the correspondent enum value, sets <span class="doxyComputerOutput">LinearStep</span> to &lt;number&gt;, and return success. On a syntax error, it return a parsing error. If nothing is parsed, it returns std::nullopt.</p>


<p>The function expects &lt;token&gt; to be one of "l", "R", "U" or "L".</p>


<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1643e7698ddbfd40fbd374a85f015846">llvm::StringRef::consumeInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#aaf19acac548dca3c8f263ceb6a860b57">llvm::VFABI::getVFParamKindFromString</a>, <a href="#a610bcac0ac7e242f391a34b91889dfa5a6adf97f83acf6453d4a6a4b1070f3754">None</a> and <a href="#a610bcac0ac7e242f391a34b91889dfa5ae0aa021e21dddbd6d8cecec71e9cf564">OK</a>.</p>


<p>Referenced by <a href="#a5483a1f81120ebaec6d91e466a25c292">tryParseLinearWithCompileTimeStep</a>.</p>

</div>
</div>

### tryParseISA() {#a1e256b3e261a7e37851be3f91173e6c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseRet anonymous{VFABIDemangler.cpp}::tryParseISA (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; MangledName, <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169c">VFISAKind</a> &amp; ISA)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extracts the <span class="doxyComputerOutput">&lt;isa&gt;</span> information from the mangled string, and sets the <span class="doxyComputerOutput">ISA</span> accordingly.</p>


<p>If successful, the &lt;isa&gt; token is removed from the input string <span class="doxyComputerOutput">MangledName</span>.</p>


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#af33ac7943ba16e891cd1b6e307029301">llvm::VFABI::_LLVM_</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169ca999042bd3d6c9b2d8946fb6fcb7bf183">llvm::AdvancedSIMD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169ca4863502abea45861b9ed022e66d66cb2">llvm::AVX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169caee6ecd3e091cdefd02e783f9b9869388">llvm::AVX2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169ca5f8acb5068c8c8db7b2a4069bd17d9fd">llvm::AVX512</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="#a610bcac0ac7e242f391a34b91889dfa5a902b0d55fddef6f8d651fe1035b7d4bd">Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169ca66a0128ad08b2053e4809e07fe05728c">llvm::LLVM</a>, <a href="#a610bcac0ac7e242f391a34b91889dfa5ae0aa021e21dddbd6d8cecec71e9cf564">OK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169ca2ce62e1cd502db9d1a7a8295164f6584">llvm::RVV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169ca5fc53fc8197865c63285f74b1e147013">llvm::SSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169ca8a880ec3350518f78cffab1bd18e97ba">llvm::SVE</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aa28286a33491b5d9a936fb6ae853baee">llvm::StringRef::take_front</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169ca88183b946cc5f0e8c96b2e66e1c74a7e">llvm::Unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a46c9ccb087f925d00317f16577410a13">llvm::VFABI::tryDemangleForVFABI</a>.</p>

</div>
</div>

### tryParseLinearTokenWithRuntimeStep() {#a4c267f75d0c944ac84dff96f8a4779f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseRet anonymous{VFABIDemangler.cpp}::tryParseLinearTokenWithRuntimeStep (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; ParseString, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39">VFParamKind</a> &amp; PKind, int &amp; Pos, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Token)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The function looks for the following strings at the beginning of the input string <span class="doxyComputerOutput">ParseString</span>:</p>


<p>&lt;token&gt; &lt;number&gt;</p>


<p>On success, it removes the parsed parameter from <span class="doxyComputerOutput">ParseString</span>, sets <span class="doxyComputerOutput">PKind</span> to the correspondent enum value, sets <span class="doxyComputerOutput">Pos</span> to &lt;number&gt;, and return success. On a syntax error, it return a parsing error. If nothing is parsed, it returns std::nullopt.</p>


<p>The function expects &lt;token&gt; to be one of "ls", "Rs", "Us" or "Ls".</p>


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1643e7698ddbfd40fbd374a85f015846">llvm::StringRef::consumeInteger</a>, <a href="#a610bcac0ac7e242f391a34b91889dfa5a902b0d55fddef6f8d651fe1035b7d4bd">Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#aaf19acac548dca3c8f263ceb6a860b57">llvm::VFABI::getVFParamKindFromString</a>, <a href="#a610bcac0ac7e242f391a34b91889dfa5a6adf97f83acf6453d4a6a4b1070f3754">None</a> and <a href="#a610bcac0ac7e242f391a34b91889dfa5ae0aa021e21dddbd6d8cecec71e9cf564">OK</a>.</p>


<p>Referenced by <a href="#a57b4cf2441156c6d912e37e94a7c7a44">tryParseLinearWithRuntimeStep</a>.</p>

</div>
</div>

### tryParseLinearWithCompileTimeStep() {#a5483a1f81120ebaec6d91e466a25c292}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseRet anonymous{VFABIDemangler.cpp}::tryParseLinearWithCompileTimeStep (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; ParseString, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39">VFParamKind</a> &amp; PKind, int &amp; StepOrPos)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The function looks for the following strings at the beginning of the input string <span class="doxyComputerOutput">ParseString</span>:</p>


<p>["l" | "R" | "U" | "L"] {"n"} &lt;number&gt;</p>


<p>On success, it removes the parsed parameter from <span class="doxyComputerOutput">ParseString</span>, sets <span class="doxyComputerOutput">PKind</span> to the correspondent enum value, sets <span class="doxyComputerOutput">LinearStep</span> to &lt;number&gt;, and return success. On a syntax error, it return a parsing error. If nothing is parsed, it returns std::nullopt.</p>


<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a>.</p>


<p>References <a href="#a610bcac0ac7e242f391a34b91889dfa5a6adf97f83acf6453d4a6a4b1070f3754">None</a>, <a href="#a610bcac0ac7e242f391a34b91889dfa5ae0aa021e21dddbd6d8cecec71e9cf564">OK</a> and <a href="#a856e22af4413a5ea9df66d623f35b824">tryParseCompileTimeLinearToken</a>.</p>


<p>Referenced by <a href="#a71eadd5ab74bdb057ebcc6b916924f78">tryParseParameter</a>.</p>

</div>
</div>

### tryParseLinearWithRuntimeStep() {#a57b4cf2441156c6d912e37e94a7c7a44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseRet anonymous{VFABIDemangler.cpp}::tryParseLinearWithRuntimeStep (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; ParseString, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39">VFParamKind</a> &amp; PKind, int &amp; StepOrPos)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The function looks for the following string at the beginning of the input string <span class="doxyComputerOutput">ParseString</span>:</p>


<p>&lt;token&gt; &lt;number&gt;</p>


<p>&lt;token&gt; is one of "ls", "Rs", "Us" or "Ls".</p>


<p>On success, it removes the parsed parameter from <span class="doxyComputerOutput">ParseString</span>, sets <span class="doxyComputerOutput">PKind</span> to the correspondent enum value, sets <span class="doxyComputerOutput">StepOrPos</span> to &lt;number&gt;, and return success. On a syntax error, it return a parsing error. If nothing is parsed, it returns std::nullopt.</p>


<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a>.</p>


<p>References <a href="#a610bcac0ac7e242f391a34b91889dfa5a6adf97f83acf6453d4a6a4b1070f3754">None</a> and <a href="#a4c267f75d0c944ac84dff96f8a4779f3">tryParseLinearTokenWithRuntimeStep</a>.</p>


<p>Referenced by <a href="#a71eadd5ab74bdb057ebcc6b916924f78">tryParseParameter</a>.</p>

</div>
</div>

### tryParseMask() {#a3af3ce355fb0d93f751694070efc4c1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseRet anonymous{VFABIDemangler.cpp}::tryParseMask (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; MangledName, bool &amp; IsMasked)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extracts the <span class="doxyComputerOutput">&lt;mask&gt;</span> information from the mangled string, and sets <span class="doxyComputerOutput">IsMasked</span> accordingly.</p>


<p>If successful, the &lt;mask&gt; token is removed from the input string <span class="doxyComputerOutput">MangledName</span>.</p>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="#a610bcac0ac7e242f391a34b91889dfa5a902b0d55fddef6f8d651fe1035b7d4bd">Error</a> and <a href="#a610bcac0ac7e242f391a34b91889dfa5ae0aa021e21dddbd6d8cecec71e9cf564">OK</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a46c9ccb087f925d00317f16577410a13">llvm::VFABI::tryDemangleForVFABI</a>.</p>

</div>
</div>

### tryParseParameter() {#a71eadd5ab74bdb057ebcc6b916924f78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseRet anonymous{VFABIDemangler.cpp}::tryParseParameter (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; ParseString, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39">VFParamKind</a> &amp; PKind, int &amp; StepOrPos)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Looks into the &lt;parameters&gt; part of the mangled name in search for valid paramaters at the beginning of the string <span class="doxyComputerOutput">ParseString</span>.</p>


<p>On success, it removes the parsed parameter from <span class="doxyComputerOutput">ParseString</span>, sets <span class="doxyComputerOutput">PKind</span> to the correspondent enum value, sets <span class="doxyComputerOutput">StepOrPos</span> accordingly, and return success. On a syntax error, it return a parsing error. If nothing is parsed, it returns std::nullopt.</p>


<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="#a610bcac0ac7e242f391a34b91889dfa5a6adf97f83acf6453d4a6a4b1070f3754">None</a>, <a href="#a610bcac0ac7e242f391a34b91889dfa5ae0aa021e21dddbd6d8cecec71e9cf564">OK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39acbf35bbdad5d09f9072d0e83e78e90e4">llvm::OMP_Uniform</a>, <a href="#a5483a1f81120ebaec6d91e466a25c292">tryParseLinearWithCompileTimeStep</a>, <a href="#a57b4cf2441156c6d912e37e94a7c7a44">tryParseLinearWithRuntimeStep</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">llvm::Vector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a46c9ccb087f925d00317f16577410a13">llvm::VFABI::tryDemangleForVFABI</a>.</p>

</div>
</div>

### tryParseVLEN() {#a14373b1995a870811ec0b24e8c7bb274}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseRet anonymous{VFABIDemangler.cpp}::tryParseVLEN (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; ParseString, <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169c">VFISAKind</a> ISA, std::pair&lt; unsigned, bool &gt; &amp; ParsedVF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract the <span class="doxyComputerOutput">&lt;vlen&gt;</span> information from the mangled string, and sets <span class="doxyComputerOutput">ParsedVF</span> accordingly.</p>


<p>A <span class="doxyComputerOutput">&lt;vlen&gt; == "x"</span> token is interpreted as a scalable vector length and the boolean is set to true, otherwise a nonzero unsigned integer will be directly used as a VF. On success, the <span class="doxyComputerOutput">&lt;vlen&gt;</span> token is removed from the input string <span class="doxyComputerOutput">ParseString</span>.</p>


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1643e7698ddbfd40fbd374a85f015846">llvm::StringRef::consumeInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a610bcac0ac7e242f391a34b91889dfa5a902b0d55fddef6f8d651fe1035b7d4bd">Error</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a610bcac0ac7e242f391a34b91889dfa5ae0aa021e21dddbd6d8cecec71e9cf564">OK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169ca2ce62e1cd502db9d1a7a8295164f6584">llvm::RVV</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169ca8a880ec3350518f78cffab1bd18e97ba">llvm::SVE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a46c9ccb087f925d00317f16577410a13">llvm::VFABI::tryDemangleForVFABI</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
