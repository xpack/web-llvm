---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AAValueSimplifyImpl` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify">AAValueSimplify</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An abstract interface for value simplify abstract attribute. <a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument">AAValueSimplifyArgument</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifycallsitereturned">AAValueSimplifyCallSiteReturned</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyfloating">AAValueSimplifyFloating</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyfunction">AAValueSimplifyFunction</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyreturned">AAValueSimplifyReturned</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8bc88899bd4ec5c222c0195c108d41f">AAValueSimplifyImpl</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aaf0b4e889521266e9e87ec9a0511ce">initialize</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractAttribute::initialize(...). <a href="#a5aaf0b4e889521266e9e87ec9a0511ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af174738655489092808b152675c84311">getAsStr</a> (Attributor *A) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#ab46cf8c2872fdda027ddc8691afbf498">AbstractAttribute::getAsStr()</a>. <a href="#af174738655489092808b152675c84311">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0ee7f22a933c1c523741e10dafafd97">trackStatistics</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#add85e4d78cefc67429904d7492aff9a4">AbstractAttribute::trackStatistics()</a> <a href="#ac0ee7f22a933c1c523741e10dafafd97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fbd14119f3e6248e220722b2e332942">getAssumedSimplifiedValue</a> (Attributor &amp;A) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AAValueSimplify::getAssumedSimplifiedValue() <a href="#a8fbd14119f3e6248e220722b2e332942">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a469217e1991252d89a236638f25c5293">manifestReplacementValue</a> (Attributor &amp;A, Instruction *CtxI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a value we can use as replacement for the associated one, or nullptr if we don't have one that makes sense. <a href="#a469217e1991252d89a236638f25c5293">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9359926dcece9d9c26725b86829b4103">checkAndUpdate</a> (Attributor &amp;A, const AbstractAttribute &amp;QueryingAA, const IRPosition &amp;IRP, bool Simplify=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function for querying AAValueSimplify and updating candidate. <a href="#a9359926dcece9d9c26725b86829b4103">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AAType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac74c71265c51cb1cd82cebadc0cfa913">askSimplifiedValueFor</a> (Attributor &amp;A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a candidate is found or not. <a href="#ac74c71265c51cb1cd82cebadc0cfa913">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5c043f1337b0357c7bd606d01cfad9d">askSimplifiedValueForOtherAAs</a> (Attributor &amp;A)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e4935f6285534875f64d5399fd6836c">manifest</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractAttribute::manifest(...). <a href="#a7e4935f6285534875f64d5399fd6836c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad277bd35b295f10501e8ead87d705599">indicatePessimisticFixpoint</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractState::indicatePessimisticFixpoint(...). <a href="#ad277bd35b295f10501e8ead87d705599">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63540fe3243b44a62cb656c73274f8ac">ensureType</a> (Attributor &amp;A, Value &amp;V, Type &amp;Ty, Instruction *CtxI, bool Check)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensure the return value is <span class="doxyComputerOutput">V</span> with type <span class="doxyComputerOutput">Ty</span>, if not possible return nullptr. <a href="#a63540fe3243b44a62cb656c73274f8ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad87f4b76b6846d029880d6b9012a7e69">reproduceInst</a> (Attributor &amp;A, const AbstractAttribute &amp;QueryingAA, Instruction &amp;I, Type &amp;Ty, Instruction *CtxI, bool Check, ValueToValueMapTy &amp;VMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reproduce <span class="doxyComputerOutput">I</span> with type <span class="doxyComputerOutput">Ty</span> or return nullptr if that is not posisble. <a href="#ad87f4b76b6846d029880d6b9012a7e69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a450c2f1a2d1c2e08bf66297247baa964">reproduceValue</a> (Attributor &amp;A, const AbstractAttribute &amp;QueryingAA, Value &amp;V, Type &amp;Ty, Instruction *CtxI, bool Check, ValueToValueMapTy &amp;VMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reproduce <span class="doxyComputerOutput">V</span> with type <span class="doxyComputerOutput">Ty</span> or return nullptr if that is not posisble. <a href="#a450c2f1a2d1c2e08bf66297247baa964">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 6146 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AAValueSimplifyImpl() {#ac8bc88899bd4ec5c222c0195c108d41f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::AAValueSimplifyImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 6147 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify/#ae7bf9ba7de768737791369b8a4f2144d">llvm::AAValueSimplify::AAValueSimplify</a> and <a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAValueSimplify::Attributor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument/#a7752e10b2fd7e57210fe52d70800c121">anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::AAValueSimplifyArgument</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifycallsitereturned/#a35b747c5ca0481d7638d69a2a21a70d0">anonymous{AttributorAttributes.cpp}::AAValueSimplifyCallSiteReturned::AAValueSimplifyCallSiteReturned</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyfloating/#a8082c58a54868be9e453bc8c74d7d9ab">anonymous{AttributorAttributes.cpp}::AAValueSimplifyFloating::AAValueSimplifyFloating</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyfunction/#a1faf8c3ad84a4c9f97d66b4820af0e0a">anonymous{AttributorAttributes.cpp}::AAValueSimplifyFunction::AAValueSimplifyFunction</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyreturned/#aea87d6637a7f8a51f214e2e5bee1c9f6">anonymous{AttributorAttributes.cpp}::AAValueSimplifyReturned::AAValueSimplifyReturned</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### askSimplifiedValueFor() {#ac74c71265c51cb1cd82cebadc0cfa913}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AAType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::askSimplifiedValueFor (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>Returns a candidate is found or not.</p>

<p>Definition at line 6287 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAValueSimplify::Attributor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a96130007e2acc25ee2ed2dd8f08f3e18">llvm::IRPosition::getAssociatedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#af5135f33d24ea71544db77941dab1e38">llvm::AbstractAttribute::getIRPosition</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1ab50339a10e1de285ac99d4c3990b8693">llvm::NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1a7951811e4b085cf68ed3dc3191f36405">llvm::OPTIONAL</a> and <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype/#aabe3cb56f76e6a223406ba8fd571f5f4">llvm::ValueSimplifyStateType::SimplifiedAssociatedValue</a>.</p>


<p>Referenced by <a href="#aa5c043f1337b0357c7bd606d01cfad9d">askSimplifiedValueForOtherAAs</a>.</p>

</div>
</div>

### askSimplifiedValueForOtherAAs() {#aa5c043f1337b0357c7bd606d01cfad9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::askSimplifiedValueForOtherAAs (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 6312 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#ac74c71265c51cb1cd82cebadc0cfa913">askSimplifiedValueFor</a> and <a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAValueSimplify::Attributor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument/#a04db9be64fd2281358f89ee3bebca79e">anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyfloating/#a5e38f307b522c2e541b9cccb795186fc">anonymous{AttributorAttributes.cpp}::AAValueSimplifyFloating::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyreturned/#ac9ae54449e677f539c50426011907713">anonymous{AttributorAttributes.cpp}::AAValueSimplifyReturned::updateImpl</a>.</p>

</div>
</div>

### checkAndUpdate() {#a9359926dcece9d9c26725b86829b4103}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::checkAndUpdate (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, bool Simplify=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Helper function for querying AAValueSimplify and updating candidate.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IRP</td>
<td class="doxyParamItemDescription"><p>The value position we are trying to unify with SimplifiedValue</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 6276 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#acff34214cf426db8b010a1d977bd2899">llvm::AbstractAttribute::AbstractAttribute</a>, <a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAValueSimplify::Attributor</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a96130007e2acc25ee2ed2dd8f08f3e18">llvm::IRPosition::getAssociatedValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ac85851126814105f4a92b699293e4141ab563ef74be13fcdcf264798ed6af5666">llvm::AA::Interprocedural</a> and <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype/#a3b30794202b9b3042b5567a270ea8735">llvm::ValueSimplifyStateType::unionAssumed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifycallsitereturned/#a249035cbf55468e38187c74bfcd1204b">anonymous{AttributorAttributes.cpp}::AAValueSimplifyCallSiteReturned::initialize</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyreturned/#ac9ae54449e677f539c50426011907713">anonymous{AttributorAttributes.cpp}::AAValueSimplifyReturned::updateImpl</a>.</p>

</div>
</div>

### getAsStr() {#af174738655489092808b152675c84311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::getAsStr (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> * A)</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#ab46cf8c2872fdda027ddc8691afbf498">AbstractAttribute::getAsStr()</a>.</p>

<p>Definition at line 6159 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAValueSimplify::Attributor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype/#aa3f4bca7ae5e76efbe268190a80a3c9d">llvm::ValueSimplifyStateType::isAtFixpoint</a>, <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype/#aa7a6972b66fea1956156c533cc2e9e82">llvm::ValueSimplifyStateType::isValidState</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype/#aabe3cb56f76e6a223406ba8fd571f5f4">llvm::ValueSimplifyStateType::SimplifiedAssociatedValue</a>.</p>

</div>
</div>

### getAssumedSimplifiedValue() {#a8fbd14119f3e6248e220722b2e332942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Value * &gt; anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::getAssumedSimplifiedValue (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>See AAValueSimplify::getAssumedSimplifiedValue()</p>

<p>Definition at line 6174 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAValueSimplify::Attributor</a> and <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype/#aabe3cb56f76e6a223406ba8fd571f5f4">llvm::ValueSimplifyStateType::SimplifiedAssociatedValue</a>.</p>

</div>
</div>

### indicatePessimisticFixpoint() {#ad277bd35b295f10501e8ead87d705599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::indicatePessimisticFixpoint ()</td>
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

<p>See AbstractState::indicatePessimisticFixpoint(...).</p>

<p>Definition at line 6341 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/irposition/#a96130007e2acc25ee2ed2dd8f08f3e18">llvm::IRPosition::getAssociatedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#ac61c038186769d32f4f8c10168367965">llvm::AbstractState::indicatePessimisticFixpoint</a> and <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype/#aabe3cb56f76e6a223406ba8fd571f5f4">llvm::ValueSimplifyStateType::SimplifiedAssociatedValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument/#a1f3d1dc8fc604a49c072019d874dd237">anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifycallsitereturned/#a249035cbf55468e38187c74bfcd1204b">anonymous{AttributorAttributes.cpp}::AAValueSimplifyCallSiteReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyfloating/#a327e58d77c06661b6d29951f0c441eba">anonymous{AttributorAttributes.cpp}::AAValueSimplifyFloating::initialize</a>, <a href="#a5aaf0b4e889521266e9e87ec9a0511ce">initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument/#a04db9be64fd2281358f89ee3bebca79e">anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifycallsitereturned/#a9d9e2fcc0af74dbeca0bf1583218628a">anonymous{AttributorAttributes.cpp}::AAValueSimplifyCallSiteReturned::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyfloating/#a5e38f307b522c2e541b9cccb795186fc">anonymous{AttributorAttributes.cpp}::AAValueSimplifyFloating::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyreturned/#ac9ae54449e677f539c50426011907713">anonymous{AttributorAttributes.cpp}::AAValueSimplifyReturned::updateImpl</a>.</p>

</div>
</div>

### initialize() {#a5aaf0b4e889521266e9e87ec9a0511ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::initialize (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>See AbstractAttribute::initialize(...).</p>

<p>Definition at line 6151 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAValueSimplify::Attributor</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a96130007e2acc25ee2ed2dd8f08f3e18">llvm::IRPosition::getAssociatedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#af5135f33d24ea71544db77941dab1e38">llvm::AbstractAttribute::getIRPosition</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a> and <a href="#ad277bd35b295f10501e8ead87d705599">indicatePessimisticFixpoint</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument/#a1f3d1dc8fc604a49c072019d874dd237">anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifycallsitereturned/#a249035cbf55468e38187c74bfcd1204b">anonymous{AttributorAttributes.cpp}::AAValueSimplifyCallSiteReturned::initialize</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyfloating/#a327e58d77c06661b6d29951f0c441eba">anonymous{AttributorAttributes.cpp}::AAValueSimplifyFloating::initialize</a>.</p>

</div>
</div>

### manifest() {#a7e4935f6285534875f64d5399fd6836c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::manifest (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>See AbstractAttribute::manifest(...).</p>

<p>Definition at line 6321 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAValueSimplify::Attributor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3ae6b94e58bfd13b21bc786578d9f8ba4a">llvm::CHANGED</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a96130007e2acc25ee2ed2dd8f08f3e18">llvm::IRPosition::getAssociatedValue</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a1405b111f812f19e71bbe4286484ef54">llvm::AbstractAttribute::manifest</a>, <a href="#a469217e1991252d89a236638f25c5293">manifestReplacementValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3a46335765005ff44b1fe1e38e5d2ddfcc">llvm::UNCHANGED</a>.</p>

</div>
</div>

### manifestReplacementValue() {#a469217e1991252d89a236638f25c5293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::manifestReplacementValue (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI)</td>
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

<p>Return a value we can use as replacement for the associated one, or nullptr if we don't have one that makes sense.</p>

<p>Definition at line 6258 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAValueSimplify::Attributor</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a6a0e4ff765ad5ab3c9a53c917f3cf1cd">llvm::IRPosition::getAssociatedType</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a96130007e2acc25ee2ed2dd8f08f3e18">llvm::IRPosition::getAssociatedValue</a>, <a href="#a450c2f1a2d1c2e08bf66297247baa964">reproduceValue</a> and <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype/#aabe3cb56f76e6a223406ba8fd571f5f4">llvm::ValueSimplifyStateType::SimplifiedAssociatedValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifycallsiteargument/#a8779a21bd698d1abfabf4fc3f7fd64b9">anonymous{AttributorAttributes.cpp}::AAValueSimplifyCallSiteArgument::manifest</a> and <a href="#a7e4935f6285534875f64d5399fd6836c">manifest</a>.</p>

</div>
</div>

### trackStatistics() {#ac0ee7f22a933c1c523741e10dafafd97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::trackStatistics ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#add85e4d78cefc67429904d7492aff9a4">AbstractAttribute::trackStatistics()</a></p>

<p>Definition at line 6170 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### ensureType() {#a63540fe3243b44a62cb656c73274f8ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::ensureType (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; V, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> &amp; Ty, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI, bool Check)</td>
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

<p>Ensure the return value is <span class="doxyComputerOutput">V</span> with type <span class="doxyComputerOutput">Ty</span>, if not possible return nullptr.</p>


<p>If <span class="doxyComputerOutput">Check</span> is true we will only verify such an operation would suceed and return a non-nullptr value if that is the case. No IR is generated or modified.</p>


<p>Definition at line 6182 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAValueSimplify::Attributor</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a651563a742c52504d1980955fe75b95d">llvm::Type::canLosslesslyBitCastTo</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/genericconvergenceverifierimpl-h/#a2bb73b5d562083dde29e9091dd81bef3">Check</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a1536669cae3776862c9ed0a566595b7d">llvm::CastInst::CreatePointerBitCastOrAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#af967a81762eaaf67f292abee4a00180c">llvm::AA::getWithType</a> and <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype/#ad0e539b8f2629b0024a998d435822d48">llvm::ValueSimplifyStateType::Ty</a>.</p>


<p>Referenced by <a href="#a450c2f1a2d1c2e08bf66297247baa964">reproduceValue</a>.</p>

</div>
</div>

### reproduceInst() {#ad87f4b76b6846d029880d6b9012a7e69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::reproduceInst (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> &amp; Ty, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI, bool Check, <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VMap)</td>
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

<p>Reproduce <span class="doxyComputerOutput">I</span> with type <span class="doxyComputerOutput">Ty</span> or return nullptr if that is not posisble.</p>


<p>If <span class="doxyComputerOutput">Check</span> is true we will only verify such an operation would suceed and return a non-nullptr value if that is the case. No IR is generated or modified.</p>


<p>Definition at line 6197 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#acff34214cf426db8b010a1d977bd2899">llvm::AbstractAttribute::AbstractAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAValueSimplify::Attributor</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/genericconvergenceverifierimpl-h/#a2bb73b5d562083dde29e9091dd81bef3">Check</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8601ff0320b6e29a13a2194200853425">llvm::isSafeToSpeculativelyExecute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7da684e1cead3524bdd9b0d171aad161">llvm::RemapInstruction</a>, <a href="#a450c2f1a2d1c2e08bf66297247baa964">reproduceValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a> and <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype/#ad0e539b8f2629b0024a998d435822d48">llvm::ValueSimplifyStateType::Ty</a>.</p>


<p>Referenced by <a href="#a450c2f1a2d1c2e08bf66297247baa964">reproduceValue</a>.</p>

</div>
</div>

### reproduceValue() {#a450c2f1a2d1c2e08bf66297247baa964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::reproduceValue (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; V, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> &amp; Ty, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI, bool Check, <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VMap)</td>
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

<p>Reproduce <span class="doxyComputerOutput">V</span> with type <span class="doxyComputerOutput">Ty</span> or return nullptr if that is not posisble.</p>


<p>If <span class="doxyComputerOutput">Check</span> is true we will only verify such an operation would suceed and return a non-nullptr value if that is the case. No IR is generated or modified.</p>


<p>Definition at line 6231 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#acff34214cf426db8b010a1d977bd2899">llvm::AbstractAttribute::AbstractAttribute</a>, <a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAValueSimplify::Attributor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/genericconvergenceverifierimpl-h/#a2bb73b5d562083dde29e9091dd81bef3">Check</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a63540fe3243b44a62cb656c73274f8ac">ensureType</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ac85851126814105f4a92b699293e4141ab563ef74be13fcdcf264798ed6af5666">llvm::AA::Interprocedural</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a1ec1a38ef077070bf9d3760ddbbcfe24">llvm::AA::isValidAtPosition</a>, <a href="/web-llvm/docs/api/classes/llvm/valuemap/#a15f92579a5fc316dab8cd1fad51015ef">llvm::ValueMap&lt; KeyT, ValueT, Config &gt;::lookup</a>, <a href="#ad87f4b76b6846d029880d6b9012a7e69">reproduceInst</a> and <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype/#ad0e539b8f2629b0024a998d435822d48">llvm::ValueSimplifyStateType::Ty</a>.</p>


<p>Referenced by <a href="#a469217e1991252d89a236638f25c5293">manifestReplacementValue</a> and <a href="#ad87f4b76b6846d029880d6b9012a7e69">reproduceInst</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
