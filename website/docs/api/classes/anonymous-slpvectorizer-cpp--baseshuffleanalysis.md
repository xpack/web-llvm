---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BaseShuffleAnalysis` Class

<p>The base class for shuffle instruction emission and shuffle cost estimation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis { ... }
</div>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fd09f63f0ce151157634df88fb3357f">BaseShuffleAnalysis</a> (Type *ScalarTy)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a330cf3a6980af7480c8de1c2dd643769">getVF</a> (Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>V is expected to be a vectorized value. <a href="#a330cf3a6980af7480c8de1c2dd643769">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38be1769f45f965483df70afee3e7715">ScalarTy</a> = nullptr</td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c6c1a7f00536e9ea11d05420bda55cd">isIdentityMask</a> (ArrayRef&lt; int &gt; Mask, const FixedVectorType *VecTy, bool IsStrict)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the mask is an identity mask. <a href="#a7c6c1a7f00536e9ea11d05420bda55cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8efd31679b2381827db95f3cad5ba44">combineMasks</a> (unsigned LocalVF, SmallVectorImpl&lt; int &gt; &amp;Mask, ArrayRef&lt; int &gt; ExtMask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tries to combine 2 different masks into single one. <a href="#af8efd31679b2381827db95f3cad5ba44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a047b7995a79492824633a62540717492">peekThroughShuffles</a> (Value *&amp;V, SmallVectorImpl&lt; int &gt; &amp;Mask, bool SinglePermute)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks through shuffles trying to reduce final number of shuffles in the code. <a href="#a047b7995a79492824633a62540717492">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename ShuffleBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static T</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8437f11cfb708e9bb288796d123e84dc">createShuffle</a> (Value *V1, Value *V2, ArrayRef&lt; int &gt; Mask, ShuffleBuilderTy &amp;Builder, Type *ScalarTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Smart shuffle instruction emission, walks through shuffles trees and tries to find the best matching vector for the actual shuffle instruction. <a href="#a8437f11cfb708e9bb288796d123e84dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75f6ee141c70a7f17fefb2706f5cf6ac">transformMaskAfterShuffle</a> (MutableArrayRef&lt; int &gt; CommonMask, ArrayRef&lt; int &gt; Mask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transforms mask <span class="doxyComputerOutput">CommonMask</span> per given <span class="doxyComputerOutput">Mask</span> to make proper set after shuffle emission. <a href="#a75f6ee141c70a7f17fefb2706f5cf6ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The base class for shuffle instruction emission and shuffle cost estimation.</p>

<p>Definition at line 9168 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### BaseShuffleAnalysis() {#a7fd09f63f0ce151157634df88fb3357f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::BaseShuffleAnalysis (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ScalarTy)</td>
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



<p>Definition at line 9172 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="#a38be1769f45f965483df70afee3e7715">ScalarTy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getVF() {#a330cf3a6980af7480c8de1c2dd643769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::getVF (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>V is expected to be a vectorized value.</p>


<p>When REVEC is disabled, there is no difference between VF and VNumElements. When REVEC is enabled, VF is VNumElements / ScalarTyNumElements. e.g., if ScalarTy is &lt;4 x Ty&gt; and V1 is &lt;8 x Ty&gt;, 2 is returned instead of 8.</p>


<p>Definition at line 9180 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a2f1d58ac35de4475017aca6c5bda6d44">getNumElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a38be1769f45f965483df70afee3e7715">ScalarTy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ScalarTy {#a38be1769f45f965483df70afee3e7715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::ScalarTy = nullptr</td>
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



<p>Definition at line 9170 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="#a7fd09f63f0ce151157634df88fb3357f">BaseShuffleAnalysis</a>, <a href="#a8437f11cfb708e9bb288796d123e84dc">createShuffle</a> and <a href="#a330cf3a6980af7480c8de1c2dd643769">getVF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### combineMasks() {#af8efd31679b2381827db95f3cad5ba44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::combineMasks (unsigned LocalVF, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; Mask, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; ExtMask)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tries to combine 2 different masks into single one.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">LocalVF</td>
<td class="doxyParamItemDescription"><p>Vector length of the permuted input vector. <span class="doxyComputerOutput">Mask</span> may change the size of the vector, <span class="doxyComputerOutput">LocalVF</span> is the original size of the shuffled vector.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 9226 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#a8437f11cfb708e9bb288796d123e84dc">createShuffle</a> and <a href="#a047b7995a79492824633a62540717492">peekThroughShuffles</a>.</p>

</div>
</div>

### createShuffle() {#a8437f11cfb708e9bb288796d123e84dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename ShuffleBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::createShuffle (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, ShuffleBuilderTy &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ScalarTy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Smart shuffle instruction emission, walks through shuffles trees and tries to find the best matching vector for the actual shuffle instruction.</p>

<p>Definition at line 9388 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a873403a2506ac332f62ad4c2d7dc1835">llvm::all</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a2fd40bb67aec98438b791520159fb146">buildUseMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#af8efd31679b2381827db95f3cad5ba44">combineMasks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a2f1d58ac35de4475017aca6c5bda6d44">getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a81aa4ff7f63f7988abea1abbe9eb0342">llvm::ShuffleVectorInst::isIdentityMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ac396bb87eb4db1dd3ce315e4d91ee2de">isUndefVector</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a0b836340e75383742d06fd0ad2f23ff8">llvm::ShuffleVectorInst::isZeroEltSplatMask</a>, <a href="#a047b7995a79492824633a62540717492">peekThroughShuffles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>, <a href="#a38be1769f45f965483df70afee3e7715">ScalarTy</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-slpvectorizer-cpp-/#a600545eb53de812fc4daae8ecb72199da018f3de8f2e77f6f34af68e83516cb9f">anonymous{SLPVectorizer.cpp}::SecondArg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a8b6f16f98498a168902dd2d5cd8f9462">SLPReVec</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#abd962b7b01f49ce61ea41ee10c49e313">llvm::SmallVectorImpl&lt; T &gt;::swap</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a8af0e2291ce043c892dc0c8d85cc81e1">transformScalarShuffleIndiciesToVector</a>.</p>

</div>
</div>

### isIdentityMask() {#a7c6c1a7f00536e9ea11d05420bda55cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::isIdentityMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> * VecTy, bool IsStrict)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if the mask is an identity mask.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsStrict</td>
<td class="doxyParamItemDescription"><p>if is true the function returns false if mask size does not match vector size.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 9198 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#a1893caf878859959ba6a3d5442ef1439">llvm::FixedVectorType::getNumElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a841e0c83f3c14a1b0979d86a1812f335">llvm::ShuffleVectorInst::isExtractSubvectorMask</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a81aa4ff7f63f7988abea1abbe9eb0342">llvm::ShuffleVectorInst::isIdentityMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>.</p>


<p>Referenced by <a href="#a047b7995a79492824633a62540717492">peekThroughShuffles</a>.</p>

</div>
</div>

### peekThroughShuffles() {#a047b7995a79492824633a62540717492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::peekThroughShuffles (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; V, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; Mask, bool SinglePermute)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Looks through shuffles trying to reduce final number of shuffles in the code.</p>


<p>The function looks through the previously emitted shuffle instructions and properly mark indices in mask as undef. For example, given the code</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%s1 = shufflevector &lt;2 x ty&gt; %0, poison, &lt;1, 0&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%s2 = shufflevector &lt;2 x ty&gt; %1, poison, &lt;1, 0&gt;</span></span></div>

</div>


<p>and if need to emit shuffle of s1 and s2 with mask &lt;1, 0, 3, 2&gt;, it will look through s1 and s2 and select vectors %0 and %1 with mask &lt;0, 1, 2, 3&gt; for the shuffle. If 2 operands are of different size, the smallest one will be resized and the mask recalculated properly. For example, given the code</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%s1 = shufflevector &lt;2 x ty&gt; %0, poison, &lt;1, 0, 1, 0&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%s2 = shufflevector &lt;2 x ty&gt; %1, poison, &lt;1, 0, 1, 0&gt;</span></span></div>

</div>


<p>and if need to emit shuffle of s1 and s2 with mask &lt;1, 0, 5, 4&gt;, it will look through s1 and s2 and select vectors %0 and %1 with mask &lt;0, 1, 2, 3&gt; for the shuffle. So, it tries to transform permutations to simple vector merge, if possible.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">V</td>
<td class="doxyParamItemDescription"><p>The input vector which must be shuffled using the given <span class="doxyComputerOutput">Mask</span>. If the better candidate is found, <span class="doxyComputerOutput">V</span> is set to this best candidate vector.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mask</td>
<td class="doxyParamItemDescription"><p>The input mask for the shuffle. If the best candidate is found during looking-through-shuffles attempt, it is updated accordingly.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SinglePermute</td>
<td class="doxyParamItemDescription"><p>true if the shuffle operation is originally a single-value-permutation. In this case the look-through-shuffles procedure may look for resizing shuffles as the best candidates.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the shuffle results in the non-resizing identity shuffle (and thus can be ignored), false - otherwise.</p></dd>
</dl>


<p>Definition at line 9273 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a38c50aa8e3e9588f4f968c2e03a0cee0">llvm::SmallVectorImpl&lt; T &gt;::assign</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a2fd40bb67aec98438b791520159fb146">buildUseMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#af8efd31679b2381827db95f3cad5ba44">combineMasks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-slpvectorizer-cpp-/#a600545eb53de812fc4daae8ecb72199da8545ba2c4d270d3cca72fb93da2a21d8">anonymous{SLPVectorizer.cpp}::FirstArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a7c6c1a7f00536e9ea11d05420bda55cd">isIdentityMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ac396bb87eb4db1dd3ce315e4d91ee2de">isUndefVector</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a0b836340e75383742d06fd0ad2f23ff8">llvm::ShuffleVectorInst::isZeroEltSplatMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-slpvectorizer-cpp-/#a600545eb53de812fc4daae8ecb72199da018f3de8f2e77f6f34af68e83516cb9f">anonymous{SLPVectorizer.cpp}::SecondArg</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a8437f11cfb708e9bb288796d123e84dc">createShuffle</a>.</p>

</div>
</div>

### transformMaskAfterShuffle() {#a75f6ee141c70a7f17fefb2706f5cf6ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::transformMaskAfterShuffle (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; int &gt; CommonMask, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transforms mask <span class="doxyComputerOutput">CommonMask</span> per given <span class="doxyComputerOutput">Mask</span> to make proper set after shuffle emission.</p>

<p>Definition at line 9510 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
