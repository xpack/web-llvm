---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pdb/nativefunctionsymbol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `NativeFunctionSymbol` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::pdb::NativeFunctionSymbol { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativefunctionsymbol-h">llvm/DebugInfo/PDB/Native/NativeFunctionSymbol.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol">NativeRawSymbol</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01884051cd8f39b42d7bb4ba051e1f11">NativeFunctionSymbol</a> (NativeSession &amp;Session, SymIndexId Id, const codeview::ProcSym &amp;Sym, uint32_t RecordOffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e5f20dce02a7dc9b7f0e997cdee93d1">~NativeFunctionSymbol</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58b43229915f69d712b7eacc769a9017">dump</a> (raw_ostream &amp;OS, int Indent, PdbSymbolIdField ShowIdFields, PdbSymbolIdField RecurseIdFields) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76ade4378d1d8a3163b7dfe0d8793075">getAddressOffset</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24c13732e79a6420b3d82fde73c226db">getAddressSection</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b64bba03bfab47ba070f56854310546">getName</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc1226330755d85f0ccdebe657bc8345">getLength</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5ecbbde7e10c0cafda45e86ff103385">getRelativeVirtualAddress</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5826c44542a0838dda4f1ddb42faa3d8">getVirtualAddress</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a998b8b6d4749134e27e473e313ece092">IPDBEnumSymbols</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46cd97d4b03e3d554934be6b9083050b">findInlineFramesByVA</a> (uint64_t VA) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/procsym">codeview::ProcSym</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1614b9e68b7bbc1d1b93b5e8d864d0b">Sym</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64b3b4f4c9492931740650262092bb89">RecordOffset</a> = 0</td>
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


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativefunctionsymbol-h">NativeFunctionSymbol.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NativeFunctionSymbol() {#a01884051cd8f39b42d7bb4ba051e1f11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeFunctionSymbol::NativeFunctionSymbol (<a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession">NativeSession</a> &amp; Session, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a0d95a0af7fff523a0a4bfb7f6b578d12">SymIndexId</a> Id, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/procsym">codeview::ProcSym</a> &amp; Sym, uint32_t RecordOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativefunctionsymbol-h">NativeFunctionSymbol.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativefunctionsymbol-cpp">NativeFunctionSymbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30ba86408593c34af77fdd90df932f8b5261">llvm::pdb::Function</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#a4cbeed8a0b429b5aea245873a199f97b">llvm::pdb::NativeRawSymbol::NativeRawSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadfd0a82c4bf37b1e90b690a22a20692e">llvm::pdb::Offset</a>, <a href="#a64b3b4f4c9492931740650262092bb89">RecordOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a> and <a href="#ac1614b9e68b7bbc1d1b93b5e8d864d0b">Sym</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~NativeFunctionSymbol() {#a7e5f20dce02a7dc9b7f0e997cdee93d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeFunctionSymbol::~NativeFunctionSymbol ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativefunctionsymbol-h">NativeFunctionSymbol.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a58b43229915f69d712b7eacc769a9017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NativeFunctionSymbol::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, int Indent, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2c">PdbSymbolIdField</a> ShowIdFields, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2c">PdbSymbolIdField</a> RecurseIdFields)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativefunctionsymbol-h">NativeFunctionSymbol.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativefunctionsymbol-cpp">NativeFunctionSymbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#aeeda1eb1da6fda8318d0a3093caa3ea2">llvm::pdb::NativeRawSymbol::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a28e0e7c7f7920e3608fea13ec3e4394e">llvm::pdb::dumpSymbolField</a>, <a href="#a76ade4378d1d8a3163b7dfe0d8793075">getAddressOffset</a>, <a href="#a24c13732e79a6420b3d82fde73c226db">getAddressSection</a>, <a href="#acc1226330755d85f0ccdebe657bc8345">getLength</a> and <a href="#a9b64bba03bfab47ba070f56854310546">getName</a>.</p>

</div>
</div>

### findInlineFramesByVA() {#a46cd97d4b03e3d554934be6b9083050b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBEnumSymbols &gt; NativeFunctionSymbol::findInlineFramesByVA (uint64_t VA)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativefunctionsymbol-h">NativeFunctionSymbol.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativefunctionsymbol-cpp">NativeFunctionSymbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/varstreamarray/#a3fd7e15638d42fca988fddf2481a4dd2">llvm::VarStreamArray&lt; ValueType, Extractor &gt;::at</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0883f644d58e1e0e4624e4773b4fc372adaac3f86343855d64fea7cde051faa79">llvm::codeview::CodeOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/symboldeserializer/#a4f31719a3302d53ef0f8ab28e7afc76e">llvm::codeview::SymbolDeserializer::deserializeAs</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/inlinesitesym/#a24c5b99051800dda908ccaf5840fb1a0">llvm::codeview::InlineSiteSym::End</a>, <a href="#a5826c44542a0838dda4f1ddb42faa3d8">getVirtualAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativefunctionsymbol-cpp/#a589ee3e3614f785f2eeb9b69ecbf16e6">inlineSiteContainsAddress</a>, <a href="#a64b3b4f4c9492931740650262092bb89">RecordOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a>, <a href="#ac1614b9e68b7bbc1d1b93b5e8d864d0b">Sym</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getAddressOffset() {#a76ade4378d1d8a3163b7dfe0d8793075}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t NativeFunctionSymbol::getAddressOffset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativefunctionsymbol-h">NativeFunctionSymbol.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativefunctionsymbol-cpp">NativeFunctionSymbol.cpp</a>.</p>


<p>Reference <a href="#ac1614b9e68b7bbc1d1b93b5e8d864d0b">Sym</a>.</p>


<p>Referenced by <a href="#a58b43229915f69d712b7eacc769a9017">dump</a>.</p>

</div>
</div>

### getAddressSection() {#a24c13732e79a6420b3d82fde73c226db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t NativeFunctionSymbol::getAddressSection ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativefunctionsymbol-h">NativeFunctionSymbol.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativefunctionsymbol-cpp">NativeFunctionSymbol.cpp</a>.</p>


<p>Reference <a href="#ac1614b9e68b7bbc1d1b93b5e8d864d0b">Sym</a>.</p>


<p>Referenced by <a href="#a58b43229915f69d712b7eacc769a9017">dump</a>.</p>

</div>
</div>

### getLength() {#acc1226330755d85f0ccdebe657bc8345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t NativeFunctionSymbol::getLength ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativefunctionsymbol-h">NativeFunctionSymbol.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativefunctionsymbol-cpp">NativeFunctionSymbol.cpp</a>.</p>


<p>Reference <a href="#ac1614b9e68b7bbc1d1b93b5e8d864d0b">Sym</a>.</p>


<p>Referenced by <a href="#a58b43229915f69d712b7eacc769a9017">dump</a>.</p>

</div>
</div>

### getName() {#a9b64bba03bfab47ba070f56854310546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string NativeFunctionSymbol::getName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativefunctionsymbol-h">NativeFunctionSymbol.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativefunctionsymbol-cpp">NativeFunctionSymbol.cpp</a>.</p>


<p>Reference <a href="#ac1614b9e68b7bbc1d1b93b5e8d864d0b">Sym</a>.</p>


<p>Referenced by <a href="#a58b43229915f69d712b7eacc769a9017">dump</a>.</p>

</div>
</div>

### getRelativeVirtualAddress() {#af5ecbbde7e10c0cafda45e86ff103385}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t NativeFunctionSymbol::getRelativeVirtualAddress ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativefunctionsymbol-h">NativeFunctionSymbol.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativefunctionsymbol-cpp">NativeFunctionSymbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a> and <a href="#ac1614b9e68b7bbc1d1b93b5e8d864d0b">Sym</a>.</p>

</div>
</div>

### getVirtualAddress() {#a5826c44542a0838dda4f1ddb42faa3d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t NativeFunctionSymbol::getVirtualAddress ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativefunctionsymbol-h">NativeFunctionSymbol.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativefunctionsymbol-cpp">NativeFunctionSymbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a> and <a href="#ac1614b9e68b7bbc1d1b93b5e8d864d0b">Sym</a>.</p>


<p>Referenced by <a href="#a46cd97d4b03e3d554934be6b9083050b">findInlineFramesByVA</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### RecordOffset {#a64b3b4f4c9492931740650262092bb89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::pdb::NativeFunctionSymbol::RecordOffset = 0</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativefunctionsymbol-h">NativeFunctionSymbol.h</a>.</p>


<p>Referenced by <a href="#a46cd97d4b03e3d554934be6b9083050b">findInlineFramesByVA</a> and <a href="#a01884051cd8f39b42d7bb4ba051e1f11">NativeFunctionSymbol</a>.</p>

</div>
</div>

### Sym {#ac1614b9e68b7bbc1d1b93b5e8d864d0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const codeview::ProcSym llvm::pdb::NativeFunctionSymbol::Sym</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativefunctionsymbol-h">NativeFunctionSymbol.h</a>.</p>


<p>Referenced by <a href="#a46cd97d4b03e3d554934be6b9083050b">findInlineFramesByVA</a>, <a href="#a76ade4378d1d8a3163b7dfe0d8793075">getAddressOffset</a>, <a href="#a24c13732e79a6420b3d82fde73c226db">getAddressSection</a>, <a href="#acc1226330755d85f0ccdebe657bc8345">getLength</a>, <a href="#a9b64bba03bfab47ba070f56854310546">getName</a>, <a href="#af5ecbbde7e10c0cafda45e86ff103385">getRelativeVirtualAddress</a>, <a href="#a5826c44542a0838dda4f1ddb42faa3d8">getVirtualAddress</a> and <a href="#a01884051cd8f39b42d7bb4ba051e1f11">NativeFunctionSymbol</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativefunctionsymbol-h">NativeFunctionSymbol.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativefunctionsymbol-cpp">NativeFunctionSymbol.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
