---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/diagnosticinfooptimizationbase/argument
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Argument` Struct Reference

<p>Used in the streaming interface as the general argument type. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::DiagnosticInfoOptimizationBase::Argument { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticinfomiroptimization/machineargument">MachineArgument</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MI-specific kinds of diagnostic Arguments. <a href="/web-llvm/docs/api/structs/llvm/diagnosticinfomiroptimization/machineargument/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20a93e745f79ca5937887af7f08ef8ac">Argument</a> (StringRef Str="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aa19965a8f70cf0a0848106b1bc885c">Argument</a> (StringRef Key, const Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a323c1797c8b204041d344850f0aacbff">Argument</a> (StringRef Key, const Type *T)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb7c2ca045226aca66521405cd3b0da1">Argument</a> (StringRef Key, StringRef S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b7190bd7c210ab11692efd5c2a84e85">Argument</a> (StringRef Key, const char *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6a66141b38930cd57f8494b9231d09b">Argument</a> (StringRef Key, int N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa869fae0f884df7e9ac24873bf903c99">Argument</a> (StringRef Key, float N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a072ba5eeec04acb5bb4549fb3968da0c">Argument</a> (StringRef Key, long N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ddce73e55a7e02e3b859601817ccede">Argument</a> (StringRef Key, long long N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad05735ac41f09473d0fadebf7f123161">Argument</a> (StringRef Key, unsigned N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42cda9362ef6e1e04eadf091f82a45a2">Argument</a> (StringRef Key, unsigned long N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d07aa6f42e18144bd41ee7283d7e12e">Argument</a> (StringRef Key, unsigned long long N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35ba289b623deec99c511a458b8aae85">Argument</a> (StringRef Key, ElementCount EC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abad1fd422e9a79b15cd61cb16a7c59d6">Argument</a> (StringRef Key, bool B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a794e58d4bc67cd3e48058622bef3b1d2">Argument</a> (StringRef Key, DebugLoc dl)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab63b7b8c645d85eaa44114fcd1303474">Argument</a> (StringRef Key, InstructionCost C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97e444c76098bb3cce46ad2d51000e00">Key</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71dcf73afcc3e377656e9503a261c42f">Val</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a356f640ee7689ed7d64dd63de1c50e27">Loc</a></td>
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

<p>Used in the streaming interface as the general argument type.</p>


<p>It internally converts everything into a key-value pair.</p>


<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Argument() {#a20a93e745f79ca5937887af7f08ef8ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DiagnosticInfoOptimizationBase::Argument::Argument (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str="")</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="#a97e444c76098bb3cce46ad2d51000e00">Key</a> and <a href="#a71dcf73afcc3e377656e9503a261c42f">Val</a>.</p>


<p>Referenced by <a href="#a6b7190bd7c210ab11692efd5c2a84e85">Argument</a>.</p>

</div>
</div>

### Argument() {#a1aa19965a8f70cf0a0848106b1bc885c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticInfoOptimizationBase::Argument::Argument (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3e999e4bb7297d284f931638721840e5">llvm::GlobalValue::dropLLVMManglingEscape</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a97e444c76098bb3cce46ad2d51000e00">Key</a>, <a href="#a356f640ee7689ed7d64dd63de1c50e27">Loc</a> and <a href="#a71dcf73afcc3e377656e9503a261c42f">Val</a>.</p>

</div>
</div>

### Argument() {#a323c1797c8b204041d344850f0aacbff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticInfoOptimizationBase::Argument::Argument (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="#a97e444c76098bb3cce46ad2d51000e00">Key</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#a71dcf73afcc3e377656e9503a261c42f">Val</a>.</p>

</div>
</div>

### Argument() {#afb7c2ca045226aca66521405cd3b0da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticInfoOptimizationBase::Argument::Argument (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="#a97e444c76098bb3cce46ad2d51000e00">Key</a> and <a href="#a71dcf73afcc3e377656e9503a261c42f">Val</a>.</p>

</div>
</div>

### Argument() {#a6b7190bd7c210ab11692efd5c2a84e85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DiagnosticInfoOptimizationBase::Argument::Argument (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * S)</td>
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



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="#a20a93e745f79ca5937887af7f08ef8ac">Argument</a> and <a href="#a97e444c76098bb3cce46ad2d51000e00">Key</a>.</p>

</div>
</div>

### Argument() {#ae6a66141b38930cd57f8494b9231d09b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticInfoOptimizationBase::Argument::Argument (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, int N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="#a97e444c76098bb3cce46ad2d51000e00">Key</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a71dcf73afcc3e377656e9503a261c42f">Val</a>.</p>

</div>
</div>

### Argument() {#aa869fae0f884df7e9ac24873bf903c99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticInfoOptimizationBase::Argument::Argument (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, float N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="#a97e444c76098bb3cce46ad2d51000e00">Key</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a13c1b5a253da5da49ce33d03dc1efc07">llvm::to_string</a> and <a href="#a71dcf73afcc3e377656e9503a261c42f">Val</a>.</p>

</div>
</div>

### Argument() {#a072ba5eeec04acb5bb4549fb3968da0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticInfoOptimizationBase::Argument::Argument (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, long N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="#a97e444c76098bb3cce46ad2d51000e00">Key</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a71dcf73afcc3e377656e9503a261c42f">Val</a>.</p>

</div>
</div>

### Argument() {#a9ddce73e55a7e02e3b859601817ccede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticInfoOptimizationBase::Argument::Argument (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, long long N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="#a97e444c76098bb3cce46ad2d51000e00">Key</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a71dcf73afcc3e377656e9503a261c42f">Val</a>.</p>

</div>
</div>

### Argument() {#ad05735ac41f09473d0fadebf7f123161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticInfoOptimizationBase::Argument::Argument (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="#a97e444c76098bb3cce46ad2d51000e00">Key</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a71dcf73afcc3e377656e9503a261c42f">Val</a>.</p>

</div>
</div>

### Argument() {#a42cda9362ef6e1e04eadf091f82a45a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticInfoOptimizationBase::Argument::Argument (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, unsigned long N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="#a97e444c76098bb3cce46ad2d51000e00">Key</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a71dcf73afcc3e377656e9503a261c42f">Val</a>.</p>

</div>
</div>

### Argument() {#a9d07aa6f42e18144bd41ee7283d7e12e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticInfoOptimizationBase::Argument::Argument (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, unsigned long long N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="#a97e444c76098bb3cce46ad2d51000e00">Key</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a71dcf73afcc3e377656e9503a261c42f">Val</a>.</p>

</div>
</div>

### Argument() {#a35ba289b623deec99c511a458b8aae85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticInfoOptimizationBase::Argument::Argument (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> EC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="#a97e444c76098bb3cce46ad2d51000e00">Key</a> and <a href="#a71dcf73afcc3e377656e9503a261c42f">Val</a>.</p>

</div>
</div>

### Argument() {#abad1fd422e9a79b15cd61cb16a7c59d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DiagnosticInfoOptimizationBase::Argument::Argument (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, bool B)</td>
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



<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a97e444c76098bb3cce46ad2d51000e00">Key</a> and <a href="#a71dcf73afcc3e377656e9503a261c42f">Val</a>.</p>

</div>
</div>

### Argument() {#a794e58d4bc67cd3e48058622bef3b1d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticInfoOptimizationBase::Argument::Argument (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="#a97e444c76098bb3cce46ad2d51000e00">Key</a>, <a href="#a356f640ee7689ed7d64dd63de1c50e27">Loc</a> and <a href="#a71dcf73afcc3e377656e9503a261c42f">Val</a>.</p>

</div>
</div>

### Argument() {#ab63b7b8c645d85eaa44114fcd1303474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticInfoOptimizationBase::Argument::Argument (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 520 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a97e444c76098bb3cce46ad2d51000e00">Key</a> and <a href="#a71dcf73afcc3e377656e9503a261c42f">Val</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Key {#a97e444c76098bb3cce46ad2d51000e00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DiagnosticInfoOptimizationBase::Argument::Key</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Referenced by <a href="#abad1fd422e9a79b15cd61cb16a7c59d6">Argument</a>, <a href="#a6b7190bd7c210ab11692efd5c2a84e85">Argument</a>, <a href="#a323c1797c8b204041d344850f0aacbff">Argument</a>, <a href="#a1aa19965a8f70cf0a0848106b1bc885c">Argument</a>, <a href="#a794e58d4bc67cd3e48058622bef3b1d2">Argument</a>, <a href="#a35ba289b623deec99c511a458b8aae85">Argument</a>, <a href="#aa869fae0f884df7e9ac24873bf903c99">Argument</a>, <a href="#ab63b7b8c645d85eaa44114fcd1303474">Argument</a>, <a href="#ae6a66141b38930cd57f8494b9231d09b">Argument</a>, <a href="#a9ddce73e55a7e02e3b859601817ccede">Argument</a>, <a href="#a072ba5eeec04acb5bb4549fb3968da0c">Argument</a>, <a href="#afb7c2ca045226aca66521405cd3b0da1">Argument</a>, <a href="#a9d07aa6f42e18144bd41ee7283d7e12e">Argument</a>, <a href="#a42cda9362ef6e1e04eadf091f82a45a2">Argument</a>, <a href="#ad05735ac41f09473d0fadebf7f123161">Argument</a>, <a href="#a20a93e745f79ca5937887af7f08ef8ac">Argument</a> and <a href="/web-llvm/docs/api/structs/llvm/diagnosticinfomiroptimization/machineargument/#a3bd4d803c09fc2671b6b58c661b94fd6">llvm::DiagnosticInfoMIROptimization::MachineArgument::MachineArgument</a>.</p>

</div>
</div>

### Loc {#a356f640ee7689ed7d64dd63de1c50e27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticLocation llvm::DiagnosticInfoOptimizationBase::Argument::Loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Referenced by <a href="#a1aa19965a8f70cf0a0848106b1bc885c">Argument</a> and <a href="#a794e58d4bc67cd3e48058622bef3b1d2">Argument</a>.</p>

</div>
</div>

### Val {#a71dcf73afcc3e377656e9503a261c42f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DiagnosticInfoOptimizationBase::Argument::Val</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Referenced by <a href="#abad1fd422e9a79b15cd61cb16a7c59d6">Argument</a>, <a href="#a323c1797c8b204041d344850f0aacbff">Argument</a>, <a href="#a1aa19965a8f70cf0a0848106b1bc885c">Argument</a>, <a href="#a794e58d4bc67cd3e48058622bef3b1d2">Argument</a>, <a href="#a35ba289b623deec99c511a458b8aae85">Argument</a>, <a href="#aa869fae0f884df7e9ac24873bf903c99">Argument</a>, <a href="#ab63b7b8c645d85eaa44114fcd1303474">Argument</a>, <a href="#ae6a66141b38930cd57f8494b9231d09b">Argument</a>, <a href="#a9ddce73e55a7e02e3b859601817ccede">Argument</a>, <a href="#a072ba5eeec04acb5bb4549fb3968da0c">Argument</a>, <a href="#afb7c2ca045226aca66521405cd3b0da1">Argument</a>, <a href="#a9d07aa6f42e18144bd41ee7283d7e12e">Argument</a>, <a href="#a42cda9362ef6e1e04eadf091f82a45a2">Argument</a>, <a href="#ad05735ac41f09473d0fadebf7f123161">Argument</a>, <a href="#a20a93e745f79ca5937887af7f08ef8ac">Argument</a>, <a href="/web-llvm/docs/api/structs/llvm/diagnosticinfomiroptimization/machineargument/#a3bd4d803c09fc2671b6b58c661b94fd6">llvm::DiagnosticInfoMIROptimization::MachineArgument::MachineArgument</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a80c2c1a9a2f2eec5c7f3bd5485012802">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
