---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AAPotentialValuesFloating` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl">AAPotentialValuesImpl</a></td>
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

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluescallsiteargument">AAPotentialValuesCallSiteArgument</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesreturned">AAPotentialValuesReturned</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63b843bfcb8c33adbb836d0c66c2bf7">AAPotentialValuesFloating</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adba089cecb7b89737a7fa570790f6b68">updateImpl</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractAttribute::updateImpl(...). <a href="#adba089cecb7b89737a7fa570790f6b68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dfa7d879ffc886a8014f1c9714ec166">handleCmp</a> (Attributor &amp;A, Value &amp;Cmp, Value *LHS, Value *RHS, CmpInst::Predicate Pred, ItemInfo II, SmallVectorImpl&lt; ItemInfo &gt; &amp;Worklist)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if <span class="doxyComputerOutput">Cmp</span> is a comparison we can simplify. <a href="#a9dfa7d879ffc886a8014f1c9714ec166">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49114a789143912efbf912250aea8397">handleSelectInst</a> (Attributor &amp;A, SelectInst &amp;SI, ItemInfo II, SmallVectorImpl&lt; ItemInfo &gt; &amp;Worklist)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4366c809736e919b276b5cda925d17ac">handleLoadInst</a> (Attributor &amp;A, LoadInst &amp;LI, ItemInfo II, SmallVectorImpl&lt; ItemInfo &gt; &amp;Worklist)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0fe28a9dccc66e85a05b9447f4141ef">handlePHINode</a> (Attributor &amp;A, PHINode &amp;PHI, ItemInfo II, SmallVectorImpl&lt; ItemInfo &gt; &amp;Worklist, SmallMapVector&lt; const Function *, LivenessInfo, 4 &gt; &amp;LivenessAAs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3de59e829dffdff466e6c22944ac47a8">handleGenericInst</a> (Attributor &amp;A, Instruction &amp;I, ItemInfo II, SmallVectorImpl&lt; ItemInfo &gt; &amp;Worklist)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the generic, non-optimistic InstSimplfy functionality if we managed to simplify any operand of the instruction <span class="doxyComputerOutput">I</span>. <a href="#a3de59e829dffdff466e6c22944ac47a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad028c9c22883706f017055ecb24d1055">simplifyInstruction</a> (Attributor &amp;A, Instruction &amp;I, ItemInfo II, SmallVectorImpl&lt; ItemInfo &gt; &amp;Worklist, SmallMapVector&lt; const Function *, LivenessInfo, 4 &gt; &amp;LivenessAAs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae86be98f39008a27ba987e282fc8dc2c">genericValueTraversal</a> (Attributor &amp;A, Value *InitialV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23e44ce2e41d7bd2b02c6a3016afb91a">trackStatistics</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#add85e4d78cefc67429904d7492aff9a4">AbstractAttribute::trackStatistics()</a> <a href="#a23e44ce2e41d7bd2b02c6a3016afb91a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 10994 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AAPotentialValuesFloating() {#af63b843bfcb8c33adbb836d0c66c2bf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::AAPotentialValuesFloating (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 10995 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a7bb25dfecff7d7d20f60a3178750dcee">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::AAPotentialValuesImpl</a> and <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAPotentialValues::Attributor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluescallsiteargument/#a1a722cf819606c7a70ed5f1ad55fd593">anonymous{AttributorAttributes.cpp}::AAPotentialValuesCallSiteArgument::AAPotentialValuesCallSiteArgument</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### genericValueTraversal() {#ae86be98f39008a27ba987e282fc8dc2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::genericValueTraversal (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * InitialV)</td>
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



<p>Definition at line 11353 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a135bd9f6645b2fba9c7652cbd7b8a157">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::addValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ac85851126814105f4a92b699293e4141aab418ed12d74fcdd3d6976b470bd2e66">llvm::AA::AnyScope</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAPotentialValues::Attributor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#afa339f4513a2704e8e2dadb6a92faab3">llvm::IRPosition::getAnchorScope</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a5cdc54db452dfdce67b7f0713f822f71">llvm::IRPosition::getCtxI</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues/#a1cfd51c7f4bfa9e26c19ff246b79a6eb">llvm::AAPotentialValues::getState</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#af967a81762eaaf67f292abee4a00180c">llvm::AA::getWithType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#ad4ad93c1d7d4ebde3579c37dcd403982">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::indicatePessimisticFixpoint</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp/#a4e2da0f938b4e92d2d3f099e3b5fe7a0">MaxPotentialValuesIterations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1a7951811e4b085cf68ed3dc3191f36405">llvm::OPTIONAL</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a8d09e795aeee61f61bd7d8ec5383a067">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::recurseForValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57feb935aaafd1bd4bfbb8dc56ad2129">llvm::simplifyInstruction</a> and <a href="/web-llvm/docs/api/structs/llvm/irposition/#a3bee165465962ee97307066da4f0fb13">llvm::IRPosition::value</a>.</p>


<p>Referenced by <a href="#adba089cecb7b89737a7fa570790f6b68">updateImpl</a>.</p>

</div>
</div>

### handleCmp() {#a9dfa7d879ffc886a8014f1c9714ec166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleCmp (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; Cmp, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/iteminfo">ItemInfo</a> II, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/iteminfo">ItemInfo</a> &gt; &amp; Worklist)</td>
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

<p>Check if <span class="doxyComputerOutput">Cmp</span> is a comparison we can simplify.</p>


<p>We handle multiple cases, one in which at least one operand is an (assumed) nullptr. If so, try to simplify it using <a href="/web-llvm/docs/api/structs/llvm/aanonnull">AANonNull</a> on the other operand. Return true if successful, in that case Worklist will be updated.</p>


<p>Definition at line 11019 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a135bd9f6645b2fba9c7652cbd7b8a157">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::addValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAPotentialValues::Attributor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/structs/llvm/informationcache/#af887d734d176f82b42528b55c0bdc4f7">llvm::InformationCache::getAnalysisResultForFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#afa339f4513a2704e8e2dadb6a92faab3">llvm::IRPosition::getAnchorScope</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a8e5f6784c446af664c5c0f6ab3c9fa26">llvm::IRPosition::getCallBaseContext</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues/#a1cfd51c7f4bfa9e26c19ff246b79a6eb">llvm::AAPotentialValues::getState</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#af967a81762eaaf67f292abee4a00180c">llvm::AA::getWithType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ae8abeaeed2f11072b2d064fe70510e9f">llvm::AA::hasAssumedIRAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ac85851126814105f4a92b699293e4141a5c330ebe62fe7984f41ec28c822a869a">llvm::AA::Intraprocedural</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a38d34fceda94c01af95b775632ba8299">llvm::CmpInst::isEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a1e32582702cf5b9d4484c0ce346b2f57">llvm::CmpInst::isFalseWhenEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a5ba8484cef2818d14b85640a903b2598">llvm::CmpInst::isTrueWhenEqual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1aebdf9721be38d1fc1cd6db8c737d1be0">llvm::REQUIRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adccdd5d6b0c85f7917306e296b27c4cd">llvm::simplifyCmpInst</a> and <a href="/web-llvm/docs/api/structs/llvm/irposition/#a3bee165465962ee97307066da4f0fb13">llvm::IRPosition::value</a>.</p>


<p>Referenced by <a href="#ad028c9c22883706f017055ecb24d1055">simplifyInstruction</a>.</p>

</div>
</div>

### handleGenericInst() {#a3de59e829dffdff466e6c22944ac47a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleGenericInst (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/iteminfo">ItemInfo</a> II, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/iteminfo">ItemInfo</a> &gt; &amp; Worklist)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the generic, non-optimistic InstSimplfy functionality if we managed to simplify any operand of the instruction <span class="doxyComputerOutput">I</span>.</p>


<p>Return true if successful, in that case Worklist will be updated.</p>


<p>Definition at line 11283 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAPotentialValues::Attributor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/llvm/informationcache/#af887d734d176f82b42528b55c0bdc4f7">llvm::InformationCache::getAnalysisResultForFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a8e5f6784c446af664c5c0f6ab3c9fa26">llvm::IRPosition::getCallBaseContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ac85851126814105f4a92b699293e4141a5c330ebe62fe7984f41ec28c822a869a">llvm::AA::Intraprocedural</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a367cc3c1cd48f8723586daebe9a17d00">llvm::simplifyInstructionWithOperands</a> and <a href="/web-llvm/docs/api/structs/llvm/irposition/#a3bee165465962ee97307066da4f0fb13">llvm::IRPosition::value</a>.</p>


<p>Referenced by <a href="#ad028c9c22883706f017055ecb24d1055">simplifyInstruction</a>.</p>

</div>
</div>

### handleLoadInst() {#a4366c809736e919b276b5cda925d17ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleLoadInst (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> &amp; LI, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/iteminfo">ItemInfo</a> II, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/iteminfo">ItemInfo</a> &gt; &amp; Worklist)</td>
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



<p>Definition at line 11159 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a135bd9f6645b2fba9c7652cbd7b8a157">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::addValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAPotentialValues::Attributor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#afa339f4513a2704e8e2dadb6a92faab3">llvm::IRPosition::getAnchorScope</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#af30179a08c576d56d2469f5373174c43">llvm::AA::getPotentiallyLoadedValues</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues/#a1cfd51c7f4bfa9e26c19ff246b79a6eb">llvm::AAPotentialValues::getState</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ac85851126814105f4a92b699293e4141ab563ef74be13fcdcf264798ed6af5666">llvm::AA::Interprocedural</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ac85851126814105f4a92b699293e4141a5c330ebe62fe7984f41ec28c822a869a">llvm::AA::Intraprocedural</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a559168f78e20f2d3d0e1763ee6e751ef">llvm::AA::isDynamicallyUnique</a>, <a href="/web-llvm/docs/api/structs/llvm/informationcache/#ae4b3c0d9e255d7969e2a8699ad0fd275">llvm::InformationCache::isOnlyUsedByAssume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ad7be59b8a3d5e2faf55b21c42ed07a63">llvm::AA::isValidInScope</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#ad028c9c22883706f017055ecb24d1055">simplifyInstruction</a>.</p>

</div>
</div>

### handlePHINode() {#ad0fe28a9dccc66e85a05b9447f4141ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handlePHINode (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> &amp; PHI, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/iteminfo">ItemInfo</a> II, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/iteminfo">ItemInfo</a> &gt; &amp; Worklist, <a href="/web-llvm/docs/api/structs/llvm/smallmapvector">SmallMapVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/livenessinfo">LivenessInfo</a>, 4 &gt; &amp; LivenessAAs)</td>
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



<p>Definition at line 11227 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a135bd9f6645b2fba9c7652cbd7b8a157">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::addValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/livenessinfo/#afefc66eade6a3f0bd9fde0926208b2fc">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::LivenessInfo::AnyDead</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAPotentialValues::Attributor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a8936a7eb7c9151c46513b192053afb2e">llvm::IRPosition::function</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#afa339f4513a2704e8e2dadb6a92faab3">llvm::IRPosition::getAnchorScope</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a96130007e2acc25ee2ed2dd8f08f3e18">llvm::IRPosition::getAssociatedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues/#a1cfd51c7f4bfa9e26c19ff246b79a6eb">llvm::AAPotentialValues::getState</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aef9e9fcf4c5dfce90276ca16d91b8e46">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a4a67bf6ab49ae2630d14e3159ef51cf4">llvm::IRPosition::inst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/aaisdead/#a2a290f1c20e4ed78922716dbf0546a6a">llvm::AAIsDead::isEdgeDead</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/livenessinfo/#a173a8e6583650e17eefb53d43cca7516">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::LivenessInfo::LivenessAA</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp/#a7410ae1c5df256622e23ceee6bd19734">mayBeInCycle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1ab50339a10e1de285ac99d4c3990b8693">llvm::NONE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#ad028c9c22883706f017055ecb24d1055">simplifyInstruction</a>.</p>

</div>
</div>

### handleSelectInst() {#a49114a789143912efbf912250aea8397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleSelectInst (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> &amp; SI, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/iteminfo">ItemInfo</a> II, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/iteminfo">ItemInfo</a> &gt; &amp; Worklist)</td>
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



<p>Definition at line 11126 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a135bd9f6645b2fba9c7652cbd7b8a157">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::addValue</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAPotentialValues::Attributor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#afa339f4513a2704e8e2dadb6a92faab3">llvm::IRPosition::getAnchorScope</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a96130007e2acc25ee2ed2dd8f08f3e18">llvm::IRPosition::getAssociatedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues/#a1cfd51c7f4bfa9e26c19ff246b79a6eb">llvm::AAPotentialValues::getState</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a4a67bf6ab49ae2630d14e3159ef51cf4">llvm::IRPosition::inst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4956305191cdba7f9995569d011a5ab7">llvm::isa_and_nonnull</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#ad028c9c22883706f017055ecb24d1055">simplifyInstruction</a>.</p>

</div>
</div>

### simplifyInstruction() {#ad028c9c22883706f017055ecb24d1055}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::simplifyInstruction (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/iteminfo">ItemInfo</a> II, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/iteminfo">ItemInfo</a> &gt; &amp; Worklist, <a href="/web-llvm/docs/api/structs/llvm/smallmapvector">SmallMapVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/livenessinfo">LivenessInfo</a>, 4 &gt; &amp; LivenessAAs)</td>
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



<p>Definition at line 11332 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAPotentialValues::Attributor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a9dfa7d879ffc886a8014f1c9714ec166">handleCmp</a>, <a href="#a3de59e829dffdff466e6c22944ac47a8">handleGenericInst</a>, <a href="#a4366c809736e919b276b5cda925d17ac">handleLoadInst</a>, <a href="#ad0fe28a9dccc66e85a05b9447f4141ef">handlePHINode</a>, <a href="#a49114a789143912efbf912250aea8397">handleSelectInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>

</div>
</div>

### trackStatistics() {#a23e44ce2e41d7bd2b02c6a3016afb91a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::trackStatistics ()</td>
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

<p>Definition at line 11428 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp/#af66d8d938691a6bb5201855082b3d604">STATS_DECLTRACK_FLOATING_ATTR</a>.</p>

</div>
</div>

### updateImpl() {#adba089cecb7b89737a7fa570790f6b68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::updateImpl (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>See AbstractAttribute::updateImpl(...).</p>

<p>Definition at line 10999 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAPotentialValues::Attributor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3ae6b94e58bfd13b21bc786578d9f8ba4a">llvm::CHANGED</a>, <a href="#ae86be98f39008a27ba987e282fc8dc2c">genericValueTraversal</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a96130007e2acc25ee2ed2dd8f08f3e18">llvm::IRPosition::getAssociatedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/potentialvaluesstate/#a12d4f7a1a433368aa1ccd61d969458ba">llvm::PotentialValuesState&lt; std::pair&lt; AA::ValueAndContext, AA::ValueScope &gt; &gt;::getAssumed</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3a46335765005ff44b1fe1e38e5d2ddfcc">llvm::UNCHANGED</a>.</p>

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
