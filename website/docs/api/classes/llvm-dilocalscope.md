---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dilocalscope
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DILocalScope` Class

<p>A scope for locals. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DILocalScope { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for scope-like contexts. <a href="/web-llvm/docs/api/classes/llvm/discope/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilexicalblockbase">DILexicalBlockBase</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subprogram description. <a href="/web-llvm/docs/api/classes/llvm/disubprogram/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69a0d7ba2e30781c0a164477f6860187">DILocalScope</a> (LLVMContext &amp;C, unsigned ID, StorageType Storage, unsigned Tag, ArrayRef&lt; Metadata * &gt; Ops)</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b1c113ced629309f318e999eaf21e36">~DILocalScope</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e0b4a5906e0bc2a7fa033548c59a220">getSubprogram</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the subprogram for this scope. <a href="#a0e0b4a5906e0bc2a7fa033548c59a220">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ec57fadd1270b2120bcebc3c416422f">getNonLexicalBlockFileScope</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the first non <a href="/web-llvm/docs/api/classes/llvm/dilexicalblockfile">DILexicalBlockFile</a> scope of this scope. <a href="#a2ec57fadd1270b2120bcebc3c416422f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae713d283078fedb08e45a4e893508866">cloneScopeForSubprogram</a> (DILocalScope &amp;RootScope, DISubprogram &amp;NewSP, LLVMContext &amp;Ctx, DenseMap&lt; const MDNode *, MDNode * &gt; &amp;Cache)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Traverses the scope chain rooted at RootScope until it hits a Subprogram, recreating the chain with "NewSP" instead. <a href="#ae713d283078fedb08e45a4e893508866">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7232dd5ab71a7bfff29b2608b4c12ede">classof</a> (const Metadata *MD)</td>
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

<p>A scope for locals.</p>


<p>A legal scope for lexical blocks, local variables, and debug info locations. Subclasses are <em><a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a></em>, <em><a href="/web-llvm/docs/api/classes/llvm/dilexicalblock">DILexicalBlock</a></em>, and <em><a href="/web-llvm/docs/api/classes/llvm/dilexicalblockfile">DILexicalBlockFile</a></em>.</p>


<p>Definition at line 1675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### DILocalScope() {#a69a0d7ba2e30781c0a164477f6860187}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DILocalScope::DILocalScope (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned ID, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, unsigned Tag, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; Ops)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/discope/#adade65a33056238a2e1698347d0d167f">llvm::DIScope::DIScope</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a8265bf29997e9e49d47a38a762d4bb0f">llvm::Metadata::Storage</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>


<p>Referenced by <a href="#ae713d283078fedb08e45a4e893508866">cloneScopeForSubprogram</a>, <a href="/web-llvm/docs/api/classes/llvm/dilexicalblockbase/#aae8819061d0ae275728e22c6fe5ca7c1">llvm::DILexicalBlockBase::DILexicalBlockBase</a>, <a href="#a2ec57fadd1270b2120bcebc3c416422f">getNonLexicalBlockFileScope</a>, <a href="/web-llvm/docs/api/classes/llvm/dilexicalblockbase/#aeb9689e14713ca686172c648aa97feab">llvm::DILexicalBlockBase::getScope</a> and <a href="#a4b1c113ced629309f318e999eaf21e36">~DILocalScope</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~DILocalScope() {#a4b1c113ced629309f318e999eaf21e36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DILocalScope::~DILocalScope ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1680 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="#a69a0d7ba2e30781c0a164477f6860187">DILocalScope</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNonLexicalBlockFileScope() {#a2ec57fadd1270b2120bcebc3c416422f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocalScope * DILocalScope::getNonLexicalBlockFileScope ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the first non <a href="/web-llvm/docs/api/classes/llvm/dilexicalblockfile">DILexicalBlockFile</a> scope of this scope.</p>


<p>Return this if it's not a <em>DILexicalBlockFIle</em>; otherwise, look up the scope chain.</p>


<p>Declaration at line 1700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1057 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="#a69a0d7ba2e30781c0a164477f6860187">DILocalScope</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

### getSubprogram() {#a0e0b4a5906e0bc2a7fa033548c59a220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DISubprogram * DILocalScope::getSubprogram ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the subprogram for this scope.</p>


<p>Return this if it's an <em><a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a></em>; otherwise, look up the scope chain.</p>


<p>Declaration at line 1687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1051 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af648a1ecd9b0189801c2c8f8f15ffba3">llvm::getDISubprogram</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a731f3ca3bc29b3acc59ef49fdb067f41">llvm::DwarfCompileUnit::getLexicalBlockDIE</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#a00d8cd249f658980c3d430915f68b6e4">getSubprogram</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a8ce342d09daa9a2d58bad8dad2018e33">anonymous{MachineOutliner.cpp}::MachineOutliner::getSubprogramOrNull</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a214637beca449d58d4313a69a9ba32af">llvm::DIBuilder::insertDeclare</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#adb6aff41bfe64d206d563112993cfb01">llvm::DIBuilder::insertLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dilabel/#aac3623eca2e1dba62d6a6e96db1e576c">llvm::DILabel::isValidLocationForIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable/#ac8c4cb4dde7067286d3e3ce80bf77224">llvm::DILocalVariable::isValidLocationForIntrinsic</a> and <a href="/web-llvm/docs/api/classes/anonymous-safestack-cpp-/safestack/#a77d82dc0922a0f94f90fcc7e9e194035">anonymous{SafeStack.cpp}::SafeStack::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a7232dd5ab71a7bfff29b2608b4c12ede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DILocalScope::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1702 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/metadata/#a91c7b9c7cf6694f41b9030429b582d26">llvm::Metadata::getMetadataID</a>.</p>

</div>
</div>

### cloneScopeForSubprogram() {#ae713d283078fedb08e45a4e893508866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocalScope * DILocalScope::cloneScopeForSubprogram (<a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> &amp; RootScope, <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> &amp; NewSP, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; &amp; Cache)</td>
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

<p>Traverses the scope chain rooted at RootScope until it hits a Subprogram, recreating the chain with "NewSP" instead.</p>

<p>Declaration at line 1692 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1063 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a69a0d7ba2e30781c0a164477f6860187">DILocalScope</a>, <a href="/web-llvm/docs/api/classes/llvm/discope/#adade65a33056238a2e1698347d0d167f">llvm::DIScope::DIScope</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#af8e7c85da0c37b1a8a5099d7a01f03a8">llvm::MDNode::replaceWithUniqued</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a> and <a href="/web-llvm/docs/api/classes/llvm/debugloc/#aac09dfae0aafa3f07db67a5813f454ae">llvm::DebugLoc::replaceInlinedAtSubprogram</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
