---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/attributefuncs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `AttributeFuncs` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::AttributeFuncs { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AttributeSafetyKind : uint8_t { <a href="#aa01ebfb5122911f6d17fb843d617a953">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a682611c4ec5c544fb17317b40e903a52">isNoFPClassCompatibleType</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is a type legal for the 'nofpclass' attribute. <a href="#a682611c4ec5c544fb17317b40e903a52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2dcaa046e6a38983e74ce28a120ce79">typeIncompatible</a> (Type *Ty, AttributeSet AS, AttributeSafetyKind ASK=ASK_ALL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Which attributes cannot be applied to a type. <a href="#ab2dcaa046e6a38983e74ce28a120ce79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67d569e12c844558c447c1d8c1476f10">getUBImplyingAttributes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get param/return attributes which imply immediate undefined behavior if an invalid value is passed. <a href="#a67d569e12c844558c447c1d8c1476f10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32fe04d73013c7bede32a1e2279cf9e5">areInlineCompatible</a> (const Function &amp;Caller, const Function &amp;Callee)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86c5bed00c85990ce80390e8db10b20b">areOutlineCompatible</a> (const Function &amp;A, const Function &amp;B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if there are any incompatible function attributes between <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span>. <a href="#a86c5bed00c85990ce80390e8db10b20b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae05b3471aef6ffe376ceef99af9b4709">mergeAttributesForInlining</a> (Function &amp;Caller, const Function &amp;Callee)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge caller's and callee's attributes. <a href="#ae05b3471aef6ffe376ceef99af9b4709">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab96d8eec2287f142354ff6d8f3bba27">mergeAttributesForOutlining</a> (Function &amp;Base, const Function &amp;ToMerge)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merges the functions attributes from <span class="doxyComputerOutput">ToMerge</span> into function <span class="doxyComputerOutput">Base</span>. <a href="#aab96d8eec2287f142354ff6d8f3bba27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b02ace8c1f9abda69c009da0432e901">updateMinLegalVectorWidthAttr</a> (Function &amp;Fn, uint64_t Width)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update min-legal-vector-width if it is in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> and less than Width. <a href="#a8b02ace8c1f9abda69c009da0432e901">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### AttributeSafetyKind {#aa01ebfb5122911f6d17fb843d617a953}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AttributeFuncs::AttributeSafetyKind : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ASK_SAFE_TO_DROP<a id="aa01ebfb5122911f6d17fb843d617a953a66e3691152e97b3b795fde63465e530c"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ASK_UNSAFE_TO_DROP<a id="aa01ebfb5122911f6d17fb843d617a953a4fbf4bde0e00e57f95e2a79bfe1ce25a"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ASK_ALL<a id="aa01ebfb5122911f6d17fb843d617a953a63f7650bea2c9781bf7a649098d15b52"></a></td>
<td class="doxyEnumItemDescription"> (= ASK_SAFE_TO_DROP | ASK_UNSAFE_TO_DROP)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### areInlineCompatible() {#a32fe04d73013c7bede32a1e2279cf9e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeFuncs::areInlineCompatible (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Callee)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Return true if the two functions have compatible target-independent attributes for inlining purposes.</p></dd>
</dl>


<p>Declaration at line 1326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2645 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp/#ad6e6415d4d2e809c620d08fb23c1544f">functionsHaveCompatibleAttributes</a>.</p>

</div>
</div>

### areOutlineCompatible() {#a86c5bed00c85990ce80390e8db10b20b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeFuncs::areOutlineCompatible (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if there are any incompatible function attributes between <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] A</td>
<td class="doxyParamItemDescription"><p>- The first function to be compared with.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] B</td>
<td class="doxyParamItemDescription"><p>- The second function to be compared with.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the functions have compatible attributes.</p></dd>
</dl>


<p>Declaration at line 1335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2650 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

### getUBImplyingAttributes() {#a67d569e12c844558c447c1d8c1476f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeMask llvm::AttributeFuncs::getUBImplyingAttributes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get param/return attributes which imply immediate undefined behavior if an invalid value is passed.</p>


<p>For example, this includes noundef (where undef implies UB), but not nonnull (where null implies poison). It also does not include attributes like nocapture, which constrain the function implementation rather than the passed value.</p>


<p>Declaration at line 1322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2418 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/attributemask/#a86730a1a0c270eb9b066301bfaac8581">llvm::AttributeMask::addAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>.</p>

</div>
</div>

### isNoFPClassCompatibleType() {#a682611c4ec5c544fb17317b40e903a52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeFuncs::isNoFPClassCompatibleType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this is a type legal for the 'nofpclass' attribute.</p>


<p>This follows the same type rules as <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator">FPMathOperator</a>.</p>


<p>Declaration at line 1303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2344 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#ac4f7d12f6bda5a60f868f3ec8be99f9c">llvm::FPMathOperator::isSupportedFloatingPointType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#adab9b2e1a33cfbe6f0fa6443046dcaf8">llvm::Attributor::identifyDefaultAbstractAttributes</a>, <a href="#ab2dcaa046e6a38983e74ce28a120ce79">typeIncompatible</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8b0688ee292d40a24ba7117b39d426bd">llvm::InstCombinerImpl::visitReturnInst</a>.</p>

</div>
</div>

### mergeAttributesForInlining() {#ae05b3471aef6ffe376ceef99af9b4709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AttributeFuncs::mergeAttributesForInlining (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Callee)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge caller's and callee's attributes.</p>

<p>Declaration at line 1338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2655 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>.</p>

</div>
</div>

### mergeAttributesForOutlining() {#aab96d8eec2287f142354ff6d8f3bba27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AttributeFuncs::mergeAttributesForOutlining (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Base, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; ToMerge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merges the functions attributes from <span class="doxyComputerOutput">ToMerge</span> into function <span class="doxyComputerOutput">Base</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] Base</td>
<td class="doxyParamItemDescription"><p>- The function being merged into.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] ToMerge</td>
<td class="doxyParamItemDescription"><p>- The function to merge attributes from.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2660 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>.</p>

</div>
</div>

### typeIncompatible() {#ab2dcaa046e6a38983e74ce28a120ce79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeMask llvm::AttributeFuncs::typeIncompatible (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> AS, <a href="#aa01ebfb5122911f6d17fb843d617a953">AttributeSafetyKind</a> ASK=<a href="#aa01ebfb5122911f6d17fb843d617a953a63f7650bea2c9781bf7a649098d15b52">ASK_ALL</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Which attributes cannot be applied to a type.</p>


<p>The argument <span class="doxyComputerOutput">AS</span> is used as a hint for the attributes whose compatibility is being checked against <span class="doxyComputerOutput">Ty</span>. This does not mean the return will be a subset of <span class="doxyComputerOutput">AS</span>, just that attributes that have specific dynamic type compatibilities (i.e <span class="doxyComputerOutput">range</span>) will be checked against what is contained in <span class="doxyComputerOutput">AS</span>. The argument <span class="doxyComputerOutput">ASK</span> indicates, if only attributes that are known to be safely droppable are contained in the mask; only attributes that might be unsafe to drop (e.g., ABI-related attributes) are in the mask; or both.</p>


<p>Declaration at line 1314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2349 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributemask/#a86730a1a0c270eb9b066301bfaac8581">llvm::AttributeMask::addAttribute</a>, <a href="#aa01ebfb5122911f6d17fb843d617a953a66e3691152e97b3b795fde63465e530c">ASK_SAFE_TO_DROP</a>, <a href="#aa01ebfb5122911f6d17fb843d617a953a4fbf4bde0e00e57f95e2a79bfe1ce25a">ASK_UNSAFE_TO_DROP</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#ab50af3bf5ee8727df07c79065d61c204">llvm::AttributeSet::getAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ad7f81241f958a1f5917a3410942d3199">llvm::ConstantRange::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a10eb642c38648a5edb4a6bc7ce217a17">llvm::Attribute::getRange</a>, <a href="#a682611c4ec5c544fb17317b40e903a52">isNoFPClassCompatibleType</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a615317b48f533b3087abb06d3a96319c">llvm::AMDGPULibCalls::fold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#a9154b11bdab240adc9c8acd18cf89717">anonymous{BitcodeReader.cpp}::BitcodeReader::materialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a423393b3ce94c7230d81a41881918ccd">mergeAttributesAndFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad73f9adce7cce90507a082ae3b30eb36">llvm::UpgradeFunctionAttributes</a>.</p>

</div>
</div>

### updateMinLegalVectorWidthAttr() {#a8b02ace8c1f9abda69c009da0432e901}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AttributeFuncs::updateMinLegalVectorWidthAttr (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn, uint64_t Width)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update min-legal-vector-width if it is in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> and less than Width.</p>

<p>Declaration at line 1347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2673 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a01875e4204852069dd4b7938cab4140b">llvm::Function::addFnAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1881146f2dcc2ca57c9c5f77f938db9d">llvm::StringRef::getAsInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4c319db4fe05c27cfe55bd133a87414d">llvm::Function::getFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a968930aea9d9efa8d46dd890fce75643">llvm::Attribute::getValueAsString</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
