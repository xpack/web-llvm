---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-shadowstackgclowering-cpp-/shadowstackgcloweringimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ShadowStackGCLoweringImpl` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{ShadowStackGCLowering.cpp}::ShadowStackGCLoweringImpl { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af321c4bca51c08ac188266282042cb39">ShadowStackGCLoweringImpl</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a285f4b41becdfd4385ddb237bfc744fc">doInitialization</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>doInitialization - If this module uses the GC intrinsics, find them now. <a href="#a285f4b41becdfd4385ddb237bfc744fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b0a9e6fcf89c53f5411701c15ad6045">runOnFunction</a> (Function &amp;F, DomTreeUpdater *DTU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnFunction - Insert code to maintain the shadow stack. <a href="#a0b0a9e6fcf89c53f5411701c15ad6045">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81973bc8dcd77b18160a170f875245e0">IsNullValue</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ed5968fd249092f330ca8d5b0e06a6e">GetFrameMap</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a599a1b8fea5df6e3e8d4e2e5fca3a759">GetConcreteStackEntryType</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad24aacbdd5747a9bdd8abb5614b2cf59">CollectRoots</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b3a41bc092a20fb72e7aaaeb8ee4ef">Head</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RootChain - This is the global linked-list that contains the chain of GC roots. <a href="#a51b3a41bc092a20fb72e7aaaeb8ee4ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d96c7f229b08c9149133d26b67e2a1a">StackEntryTy</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>StackEntryTy - Abstract type of a link in the shadow stack. <a href="#a0d96c7f229b08c9149133d26b67e2a1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae803c7b1f1296a6a81ea98ce08df5fcf">FrameMapTy</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *, <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6bdc853ce361a01432b6a5832dbac30">Roots</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Roots - GC roots in the current function. <a href="#ad6bdc853ce361a01432b6a5832dbac30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f3ca749d974c29055a5db1071ca2416">CreateGEP</a> (LLVMContext &amp;Context, IRBuilder&lt;&gt; &amp;B, Type *Ty, Value *BasePtr, int Idx1, const char *Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25b843d7d6d698a0bb8ee54e81ea9597">CreateGEP</a> (LLVMContext &amp;Context, IRBuilder&lt;&gt; &amp;B, Type *Ty, Value *BasePtr, int Idx1, int Idx2, const char *Name)</td>
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


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/shadowstackgclowering-cpp">ShadowStackGCLowering.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ShadowStackGCLoweringImpl() {#af321c4bca51c08ac188266282042cb39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ShadowStackGCLowering.cpp}::ShadowStackGCLoweringImpl::ShadowStackGCLoweringImpl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/shadowstackgclowering-cpp">ShadowStackGCLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a285f4b41becdfd4385ddb237bfc744fc">doInitialization</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### doInitialization() {#a285f4b41becdfd4385ddb237bfc744fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShadowStackGCLoweringImpl::doInitialization (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>doInitialization - If this module uses the GC intrinsics, find them now.</p>


<p>If not, exit fast.</p>


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/shadowstackgclowering-cpp">ShadowStackGCLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/structtype/#a82648246c07eb8a33f628eea28cb988c">llvm::StructType::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca5ebf288ceb5bbeb7025564727db6d705">llvm::GlobalValue::LinkOnceAnyLinkage</a>.</p>


<p>Referenced by <a href="#af321c4bca51c08ac188266282042cb39">ShadowStackGCLoweringImpl</a>.</p>

</div>
</div>

### runOnFunction() {#a0b0a9e6fcf89c53f5411701c15ad6045}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShadowStackGCLoweringImpl::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> * DTU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>runOnFunction - Insert code to maintain the shadow stack.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/shadowstackgclowering-cpp">ShadowStackGCLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4e5c1b91bf5e2860398e3fa35c96b5af">llvm::IRBuilderBase::GetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab73bb6948312ca0f98055c6a74c37045">llvm::IRBuilderBase::getPtrTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/escapeenumerator/#ac63ecd195310b8a31b445bb613028893">llvm::EscapeEnumerator::Next</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a644036a50a6121fd9e7e6f5ddadb7fc8">llvm::IRBuilderBase::SetInsertPointPastAllocas</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ae855357b6c5e6e7ed1869272708a3a84">llvm::Value::takeName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### CollectRoots() {#ad24aacbdd5747a9bdd8abb5614b2cf59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ShadowStackGCLoweringImpl::CollectRoots (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/shadowstackgclowering-cpp">ShadowStackGCLowering.cpp</a>.</p>

</div>
</div>

### GetConcreteStackEntryType() {#a599a1b8fea5df6e3e8d4e2e5fca3a759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * ShadowStackGCLoweringImpl::GetConcreteStackEntryType (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/shadowstackgclowering-cpp">ShadowStackGCLowering.cpp</a>.</p>

</div>
</div>

### GetFrameMap() {#a0ed5968fd249092f330ca8d5b0e06a6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ShadowStackGCLoweringImpl::GetFrameMap (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/shadowstackgclowering-cpp">ShadowStackGCLowering.cpp</a>.</p>

</div>
</div>

### IsNullValue() {#a81973bc8dcd77b18160a170f875245e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShadowStackGCLoweringImpl::IsNullValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/shadowstackgclowering-cpp">ShadowStackGCLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FrameMapTy {#ae803c7b1f1296a6a81ea98ce08df5fcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType* anonymous{ShadowStackGCLowering.cpp}::ShadowStackGCLoweringImpl::FrameMapTy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/shadowstackgclowering-cpp">ShadowStackGCLowering.cpp</a>.</p>

</div>
</div>

### Head {#a51b3a41bc092a20fb72e7aaaeb8ee4ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable* anonymous{ShadowStackGCLowering.cpp}::ShadowStackGCLoweringImpl::Head = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RootChain - This is the global linked-list that contains the chain of GC roots.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/shadowstackgclowering-cpp">ShadowStackGCLowering.cpp</a>.</p>

</div>
</div>

### Roots {#ad6bdc853ce361a01432b6a5832dbac30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;CallInst *, AllocaInst *&gt; &gt; anonymous{ShadowStackGCLowering.cpp}::ShadowStackGCLoweringImpl::Roots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Roots - GC roots in the current function.</p>


<p>Each is a pair of the intrinsic call and its corresponding alloca.</p>


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/shadowstackgclowering-cpp">ShadowStackGCLowering.cpp</a>.</p>

</div>
</div>

### StackEntryTy {#a0d96c7f229b08c9149133d26b67e2a1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType* anonymous{ShadowStackGCLowering.cpp}::ShadowStackGCLoweringImpl::StackEntryTy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>StackEntryTy - Abstract type of a link in the shadow stack.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/shadowstackgclowering-cpp">ShadowStackGCLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### CreateGEP() {#a7f3ca749d974c29055a5db1071ca2416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GetElementPtrInst * anonymous{ShadowStackGCLowering.cpp}::ShadowStackGCLoweringImpl::CreateGEP (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; B, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * BasePtr, int Idx1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/shadowstackgclowering-cpp">ShadowStackGCLowering.cpp</a>.</p>

</div>
</div>

### CreateGEP() {#a25b843d7d6d698a0bb8ee54e81ea9597}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GetElementPtrInst * anonymous{ShadowStackGCLowering.cpp}::ShadowStackGCLoweringImpl::CreateGEP (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; B, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * BasePtr, int Idx1, int Idx2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/shadowstackgclowering-cpp">ShadowStackGCLowering.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/shadowstackgclowering-cpp">ShadowStackGCLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
