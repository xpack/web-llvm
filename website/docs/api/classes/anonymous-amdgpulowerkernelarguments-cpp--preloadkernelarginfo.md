---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-amdgpulowerkernelarguments-cpp-/preloadkernelarginfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PreloadKernelArgInfo` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">HiddenArg : unsigned { <a href="#a94f59631778aa6d2557cd927796c03d2">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68eecf773546d45222123c448c9cba3d">PreloadKernelArgInfo</a> (Function &amp;F, const GCNSubtarget &amp;ST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49308385cf90a25d63f1879307c7daa8">setInitialFreeUserSGPRsCount</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a8c2bbde71660b23e66788618bf10e0">tryAllocPreloadSGPRs</a> (unsigned AllocSize, uint64_t ArgOffset, uint64_t LastExplicitArgOffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a5253091344c2d534f5afd16941e25d">tryAllocImplicitArgPreloadSGPRs</a> (uint64_t ImplicitArgsBaseOffset, uint64_t LastExplicitArgOffset, IRBuilder&lt;&gt; &amp;Builder)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a151c8e3dfa6553896a65c10297b0598a">cloneFunctionWithPreloadImplicitArgs</a> (unsigned LastPreloadIndex)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7a5ea424d0b94825907e83a7b3197af">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a793796a70cea7d1b25fad1656c6eef4c">ST</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad726d8f686997c2683192fc6e1a2a282">NumFreeUserSGPRs</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static HiddenArg</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82621f660f6ce5d90f936e054fcbffc6">getHiddenArgFromOffset</a> (unsigned Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4f9ff4bbdb764795127b417b9379214">getHiddenArgType</a> (LLVMContext &amp;Ctx, HiddenArg HA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a743ddf25a7e5cc0f4836e5e84dd79903">getHiddenArgName</a> (HiddenArg HA)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr HiddenArgInfo</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62497c8bb0a24733a9f2469bd9e809bd">HiddenArgs</a>[END_HIDDEN_ARGS] = ...</td>
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


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp">AMDGPULowerKernelArguments.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### HiddenArg {#a94f59631778aa6d2557cd927796c03d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::HiddenArg : unsigned</td>
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
<td class="doxyEnumItemName">HIDDEN_BLOCK_COUNT_X<a id="a94f59631778aa6d2557cd927796c03d2a6635ff27eab2d231e94adf37ecbe7495"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HIDDEN_BLOCK_COUNT_Y<a id="a94f59631778aa6d2557cd927796c03d2a3759d03e3117abe1862e8683a041550c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HIDDEN_BLOCK_COUNT_Z<a id="a94f59631778aa6d2557cd927796c03d2a1dda076b557cfece9bd65e7f9a51ebc7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HIDDEN_GROUP_SIZE_X<a id="a94f59631778aa6d2557cd927796c03d2a1c2727d5be07a6883acccf5c24ab3880"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HIDDEN_GROUP_SIZE_Y<a id="a94f59631778aa6d2557cd927796c03d2afeee91e1dd475383ea24defc04c639e5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HIDDEN_GROUP_SIZE_Z<a id="a94f59631778aa6d2557cd927796c03d2a6a84a3ad3fa5bd011d79229f977511f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HIDDEN_REMAINDER_X<a id="a94f59631778aa6d2557cd927796c03d2a83f3e9e1d3ddfa6445d233b674808f85"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HIDDEN_REMAINDER_Y<a id="a94f59631778aa6d2557cd927796c03d2ad1c2003d0529ea284d57592a05dfc0da"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HIDDEN_REMAINDER_Z<a id="a94f59631778aa6d2557cd927796c03d2af6cb9e461b9a1de368ae1c316faed50c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">END_HIDDEN_ARGS<a id="a94f59631778aa6d2557cd927796c03d2a946883ea271ec0acc9dc850c96e6c680"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp">AMDGPULowerKernelArguments.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PreloadKernelArgInfo() {#a68eecf773546d45222123c448c9cba3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::PreloadKernelArgInfo (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST)</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp">AMDGPULowerKernelArguments.cpp</a>.</p>


<p>Reference <a href="#a49308385cf90a25d63f1879307c7daa8">setInitialFreeUserSGPRsCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a804c9545f28631dc405eccad6d7234a7">lowerKernelArguments</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### setInitialFreeUserSGPRsCount() {#a49308385cf90a25d63f1879307c7daa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::setInitialFreeUserSGPRsCount ()</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp">AMDGPULowerKernelArguments.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/gcnusersgprusageinfo/#a8cb6ff5b4d97ee4b7d8a03c3cd11d644">llvm::GCNUserSGPRUsageInfo::getNumFreeUserSGPRs</a>.</p>


<p>Referenced by <a href="#a68eecf773546d45222123c448c9cba3d">PreloadKernelArgInfo</a>.</p>

</div>
</div>

### tryAllocImplicitArgPreloadSGPRs() {#a7a5253091344c2d534f5afd16941e25d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::tryAllocImplicitArgPreloadSGPRs (uint64_t ImplicitArgsBaseOffset, uint64_t LastExplicitArgOffset, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder)</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp">AMDGPULowerKernelArguments.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#ac6baa801e4aea800984e760d5460662f">llvm::Function::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aecf2b6d6f052a378dd8f69fd1bb700b1">llvm::Function::getArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aa1731508126b77035ab3ba9d71d5374b">llvm::Intrinsic::getDeclarationIfExists</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3ac5d9eb48038aa973017317279eadf5">llvm::GetPointerBaseWithConstantOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>

</div>
</div>

### tryAllocPreloadSGPRs() {#a5a8c2bbde71660b23e66788618bf10e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::tryAllocPreloadSGPRs (unsigned AllocSize, uint64_t ArgOffset, uint64_t LastExplicitArgOffset)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp">AMDGPULowerKernelArguments.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a41896492f62ee8d25cf8aaad70bd88aa">llvm::alignDown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a25f1d7ccf87af8d87fcb950f7ed758b5">llvm::isAligned</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### cloneFunctionWithPreloadImplicitArgs() {#a151c8e3dfa6553896a65c10297b0598a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::cloneFunctionWithPreloadImplicitArgs (unsigned LastPreloadIndex)</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp">AMDGPULowerKernelArguments.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### F {#ac7a5ea424d0b94825907e83a7b3197af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp">AMDGPULowerKernelArguments.cpp</a>.</p>

</div>
</div>

### NumFreeUserSGPRs {#ad726d8f686997c2683192fc6e1a2a282}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::NumFreeUserSGPRs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp">AMDGPULowerKernelArguments.cpp</a>.</p>

</div>
</div>

### ST {#a793796a70cea7d1b25fad1656c6eef4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget&amp; anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp">AMDGPULowerKernelArguments.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getHiddenArgFromOffset() {#a82621f660f6ce5d90f936e054fcbffc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HiddenArg anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::getHiddenArgFromOffset (unsigned Offset)</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp">AMDGPULowerKernelArguments.cpp</a>.</p>

</div>
</div>

### getHiddenArgName() {#a743ddf25a7e5cc0f4836e5e84dd79903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::getHiddenArgName (HiddenArg HA)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp">AMDGPULowerKernelArguments.cpp</a>.</p>

</div>
</div>

### getHiddenArgType() {#af4f9ff4bbdb764795127b417b9379214}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::getHiddenArgType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, HiddenArg HA)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp">AMDGPULowerKernelArguments.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### HiddenArgs {#a62497c8bb0a24733a9f2469bd9e809bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HiddenArgInfo anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::HiddenArgs[END_HIDDEN_ARGS]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
      {0, 4, "_hidden_block_count_x"}, {4, 4, "_hidden_block_count_y"},
      {8, 4, "_hidden_block_count_z"}, {12, 2, "_hidden_group_size_x"},
      {14, 2, "_hidden_group_size_y"}, {16, 2, "_hidden_group_size_z"},
      {18, 2, "_hidden_remainder_x"},  {20, 2, "_hidden_remainder_y"},
      {22, 2, "_hidden_remainder_z"}}
</div>
</dd>
</dl>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp">AMDGPULowerKernelArguments.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp">AMDGPULowerKernelArguments.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
