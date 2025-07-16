---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/aapotentialvalues
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AAPotentialValues` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::AAPotentialValues { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">llvm/Transforms/IPO/Attributor.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/statewrapper">StateWrapper&lt;StateTy, BaseType, Ts&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to tie a abstract state implementation to an abstract attribute. <a href="/web-llvm/docs/api/structs/llvm/statewrapper/#details">More...</a></p>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53384e8a2d5e2882d0a202919c32473e">Base</a> = <a href="/web-llvm/docs/api/structs/llvm/statewrapper">StateWrapper</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a728c8547efb810fd4df58b3c800165c8">PotentialLLVMValuesState</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05f3b3169e1f6a561b0c38f0150b3867">Attributor</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a335124606eb59fae29ab97c17e818f1e">AAPotentialValues</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a728c8547efb810fd4df58b3c800165c8">PotentialLLVMValuesState</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cfd51c7f4bfa9e26c19ff246b79a6eb">getState</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractAttribute::getState(...). <a href="#a1cfd51c7f4bfa9e26c19ff246b79a6eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a728c8547efb810fd4df58b3c800165c8">PotentialLLVMValuesState</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a569aeb2730ec58a3e8e47ae338b36d7a">getState</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c60a9166697a5812bfaf3d6b83a8411">getName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a7d84d85c6cb8cc16db41d83859096256">AbstractAttribute::getName()</a> <a href="#a0c60a9166697a5812bfaf3d6b83a8411">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a718457932779b1a7740faf16df02efa8">getIdAddr</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#afb1ae982372c7bd88717c53d8f8e5470">AbstractAttribute::getIdAddr()</a> <a href="#a718457932779b1a7740faf16df02efa8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8df6431c5a7e544f2e611ce3676a6b4e">getAssumedSimplifiedValues</a> (Attributor &amp;A, SmallVectorImpl&lt; AA::ValueAndContext &gt; &amp;Values, AA::ValueScope, bool RecurseForSelectAndPHI=false) const =0</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fcfe615ae30e380be72f4606c905004">requiresCallersForArgOrFunction</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#aeb873d328f3ef9c9f88447c0df0be6c5">AbstractAttribute::requiresCallersForArgOrFunction</a>. <a href="#a3fcfe615ae30e380be72f4606c905004">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues">AAPotentialValues</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add1e9f30b3cb68281be8bfc9f8a6439d">createForPosition</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an abstract attribute view for the position <span class="doxyComputerOutput">IRP</span>. <a href="#add1e9f30b3cb68281be8bfc9f8a6439d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbaf43cc6d56847d8f8202623b7f61e7">getSingleValue</a> (Attributor &amp;A, const AbstractAttribute &amp;AA, const IRPosition &amp;IRP, SmallVectorImpl&lt; AA::ValueAndContext &gt; &amp;Values)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the single value in <span class="doxyComputerOutput">Values</span> if any. <a href="#afbaf43cc6d56847d8f8202623b7f61e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a109b4ad3e1dc99269a43fb4ccdc8404a">classof</a> (const AbstractAttribute *AA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function should return true if the type of the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a></span> is <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues">AAPotentialValues</a>. <a href="#a109b4ad3e1dc99269a43fb4ccdc8404a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb9324a5b9eb2871bb0c9dc781b273c2">ID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unique ID (due to the unique address) <a href="#acb9324a5b9eb2871bb0c9dc781b273c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 5315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Base {#a53384e8a2d5e2882d0a202919c32473e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AAPotentialValues::Base =  StateWrapper&lt;PotentialLLVMValuesState, AbstractAttribute&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### Attributor {#a05f3b3169e1f6a561b0c38f0150b3867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 5356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a05f3b3169e1f6a561b0c38f0150b3867">Attributor</a>.</p>


<p>Referenced by <a href="#a335124606eb59fae29ab97c17e818f1e">AAPotentialValues</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesargument/#ad2e632b2959aa1b720fd625cf14d6dee">anonymous{AttributorAttributes.cpp}::AAPotentialValuesArgument::AAPotentialValuesArgument</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluescallsite/#a81cf980422871b5a58ff2945d5ce38b3">anonymous{AttributorAttributes.cpp}::AAPotentialValuesCallSite::AAPotentialValuesCallSite</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluescallsiteargument/#a1a722cf819606c7a70ed5f1ad55fd593">anonymous{AttributorAttributes.cpp}::AAPotentialValuesCallSiteArgument::AAPotentialValuesCallSiteArgument</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluescallsitereturned/#a5aae3465f80ffde0f9f0b2a81d3e90f2">anonymous{AttributorAttributes.cpp}::AAPotentialValuesCallSiteReturned::AAPotentialValuesCallSiteReturned</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#af63b843bfcb8c33adbb836d0c66c2bf7">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::AAPotentialValuesFloating</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfunction/#ae0ebddd574ba43c75794c26cb3d185a2">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFunction::AAPotentialValuesFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a7bb25dfecff7d7d20f60a3178750dcee">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::AAPotentialValuesImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesreturned/#a2264c5258dcdb1bcbec30c555f85ce75">anonymous{AttributorAttributes.cpp}::AAPotentialValuesReturned::AAPotentialValuesReturned</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a135bd9f6645b2fba9c7652cbd7b8a157">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::addValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a98e912ad4f52dcd78856d78ad4c06338">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::askOtherAA</a>, <a href="#a05f3b3169e1f6a561b0c38f0150b3867">Attributor</a>, <a href="#add1e9f30b3cb68281be8bfc9f8a6439d">createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ae86be98f39008a27ba987e282fc8dc2c">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::genericValueTraversal</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#af2a41297cc7eaf1995081df9a788b778">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a957f22748fdfd31dfbe31f71feb5329b">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::getAssumedSimplifiedValues</a>, <a href="#afbaf43cc6d56847d8f8202623b7f61e7">getSingleValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#ae957d55f18d016455143fa3b219c5203">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::giveUpOnIntraprocedural</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a9dfa7d879ffc886a8014f1c9714ec166">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleCmp</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a3de59e829dffdff466e6c22944ac47a8">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleGenericInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a4366c809736e919b276b5cda925d17ac">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleLoadInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ad0fe28a9dccc66e85a05b9447f4141ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handlePHINode</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a49114a789143912efbf912250aea8397">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleSelectInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesargument/#a9820ec9c7c0f863ac4ee6269af81cf3e">anonymous{AttributorAttributes.cpp}::AAPotentialValuesArgument::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a92d1a2aa02b302934a11d953531de329">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesreturned/#a30f92140edfc60c710d849308c039161">anonymous{AttributorAttributes.cpp}::AAPotentialValuesReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#aaf6f1a343b2a0c4e03abaff3569e5269">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesreturned/#a1cfca839ff13dd1c214a5dae9c737bda">anonymous{AttributorAttributes.cpp}::AAPotentialValuesReturned::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a8d09e795aeee61f61bd7d8ec5383a067">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::recurseForValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ad028c9c22883706f017055ecb24d1055">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::simplifyInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesargument/#a2cc688aac3b055fb8d0cca7033823473">anonymous{AttributorAttributes.cpp}::AAPotentialValuesArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluescallsitereturned/#a326827ab35aa09c37cb1a4ee329f67ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesCallSiteReturned::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#adba089cecb7b89737a7fa570790f6b68">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfunction/#a630766c50f88486d69977d19fbd38e16">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a7bcb72f93d3f32d45fccf13274b5e6b5">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesreturned/#a8f6027dabb6a1e32d6d01e904d6372a0">anonymous{AttributorAttributes.cpp}::AAPotentialValuesReturned::updateImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AAPotentialValues() {#a335124606eb59fae29ab97c17e818f1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AAPotentialValues::AAPotentialValues (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 5318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#a05f3b3169e1f6a561b0c38f0150b3867">Attributor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a7bb25dfecff7d7d20f60a3178750dcee">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::AAPotentialValuesImpl</a> and <a href="#add1e9f30b3cb68281be8bfc9f8a6439d">createForPosition</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getIdAddr() {#a718457932779b1a7740faf16df02efa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::AAPotentialValues::getIdAddr ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#afb1ae982372c7bd88717c53d8f8e5470">AbstractAttribute::getIdAddr()</a></p>

<p>Definition at line 5340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#acb9324a5b9eb2871bb0c9dc781b273c2">ID</a>.</p>

</div>
</div>

### getName() {#a0c60a9166697a5812bfaf3d6b83a8411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string llvm::AAPotentialValues::getName ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a7d84d85c6cb8cc16db41d83859096256">AbstractAttribute::getName()</a></p>

<p>Definition at line 5337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### getState() {#a1cfd51c7f4bfa9e26c19ff246b79a6eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PotentialLLVMValuesState &amp; llvm::AAPotentialValues::getState ()</td>
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

<p>See AbstractAttribute::getState(...).</p>

<p>Definition at line 5324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ae86be98f39008a27ba987e282fc8dc2c">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::genericValueTraversal</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#af2a41297cc7eaf1995081df9a788b778">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#ae957d55f18d016455143fa3b219c5203">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::giveUpOnIntraprocedural</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a9dfa7d879ffc886a8014f1c9714ec166">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleCmp</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a4366c809736e919b276b5cda925d17ac">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleLoadInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ad0fe28a9dccc66e85a05b9447f4141ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handlePHINode</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a49114a789143912efbf912250aea8397">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleSelectInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#ad4ad93c1d7d4ebde3579c37dcd403982">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::indicatePessimisticFixpoint</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a92d1a2aa02b302934a11d953531de329">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesreturned/#a30f92140edfc60c710d849308c039161">anonymous{AttributorAttributes.cpp}::AAPotentialValuesReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a8d09e795aeee61f61bd7d8ec5383a067">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::recurseForValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesargument/#a2cc688aac3b055fb8d0cca7033823473">anonymous{AttributorAttributes.cpp}::AAPotentialValuesArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluescallsitereturned/#a326827ab35aa09c37cb1a4ee329f67ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesCallSiteReturned::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesreturned/#a8f6027dabb6a1e32d6d01e904d6372a0">anonymous{AttributorAttributes.cpp}::AAPotentialValuesReturned::updateImpl</a>.</p>

</div>
</div>

### getState() {#a569aeb2730ec58a3e8e47ae338b36d7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PotentialLLVMValuesState &amp; llvm::AAPotentialValues::getState ()</td>
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



<p>Definition at line 5325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getAssumedSimplifiedValues() {#a8df6431c5a7e544f2e611ce3676a6b4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AAPotentialValues::getAssumedSimplifiedValues (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/aa/valueandcontext">AA::ValueAndContext</a> &gt; &amp; Values, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ac85851126814105f4a92b699293e4141">AA::ValueScope</a>, bool RecurseForSelectAndPHI=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a109b4ad3e1dc99269a43fb4ccdc8404a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAPotentialValues::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> * AA)</td>
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

<p>This function should return true if the type of the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a></span> is <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues">AAPotentialValues</a>.</p>

<p>Definition at line 5344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#acb9324a5b9eb2871bb0c9dc781b273c2">ID</a>.</p>

</div>
</div>

### createForPosition() {#add1e9f30b3cb68281be8bfc9f8a6439d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAPotentialValues &amp; llvm::AAPotentialValues::createForPosition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>Create an abstract attribute view for the position <span class="doxyComputerOutput">IRP</span>.</p>

<p>Definition at line 5328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a335124606eb59fae29ab97c17e818f1e">AAPotentialValues</a> and <a href="#a05f3b3169e1f6a561b0c38f0150b3867">Attributor</a>.</p>

</div>
</div>

### getSingleValue() {#afbaf43cc6d56847d8f8202623b7f61e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AAPotentialValues::getSingleValue (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; AA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/aa/valueandcontext">AA::ValueAndContext</a> &gt; &amp; Values)</td>
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

<p>Extract the single value in <span class="doxyComputerOutput">Values</span> if any.</p>

<p>Declaration at line 5332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 10779 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a05f3b3169e1f6a561b0c38f0150b3867">Attributor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a1e7aede47c97d1e610eeb8bdf152f4cc">llvm::AA::combineOptionalValuesInAAValueLatice</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a> and <a href="/web-llvm/docs/api/structs/llvm/irposition/#a6a0e4ff765ad5ab3c9a53c917f3cf1cd">llvm::IRPosition::getAssociatedType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a853ba647ef2e86e05cd988dae8ed8897">llvm::Attributor::getAssumedConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a529439af5980ea04e96200187061c86d">llvm::Attributor::getAssumedSimplified</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#aaf6f1a343b2a0c4e03abaff3569e5269">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::manifest</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesreturned/#a1cfca839ff13dd1c214a5dae9c737bda">anonymous{AttributorAttributes.cpp}::AAPotentialValuesReturned::manifest</a>.</p>

</div>
</div>

### requiresCallersForArgOrFunction() {#a3fcfe615ae30e380be72f4606c905004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAPotentialValues::requiresCallersForArgOrFunction ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#aeb873d328f3ef9c9f88447c0df0be6c5">AbstractAttribute::requiresCallersForArgOrFunction</a>.</p>

<p>Definition at line 5321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#acb9324a5b9eb2871bb0c9dc781b273c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char AAPotentialValues::ID = 0</td>
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

<p>Unique ID (due to the unique address)</p>

<p>Definition at line 5349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="#a109b4ad3e1dc99269a43fb4ccdc8404a">classof</a>, <a href="#a718457932779b1a7740faf16df02efa8">getIdAddr</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuattributor-cpp-/#a54acd54cc3db43b11d42ebf210d08cf7">anonymous{AMDGPUAttributor.cpp}::runImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
