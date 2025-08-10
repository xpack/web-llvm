---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/abstractcallsite
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AbstractCallSite` Class

<p><a href="/web-llvm/docs/api/classes/llvm/abstractcallsite">AbstractCallSite</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AbstractCallSite { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">llvm/IR/AbstractCallSite.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582d0050c740c1f23bce6bc0c8c5b189">AbstractCallSite</a> (const Use *U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sole constructor for abstract call sites (ACS). <a href="#a582d0050c740c1f23bce6bc0c8c5b189">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a849dee873893038338c06b0829b41ca4">operator bool</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Conversion operator to conveniently check for a valid/initialized ACS. <a href="#a849dee873893038338c06b0829b41ca4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d97fd714e72a72bd6d96a8b1ebf62ea">getInstruction</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the underlying instruction. <a href="#a1d97fd714e72a72bd6d96a8b1ebf62ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27b382e987878c9f338d79220acc06b2">isDirectCall</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this ACS represents a direct call. <a href="#a27b382e987878c9f338d79220acc06b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31b793fd30a35a9db6bbd8ead7796ba0">isIndirectCall</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this ACS represents an indirect call. <a href="#a31b793fd30a35a9db6bbd8ead7796ba0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2300cb53451591b87c7c5621c31643a2">isCallbackCall</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this ACS represents a callback call. <a href="#a2300cb53451591b87c7c5621c31643a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c967c8ed9f20b937ad425a0992eab81">isCallee</a> (Value::const_user_iterator UI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">UI</span> is the use that defines the callee of this ACS. <a href="#a5c967c8ed9f20b937ad425a0992eab81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a186e1b3785876bc1827f2c352f831a36">isCallee</a> (const Use *U) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">U</span> is the use that defines the callee of this ACS. <a href="#a186e1b3785876bc1827f2c352f831a36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8b5e4f9ae59fedfc0f0be8395992ea3">getNumArgOperands</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of parameters of the callee. <a href="#ab8b5e4f9ae59fedfc0f0be8395992ea3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e8ae04873ef7a72fbad37852333d290">getCallArgOperandNo</a> (Argument &amp;Arg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the operand index of the underlying instruction associated with <span class="doxyComputerOutput">Arg</span>. <a href="#a7e8ae04873ef7a72fbad37852333d290">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a2fe9e8614a228a5dcf747c4574c815">getCallArgOperandNo</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the operand index of the underlying instruction associated with the function parameter number <span class="doxyComputerOutput">ArgNo</span> or -1 if there is none. <a href="#a5a2fe9e8614a228a5dcf747c4574c815">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6066aaa9c2bcca469acdce4369e03712">getCallArgOperand</a> (Argument &amp;Arg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the operand of the underlying instruction associated with <span class="doxyComputerOutput">Arg</span>. <a href="#a6066aaa9c2bcca469acdce4369e03712">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61d314ffacb9684d0b278e034f2d517a">getCallArgOperand</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the operand of the underlying instruction associated with the function parameter number <span class="doxyComputerOutput">ArgNo</span> or nullptr if there is none. <a href="#a61d314ffacb9684d0b278e034f2d517a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08682577ed47d8887ffb956192aa379d">getCallArgOperandNoForCallee</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the operand index of the underlying instruction associated with the callee of this ACS. <a href="#a08682577ed47d8887ffb956192aa379d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a377c884b7ab6a21ce8f1113da49094f1">getCalleeUseForCallback</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the use of the callee value in the underlying instruction. <a href="#a377c884b7ab6a21ce8f1113da49094f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91e818b6c5395b706e4d6ec60f636800">getCalledOperand</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the pointer to function that is being called. <a href="#a91e818b6c5395b706e4d6ec60f636800">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe5141e594e4351ab2b1f5e73c736733">getCalledFunction</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the function being called if this is a direct call, otherwise return null (if it's an indirect call). <a href="#abe5141e594e4351ab2b1f5e73c736733">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42ff0e00e94a4c78fc910510e45aa9b4">CB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The underlying call site: caller -&gt; callee, if this is a direct or indirect call site caller -&gt; broker function, if this is a callback call site. <a href="#a42ff0e00e94a4c78fc910510e45aa9b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/abstractcallsite/callbackinfo">CallbackInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a147a69d769fd0a682b878442202a65">CI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The encoding of a callback with regards to the underlying instruction. <a href="#a7a147a69d769fd0a682b878442202a65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a401e244b78386047c64edc64f80ba9c0">getCallbackUses</a> (const CallBase &amp;CB, SmallVectorImpl&lt; const Use * &gt; &amp;CallbackUses)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add operand uses of <span class="doxyComputerOutput">CB</span> that represent callback uses into <span class="doxyComputerOutput">CallbackUses</span>. <a href="#a401e244b78386047c64edc64f80ba9c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/abstractcallsite">AbstractCallSite</a>.</p>


<p>An abstract call site is a wrapper that allows to treat direct, indirect, and callback calls the same. If an abstract call site represents a direct or indirect call site it behaves like a stripped down version of a normal call site object. The abstract call site can also represent a callback call, thus the fact that the initially called function (=broker) may invoke a third one (=callback callee). In this case, the abstract call site hides the middle man, hence the broker function. The result is a representation of the callback call, inside the broker, but in the context of the original call to the broker.</p>


<p>There are up to three functions involved when we talk about callback call sites. The caller (1), which invokes the broker function. The broker function (2), that will invoke the callee zero or more times. And finally the callee (3), which is the target of the callback call.</p>


<p>The abstract call site will handle the mapping from parameters to arguments depending on the semantic of the broker function. However, it is important to note that the mapping is often partial. Thus, some arguments of the call/invoke instruction are mapped to parameters of the callee while others are not.</p>


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AbstractCallSite() {#a582d0050c740c1f23bce6bc0c8c5b189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AbstractCallSite::AbstractCallSite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sole constructor for abstract call sites (ACS).</p>


<p>Create an abstract call site from a use.</p>


<p>An abstract call site can only be constructed through a <a href="/web-llvm/docs/api/classes/llvm/use">llvm::Use</a> because each operand (=use) of an instruction could potentially be a different abstract call site. Furthermore, even if the value of the <a href="/web-llvm/docs/api/classes/llvm/use">llvm::Use</a> is the same, and the user is as well, the abstract call sites might not be.</p>


<p>If a use is not associated with an abstract call site the constructed ACS will evaluate to false if converted to a boolean.</p>


<p>If the use is the callee use of a call or invoke instruction, the constructed abstract call site will behave as a llvm::CallSite would.</p>


<p>If the use is not a callee use of a call or invoke instruction, the callback metadata is used to determine the argument &lt;-&gt; parameter mapping as well as the callee of the abstract call site.</p>


<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/abstractcallsite-cpp">AbstractCallSite.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mdoperand/#ac5d52549f5e52702a331fbc4bd7eb512">llvm::MDOperand::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a571612461ea4af620bc4c441d61579a3">llvm::MDNode::operands</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#a849dee873893038338c06b0829b41ca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AbstractCallSite::operator bool ()</td>
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

<p>Conversion operator to conveniently check for a valid/initialized ACS.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCallArgOperand() {#a6066aaa9c2bcca469acdce4369e03712}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::AbstractCallSite::getCallArgOperand (<a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> &amp; Arg)</td>
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

<p>Return the operand of the underlying instruction associated with <span class="doxyComputerOutput">Arg</span>.</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/argument/#ab205d366b1137026c32f5678f7cc2726">llvm::Argument::getArgNo</a> and <a href="#a6066aaa9c2bcca469acdce4369e03712">getCallArgOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a8d0a2ebeeedeb0bd16a52affb7f6ed88">llvm::Attributor::checkForAllCallSites</a>, <a href="#a6066aaa9c2bcca469acdce4369e03712">getCallArgOperand</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a>.</p>

</div>
</div>

### getCallArgOperand() {#a61d314ffacb9684d0b278e034f2d517a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::AbstractCallSite::getCallArgOperand (unsigned ArgNo)</td>
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

<p>Return the operand of the underlying instruction associated with the function parameter number <span class="doxyComputerOutput">ArgNo</span> or nullptr if there is none.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>


<p>Reference <a href="#a27b382e987878c9f338d79220acc06b2">isDirectCall</a>.</p>

</div>
</div>

### getCallArgOperandNo() {#a7e8ae04873ef7a72fbad37852333d290}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AbstractCallSite::getCallArgOperandNo (<a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> &amp; Arg)</td>
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

<p>Return the operand index of the underlying instruction associated with <span class="doxyComputerOutput">Arg</span>.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/argument/#ab205d366b1137026c32f5678f7cc2726">llvm::Argument::getArgNo</a> and <a href="#a7e8ae04873ef7a72fbad37852333d290">getCallArgOperandNo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/irposition/#a882f8f4551f4267174aa36b7e3b68a97">llvm::IRPosition::callsite_argument</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a265735d2c2edc0a1a03611e7aadd24cd">llvm::IRPosition::getAssociatedArgument</a>, <a href="#a7e8ae04873ef7a72fbad37852333d290">getCallArgOperandNo</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a>.</p>

</div>
</div>

### getCallArgOperandNo() {#a5a2fe9e8614a228a5dcf747c4574c815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AbstractCallSite::getCallArgOperandNo (unsigned ArgNo)</td>
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

<p>Return the operand index of the underlying instruction associated with the function parameter number <span class="doxyComputerOutput">ArgNo</span> or -1 if there is none.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>


<p>Reference <a href="#a27b382e987878c9f338d79220acc06b2">isDirectCall</a>.</p>

</div>
</div>

### getCallArgOperandNoForCallee() {#a08682577ed47d8887ffb956192aa379d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AbstractCallSite::getCallArgOperandNoForCallee ()</td>
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

<p>Return the operand index of the underlying instruction associated with the callee of this ACS.</p>


<p>Only valid for callback calls!</p>


<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a2300cb53451591b87c7c5621c31643a2">isCallbackCall</a>.</p>


<p>Referenced by <a href="#a91e818b6c5395b706e4d6ec60f636800">getCalledOperand</a> and <a href="#a377c884b7ab6a21ce8f1113da49094f1">getCalleeUseForCallback</a>.</p>

</div>
</div>

### getCalledFunction() {#abe5141e594e4351ab2b1f5e73c736733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::AbstractCallSite::getCalledFunction ()</td>
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

<p>Return the function being called if this is a direct call, otherwise return null (if it's an indirect call).</p>

<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#a91e818b6c5395b706e4d6ec60f636800">getCalledOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a8d0a2ebeeedeb0bd16a52affb7f6ed88">llvm::Attributor::checkForAllCallSites</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa273a7c3463d96e7f545c205ff3b50e3">llvm::forEachCallbackFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a265735d2c2edc0a1a03611e7aadd24cd">llvm::IRPosition::getAssociatedArgument</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a273e9b97fc0dfec8df7cf4294d9b87fe">llvm::Attributor::isValidFunctionSignatureRewrite</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a>.</p>

</div>
</div>

### getCalledOperand() {#a91e818b6c5395b706e4d6ec60f636800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::AbstractCallSite::getCalledOperand ()</td>
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

<p>Return the pointer to function that is being called.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>


<p>References <a href="#a08682577ed47d8887ffb956192aa379d">getCallArgOperandNoForCallee</a> and <a href="#a27b382e987878c9f338d79220acc06b2">isDirectCall</a>.</p>


<p>Referenced by <a href="#abe5141e594e4351ab2b1f5e73c736733">getCalledFunction</a>.</p>

</div>
</div>

### getCalleeUseForCallback() {#a377c884b7ab6a21ce8f1113da49094f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Use &amp; llvm::AbstractCallSite::getCalleeUseForCallback ()</td>
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

<p>Return the use of the callee value in the underlying instruction.</p>


<p>Only valid for callback calls!</p>


<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a08682577ed47d8887ffb956192aa379d">getCallArgOperandNoForCallee</a>, <a href="#a1d97fd714e72a72bd6d96a8b1ebf62ea">getInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a3f3b252f63d32a9a6e05208ce26562bf">llvm::User::getOperandUse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a8d0a2ebeeedeb0bd16a52affb7f6ed88">llvm::Attributor::checkForAllCallSites</a>.</p>

</div>
</div>

### getInstruction() {#a1d97fd714e72a72bd6d96a8b1ebf62ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallBase * llvm::AbstractCallSite::getInstruction ()</td>
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

<p>Return the underlying instruction.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/irposition/#a882f8f4551f4267174aa36b7e3b68a97">llvm::IRPosition::callsite_argument</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a8d0a2ebeeedeb0bd16a52affb7f6ed88">llvm::Attributor::checkForAllCallSites</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#af05ad96486c97ea7158a65507aaee0ef">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::createReplacementValues</a>, <a href="#a377c884b7ab6a21ce8f1113da49094f1">getCalleeUseForCallback</a> and <a href="/web-llvm/docs/api/structs/llvm/attributor/#a273e9b97fc0dfec8df7cf4294d9b87fe">llvm::Attributor::isValidFunctionSignatureRewrite</a>.</p>

</div>
</div>

### getNumArgOperands() {#ab8b5e4f9ae59fedfc0f0be8395992ea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AbstractCallSite::getNumArgOperands ()</td>
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

<p>Return the number of parameters of the callee.</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>


<p>Reference <a href="#a27b382e987878c9f338d79220acc06b2">isDirectCall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/irposition/#a882f8f4551f4267174aa36b7e3b68a97">llvm::IRPosition::callsite_argument</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a8d0a2ebeeedeb0bd16a52affb7f6ed88">llvm::Attributor::checkForAllCallSites</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a265735d2c2edc0a1a03611e7aadd24cd">llvm::IRPosition::getAssociatedArgument</a> and <a href="/web-llvm/docs/api/structs/llvm/attributor/#a273e9b97fc0dfec8df7cf4294d9b87fe">llvm::Attributor::isValidFunctionSignatureRewrite</a>.</p>

</div>
</div>

### isCallbackCall() {#a2300cb53451591b87c7c5621c31643a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AbstractCallSite::isCallbackCall ()</td>
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

<p>Return true if this ACS represents a callback call.</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a8d0a2ebeeedeb0bd16a52affb7f6ed88">llvm::Attributor::checkForAllCallSites</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2fbc912ee1cbb5ddcaea71940aa33685">llvm::forEachCallbackCallSite</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a265735d2c2edc0a1a03611e7aadd24cd">llvm::IRPosition::getAssociatedArgument</a>, <a href="#a08682577ed47d8887ffb956192aa379d">getCallArgOperandNoForCallee</a>, <a href="#a27b382e987878c9f338d79220acc06b2">isDirectCall</a>, <a href="#a31b793fd30a35a9db6bbd8ead7796ba0">isIndirectCall</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a273e9b97fc0dfec8df7cf4294d9b87fe">llvm::Attributor::isValidFunctionSignatureRewrite</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a>.</p>

</div>
</div>

### isCallee() {#a5c967c8ed9f20b937ad425a0992eab81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AbstractCallSite::isCallee (<a href="/web-llvm/docs/api/classes/llvm/value/#a146665db2d7a79fa164098370a3a34c4">Value::const_user_iterator</a> UI)</td>
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

<p>Return true if <span class="doxyComputerOutput">UI</span> is the use that defines the callee of this ACS.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>


<p>Reference <a href="#a5c967c8ed9f20b937ad425a0992eab81">isCallee</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a8d0a2ebeeedeb0bd16a52affb7f6ed88">llvm::Attributor::checkForAllCallSites</a> and <a href="#a5c967c8ed9f20b937ad425a0992eab81">isCallee</a>.</p>

</div>
</div>

### isCallee() {#a186e1b3785876bc1827f2c352f831a36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AbstractCallSite::isCallee (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * U)</td>
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

<p>Return true if <span class="doxyComputerOutput">U</span> is the use that defines the callee of this ACS.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#a27b382e987878c9f338d79220acc06b2">isDirectCall</a>.</p>

</div>
</div>

### isDirectCall() {#a27b382e987878c9f338d79220acc06b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AbstractCallSite::isDirectCall ()</td>
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

<p>Return true if this ACS represents a direct call.</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>


<p>Reference <a href="#a2300cb53451591b87c7c5621c31643a2">isCallbackCall</a>.</p>


<p>Referenced by <a href="#a61d314ffacb9684d0b278e034f2d517a">getCallArgOperand</a>, <a href="#a5a2fe9e8614a228a5dcf747c4574c815">getCallArgOperandNo</a>, <a href="#a91e818b6c5395b706e4d6ec60f636800">getCalledOperand</a>, <a href="#ab8b5e4f9ae59fedfc0f0be8395992ea3">getNumArgOperands</a> and <a href="#a186e1b3785876bc1827f2c352f831a36">isCallee</a>.</p>

</div>
</div>

### isIndirectCall() {#a31b793fd30a35a9db6bbd8ead7796ba0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AbstractCallSite::isIndirectCall ()</td>
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

<p>Return true if this ACS represents an indirect call.</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>


<p>Reference <a href="#a2300cb53451591b87c7c5621c31643a2">isCallbackCall</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CB {#a42ff0e00e94a4c78fc910510e45aa9b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallBase* llvm::AbstractCallSite::CB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The underlying call site: caller -&gt; callee, if this is a direct or indirect call site caller -&gt; broker function, if this is a callback call site.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>

</div>
</div>

### CI {#a7a147a69d769fd0a682b878442202a65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallbackInfo llvm::AbstractCallSite::CI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The encoding of a callback with regards to the underlying instruction.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getCallbackUses() {#a401e244b78386047c64edc64f80ba9c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AbstractCallSite::getCallbackUses (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * &gt; &amp; CallbackUses)</td>
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

<p>Add operand uses of <span class="doxyComputerOutput">CB</span> that represent callback uses into <span class="doxyComputerOutput">CallbackUses</span>.</p>


<p>All uses added to <span class="doxyComputerOutput">CallbackUses</span> can be used to create abstract call sites for which <a href="#a2300cb53451591b87c7c5621c31643a2">AbstractCallSite::isCallbackCall()</a> will return true.</p>


<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/abstractcallsite-cpp">AbstractCallSite.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a571612461ea4af620bc4c441d61579a3">llvm::MDNode::operands</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a2fbc912ee1cbb5ddcaea71940aa33685">llvm::forEachCallbackCallSite</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a265735d2c2edc0a1a03611e7aadd24cd">llvm::IRPosition::getAssociatedArgument</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalledgescallsite/#a827970be0131200af76c14c9e1a24b15">anonymous{AttributorAttributes.cpp}::AACallEdgesCallSite::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/abstractcallsite-cpp">AbstractCallSite.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
