---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/coro/shape
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Shape` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::coro::Shape { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">llvm/Transforms/Coroutines/CoroShape.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36882e56b196a358b82accb17fbaf3ee">Shape</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5173556f061b7bc78184139283d1ef3b">Shape</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4ca8a1156a9b26ecee8c95d328d5739">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe664f8e39ffc3ae37c49342e39d7423">analyze</a> (Function &amp;F, SmallVectorImpl&lt; CoroFrameInst * &gt; &amp;CoroFrames, SmallVectorImpl&lt; CoroSaveInst * &gt; &amp;UnusedCoroSaves)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae365293b0e4b5cb45b3af280d14b26f1">invalidateCoroutine</a> (Function &amp;F, SmallVectorImpl&lt; CoroFrameInst * &gt; &amp;CoroFrames)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9da150551f59d19a75ade67b39cb1d8">initABI</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a917fb3f24e47a8df6464b9d288310332">cleanCoroutine</a> (SmallVectorImpl&lt; CoroFrameInst * &gt; &amp;CoroFrames, SmallVectorImpl&lt; CoroSaveInst * &gt; &amp;UnusedCoroSaves)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/coroidinst">CoroIdInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3660324b8035c8b52afd23e54623ddf8">getSwitchCoroId</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/anycoroidretconinst">AnyCoroIdRetconInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2acb69a078f9bb3184aa59c6d4966861">getRetconCoroId</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/coroidasyncinst">CoroIdAsyncInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7ceee8402cf34043300744bd266d69b">getAsyncCoroId</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedc5db661c24859142b1b7a67dc05ba7">getSwitchIndexField</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22c53726eaeafbc188994ecbc7e27674">getIndexType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e8a88398e176735a277b77269570c50">getIndex</a> (uint64_t Value) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e44b079291a98a6f381ddc2f4e613d0">getSwitchResumePointerType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a578073d9d2487a3806e8a51abb1b6e">getResumeFunctionType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac91071b50ec814bdcb75af662c3b8b28">getRetconResultTypes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5831a89147ca4aaf1b08877d21ca931b">getRetconResumeTypes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e2e134e22f7bd3f6270ef63546e9994">getResumeFunctionCC</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab0e2582dd592f549f16c9a26b9d5f42">getPromiseAlloca</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac406c2b5a7e2d11174becab5cb27765d">getInsertPtAfterFramePtr</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78fa8f84df72aa178f82c9421b0cf387">emitAlloc</a> (IRBuilder&lt;&gt; &amp;Builder, Value *Size, CallGraph *CG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate memory according to the rules of the active lowering. <a href="#a78fa8f84df72aa178f82c9421b0cf387">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acad2aaa7f484c978bb790533eec90ac4">emitDealloc</a> (IRBuilder&lt;&gt; &amp;Builder, Value *Ptr, CallGraph *CG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocate memory according to the rules of the active lowering. <a href="#acad2aaa7f484c978bb790533eec90ac4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/corobegininst">CoroBeginInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfb56acef5d60fefb2edc417f0bfbda0">CoroBegin</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/anycoroendinst">AnyCoroEndInst</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc470e92d3cd5fb8d54d7b9179841463">CoroEnds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/corosizeinst">CoroSizeInst</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48b7ab2f26b9e2bc67de02229a1cdd1f">CoroSizes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/coroaligninst">CoroAlignInst</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad49b292032d2eebe5e027ab2d4445e6d">CoroAligns</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/anycorosuspendinst">AnyCoroSuspendInst</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fd0aa934908c837c6d78097a2fd667b">CoroSuspends</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/coroawaitsuspendinst">CoroAwaitSuspendInst</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b14d3f96facecc355aaac306b6279ae">CoroAwaitSuspends</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06f9098a6725a57dcb2b25cdc9fd3398">SymmetricTransfers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae290085a52a8df4810b4e7f48dbe1ac5">SwiftErrorOps</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380">coro::ABI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e554c60419835fc3c74b91b28ca31c8">ABI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24c5fed9b14aed8a3b4f3828472fbab5">FrameTy</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a1a8e48ba1e5d845e979d5da8de597d">FrameAlign</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a742806b2e667a87817ae171e1ec59826">FrameSize</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eac2988672b484645dcbcd706430967">FramePtr</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3a9a76ce45cff6c0385091993bccdcc">AllocaSpillBlock</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coro/shape/switchloweringstorage">SwitchLoweringStorage</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe8f7906a8618f90e2a75109a778054a">SwitchLowering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coro/shape/retconloweringstorage">RetconLoweringStorage</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace1508259ecd37ceaafb9162d3768fff">RetconLowering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coro/shape/asyncloweringstorage">AsyncLoweringStorage</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cca043bc17f6f673acb6324db527dae">AsyncLowering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/structs/llvm/coro/shape">llvm::coro::Shape</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab313582250cc09f94152fadf051e70d3"></a></td>
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


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Shape() {#a36882e56b196a358b82accb17fbaf3ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coro::Shape::Shape ()</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a8bf580168c7138b15f7bfdd080416bec">doSplitCoroutine</a>.</p>

</div>
</div>

### Shape() {#a5173556f061b7bc78184139283d1ef3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coro::Shape::Shape (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>References <a href="#afe664f8e39ffc3ae37c49342e39d7423">analyze</a>, <a href="#a917fb3f24e47a8df6464b9d288310332">cleanCoroutine</a>, <a href="#abfb56acef5d60fefb2edc417f0bfbda0">CoroBegin</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#ae365293b0e4b5cb45b3af280d14b26f1">invalidateCoroutine</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### analyze() {#afe664f8e39ffc3ae37c49342e39d7423}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void coro::Shape::analyze (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/coroframeinst">CoroFrameInst</a> * &gt; &amp; CoroFrames, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/corosaveinst">CoroSaveInst</a> * &gt; &amp; UnusedCoroSaves)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>, definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp">Coroutines.cpp</a>.</p>


<p>References <a href="#a4e554c60419835fc3c74b91b28ca31c8">ABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="#a0cca043bc17f6f673acb6324db527dae">AsyncLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ab4ca8a1156a9b26ecee8c95d328d5739">clear</a>, <a href="#ad49b292032d2eebe5e027ab2d4445e6d">CoroAligns</a>, <a href="#a0b14d3f96facecc355aaac306b6279ae">CoroAwaitSuspends</a>, <a href="#abfb56acef5d60fefb2edc417f0bfbda0">CoroBegin</a>, <a href="#adc470e92d3cd5fb8d54d7b9179841463">CoroEnds</a>, <a href="#a48b7ab2f26b9e2bc67de02229a1cdd1f">CoroSizes</a>, <a href="#a5fd0aa934908c837c6d78097a2fd667b">CoroSuspends</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ad7ceee8402cf34043300744bd266d69b">getAsyncCoroId</a>, <a href="#a2acb69a078f9bb3184aa59c6d4966861">getRetconCoroId</a>, <a href="#a3660324b8035c8b52afd23e54623ddf8">getSwitchCoroId</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a>, <a href="#ace1508259ecd37ceaafb9162d3768fff">RetconLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a> and <a href="#abe8f7906a8618f90e2a75109a778054a">SwitchLowering</a>.</p>


<p>Referenced by <a href="#a5173556f061b7bc78184139283d1ef3b">Shape</a>.</p>

</div>
</div>

### cleanCoroutine() {#a917fb3f24e47a8df6464b9d288310332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void coro::Shape::cleanCoroutine (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/coroframeinst">CoroFrameInst</a> * &gt; &amp; CoroFrames, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/corosaveinst">CoroSaveInst</a> * &gt; &amp; UnusedCoroSaves)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>, definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp">Coroutines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a> and <a href="#abfb56acef5d60fefb2edc417f0bfbda0">CoroBegin</a>.</p>


<p>Referenced by <a href="#a5173556f061b7bc78184139283d1ef3b">Shape</a>.</p>

</div>
</div>

### clear() {#ab4ca8a1156a9b26ecee8c95d328d5739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::coro::Shape::clear ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>References <a href="#ae3a9a76ce45cff6c0385091993bccdcc">AllocaSpillBlock</a>, <a href="#ad49b292032d2eebe5e027ab2d4445e6d">CoroAligns</a>, <a href="#a0b14d3f96facecc355aaac306b6279ae">CoroAwaitSuspends</a>, <a href="#abfb56acef5d60fefb2edc417f0bfbda0">CoroBegin</a>, <a href="#adc470e92d3cd5fb8d54d7b9179841463">CoroEnds</a>, <a href="#a48b7ab2f26b9e2bc67de02229a1cdd1f">CoroSizes</a>, <a href="#a5fd0aa934908c837c6d78097a2fd667b">CoroSuspends</a>, <a href="#a5eac2988672b484645dcbcd706430967">FramePtr</a>, <a href="#a24c5fed9b14aed8a3b4f3828472fbab5">FrameTy</a>, <a href="#ae290085a52a8df4810b4e7f48dbe1ac5">SwiftErrorOps</a> and <a href="#a06f9098a6725a57dcb2b25cdc9fd3398">SymmetricTransfers</a>.</p>


<p>Referenced by <a href="#afe664f8e39ffc3ae37c49342e39d7423">analyze</a>.</p>

</div>
</div>

### emitAlloc() {#a78fa8f84df72aa178f82c9421b0cf387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * coro::Shape::emitAlloc (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Size, <a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a> * CG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate memory according to the rules of the active lowering.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CG</td>
<td class="doxyParamItemDescription"><p>- if non-null, will be updated for the new call</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>, definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp">Coroutines.cpp</a>.</p>


<p>References <a href="#a4e554c60419835fc3c74b91b28ca31c8">ABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp/#ae67da287e739d52afd1dad7fd1dd577f">addCallToCallGraph</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1aea571dc00aef155a16d4e7e1861e1682">llvm::Alloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac79ca3c2d2d74cf33684397a91846564">llvm::IRBuilderBase::CreateIntCast</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp/#a4541bd6496be4d9b8be992774e81c71e">propagateCallAttrsFromCallee</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a>, <a href="#ace1508259ecd37ceaafb9162d3768fff">RetconLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/coro/anonymous-spillutils-cpp-/#a36764d140de2314a0f15b203f0556112">llvm::coro::anonymous{SpillUtils.cpp}::lowerNonLocalAlloca</a>.</p>

</div>
</div>

### emitDealloc() {#acad2aaa7f484c978bb790533eec90ac4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void coro::Shape::emitDealloc (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a> * CG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deallocate memory according to the rules of the active lowering.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CG</td>
<td class="doxyParamItemDescription"><p>- if non-null, will be updated for the new call</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>, definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp">Coroutines.cpp</a>.</p>


<p>References <a href="#a4e554c60419835fc3c74b91b28ca31c8">ABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp/#ae67da287e739d52afd1dad7fd1dd577f">addCallToCallGraph</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp/#a4541bd6496be4d9b8be992774e81c71e">propagateCallAttrsFromCallee</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a>, <a href="#ace1508259ecd37ceaafb9162d3768fff">RetconLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/coro/anonymous-spillutils-cpp-/#a36764d140de2314a0f15b203f0556112">llvm::coro::anonymous{SpillUtils.cpp}::lowerNonLocalAlloca</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a3907189466613e437b0ea2731bf9b159">maybeFreeRetconStorage</a>.</p>

</div>
</div>

### getAsyncCoroId() {#ad7ceee8402cf34043300744bd266d69b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CoroIdAsyncInst * llvm::coro::Shape::getAsyncCoroId ()</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>References <a href="#a4e554c60419835fc3c74b91b28ca31c8">ABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#abfb56acef5d60fefb2edc417f0bfbda0">CoroBegin</a>.</p>


<p>Referenced by <a href="#afe664f8e39ffc3ae37c49342e39d7423">analyze</a>.</p>

</div>
</div>

### getIndex() {#a9e8a88398e176735a277b77269570c50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantInt * llvm::coro::Shape::getIndex (uint64_t Value)</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Reference <a href="#a22c53726eaeafbc188994ecbc7e27674">getIndexType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#aa6734dd82cf736e89074802287b0abfe">markCoroutineAsDone</a>.</p>

</div>
</div>

### getIndexType() {#a22c53726eaeafbc188994ecbc7e27674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType * llvm::coro::Shape::getIndexType ()</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>References <a href="#a4e554c60419835fc3c74b91b28ca31c8">ABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a24c5fed9b14aed8a3b4f3828472fbab5">FrameTy</a>, <a href="#aedc5db661c24859142b1b7a67dc05ba7">getSwitchIndexField</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a>.</p>


<p>Referenced by <a href="#a9e8a88398e176735a277b77269570c50">getIndex</a>.</p>

</div>
</div>

### getInsertPtAfterFramePtr() {#ac406c2b5a7e2d11174becab5cb27765d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::iterator llvm::coro::Shape::getInsertPtAfterFramePtr ()</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5eac2988672b484645dcbcd706430967">FramePtr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a58bcd428c0ca38b723b8ef938868ec4a">llvm::coro::getSpillInsertionPt</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>.</p>

</div>
</div>

### getPromiseAlloca() {#aab0e2582dd592f549f16c9a26b9d5f42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst * llvm::coro::Shape::getPromiseAlloca ()</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>References <a href="#a4e554c60419835fc3c74b91b28ca31c8">ABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a> and <a href="#abe8f7906a8618f90e2a75109a778054a">SwitchLowering</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a712c7e27f92253c99bcc20689a4e93b0">buildFrameType</a>.</p>

</div>
</div>

### getResumeFunctionCC() {#a4e2e134e22f7bd3f6270ef63546e9994}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallingConv::ID llvm::coro::Shape::getResumeFunctionCC ()</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>References <a href="#a4e554c60419835fc3c74b91b28ca31c8">ABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="#a0cca043bc17f6f673acb6324db527dae">AsyncLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a>, <a href="#ace1508259ecd37ceaafb9162d3768fff">RetconLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a>.</p>

</div>
</div>

### getResumeFunctionType() {#a1a578073d9d2487a3806e8a51abb1b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType * llvm::coro::Shape::getResumeFunctionType ()</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>References <a href="#a4e554c60419835fc3c74b91b28ca31c8">ABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="#a24c5fed9b14aed8a3b4f3828472fbab5">FrameTy</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a>, <a href="#ace1508259ecd37ceaafb9162d3768fff">RetconLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a452dcc29fd5e19bda874218e10a8945c">createCloneDeclaration</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a84fbc09723655416fad6677d7fdaf8a6">replaceFallthroughCoroEnd</a>.</p>

</div>
</div>

### getRetconCoroId() {#a2acb69a078f9bb3184aa59c6d4966861}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnyCoroIdRetconInst * llvm::coro::Shape::getRetconCoroId ()</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>References <a href="#a4e554c60419835fc3c74b91b28ca31c8">ABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#abfb56acef5d60fefb2edc417f0bfbda0">CoroBegin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a>.</p>


<p>Referenced by <a href="#afe664f8e39ffc3ae37c49342e39d7423">analyze</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a712c7e27f92253c99bcc20689a4e93b0">buildFrameType</a>.</p>

</div>
</div>

### getRetconResultTypes() {#ac91071b50ec814bdcb75af662c3b8b28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Type * &gt; llvm::coro::Shape::getRetconResultTypes ()</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>References <a href="#a4e554c60419835fc3c74b91b28ca31c8">ABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abfb56acef5d60fefb2edc417f0bfbda0">CoroBegin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a>.</p>

</div>
</div>

### getRetconResumeTypes() {#a5831a89147ca4aaf1b08877d21ca931b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Type * &gt; llvm::coro::Shape::getRetconResumeTypes ()</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>References <a href="#a4e554c60419835fc3c74b91b28ca31c8">ABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a>, <a href="#ace1508259ecd37ceaafb9162d3768fff">RetconLowering</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a>.</p>

</div>
</div>

### getSwitchCoroId() {#a3660324b8035c8b52afd23e54623ddf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CoroIdInst * llvm::coro::Shape::getSwitchCoroId ()</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>References <a href="#a4e554c60419835fc3c74b91b28ca31c8">ABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#abfb56acef5d60fefb2edc417f0bfbda0">CoroBegin</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a>.</p>


<p>Referenced by <a href="#afe664f8e39ffc3ae37c49342e39d7423">analyze</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab7881567f602c3a94d11e2817f4464e0">handleNoSuspendCoroutine</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a8bd87bda26e6aac77644f79dbd06c340">llvm::coro::normalizeCoroutine</a>.</p>

</div>
</div>

### getSwitchIndexField() {#aedc5db661c24859142b1b7a67dc05ba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::coro::Shape::getSwitchIndexField ()</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>References <a href="#a4e554c60419835fc3c74b91b28ca31c8">ABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a24c5fed9b14aed8a3b4f3828472fbab5">FrameTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a> and <a href="#abe8f7906a8618f90e2a75109a778054a">SwitchLowering</a>.</p>


<p>Referenced by <a href="#a22c53726eaeafbc188994ecbc7e27674">getIndexType</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#aa6734dd82cf736e89074802287b0abfe">markCoroutineAsDone</a>.</p>

</div>
</div>

### getSwitchResumePointerType() {#a2e44b079291a98a6f381ddc2f4e613d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType * llvm::coro::Shape::getSwitchResumePointerType ()</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>References <a href="#a4e554c60419835fc3c74b91b28ca31c8">ABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a24c5fed9b14aed8a3b4f3828472fbab5">FrameTy</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/switchfieldindex/#aef925686aca6c6970964fea2c25bf242a012dd1dc85c718e8159980fa4273d9e6">llvm::coro::Shape::SwitchFieldIndex::Resume</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a>.</p>

</div>
</div>

### initABI() {#ae9da150551f59d19a75ade67b39cb1d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::coro::Shape::initABI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>

</div>
</div>

### invalidateCoroutine() {#ae365293b0e4b5cb45b3af280d14b26f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void coro::Shape::invalidateCoroutine (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/coroframeinst">CoroFrameInst</a> * &gt; &amp; CoroFrames)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>, definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp">Coroutines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a97370114df349e0996f133e3402c1595">llvm::changeToUnreachable</a>, <a href="#abfb56acef5d60fefb2edc417f0bfbda0">CoroBegin</a>, <a href="#adc470e92d3cd5fb8d54d7b9179841463">CoroEnds</a>, <a href="#a5fd0aa934908c837c6d78097a2fd667b">CoroSuspends</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp/#a434449d5a0f4b334aca9163b13b6286ba02b848adda8d7d33a2b25d87dbef1d75">Poison</a>.</p>


<p>Referenced by <a href="#a5173556f061b7bc78184139283d1ef3b">Shape</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

###  {#ab313582250cc09f94152fadf051e70d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::coro::Shape llvm::coro::Shape</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>

</div>
</div>

### ABI {#a4e554c60419835fc3c74b91b28ca31c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">coro::ABI llvm::coro::Shape::ABI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Referenced by <a href="#afe664f8e39ffc3ae37c49342e39d7423">analyze</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a712c7e27f92253c99bcc20689a4e93b0">buildFrameType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/anonymous-spillutils-cpp-/#a452155536772ef01d3c028f7284ecd2b">llvm::coro::anonymous{SpillUtils.cpp}::collectFrameAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a452dcc29fd5e19bda874218e10a8945c">createCloneDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a88fd8d22fd3856c5ed785a7d9f2a736e">CreateNewABI</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af0793991541abccfec5c0d8831612b7b">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::createNoAllocVariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a8bf580168c7138b15f7bfdd080416bec">doSplitCoroutine</a>, <a href="#a78fa8f84df72aa178f82c9421b0cf387">emitAlloc</a>, <a href="#acad2aaa7f484c978bb790533eec90ac4">emitDealloc</a>, <a href="#ad7ceee8402cf34043300744bd266d69b">getAsyncCoroId</a>, <a href="#a22c53726eaeafbc188994ecbc7e27674">getIndexType</a>, <a href="#aab0e2582dd592f549f16c9a26b9d5f42">getPromiseAlloca</a>, <a href="#a4e2e134e22f7bd3f6270ef63546e9994">getResumeFunctionCC</a>, <a href="#a1a578073d9d2487a3806e8a51abb1b6e">getResumeFunctionType</a>, <a href="#a2acb69a078f9bb3184aa59c6d4966861">getRetconCoroId</a>, <a href="#ac91071b50ec814bdcb75af662c3b8b28">getRetconResultTypes</a>, <a href="#a5831a89147ca4aaf1b08877d21ca931b">getRetconResumeTypes</a>, <a href="#a3660324b8035c8b52afd23e54623ddf8">getSwitchCoroId</a>, <a href="#aedc5db661c24859142b1b7a67dc05ba7">getSwitchIndexField</a>, <a href="#a2e44b079291a98a6f381ddc2f4e613d0">getSwitchResumePointerType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab7881567f602c3a94d11e2817f4464e0">handleNoSuspendCoroutine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#aa6734dd82cf736e89074802287b0abfe">markCoroutineAsDone</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a3907189466613e437b0ea2731bf9b159">maybeFreeRetconStorage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a8bd87bda26e6aac77644f79dbd06c340">llvm::coro::normalizeCoroutine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#aa2ead3ae2cc059f459be46ce71ef20a5">removeCoroEndsFromRampFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a84fbc09723655416fad6677d7fdaf8a6">replaceFallthroughCoroEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a8543371395854bee27033b8e24836cb0">replaceFrameSizeAndAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a236935b2df66a03a0a54350a6b9b84bc">replaceSwiftErrorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a9cb75e325aabbbb2e1fdf034b2f11491">replaceUnwindCoroEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a76d02f8354cb0d3c8b30eb7812ae01b2">simplifySuspendPoints</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af34178528cc721dfa273965733da1f37">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::split</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab02a4d4ecc962ea09ed6c79ebc699a54">updateAsyncFuncPointerContextSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a1d6bceebc19a80123ae26670c7645d1a">updateCallGraphAfterCoroutineSplit</a>.</p>

</div>
</div>

### AllocaSpillBlock {#ae3a9a76ce45cff6c0385091993bccdcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* llvm::coro::Shape::AllocaSpillBlock = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Referenced by <a href="#ab4ca8a1156a9b26ecee8c95d328d5739">clear</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>.</p>

</div>
</div>

### AsyncLowering {#a0cca043bc17f6f673acb6324db527dae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsyncLoweringStorage llvm::coro::Shape::AsyncLowering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Referenced by <a href="#afe664f8e39ffc3ae37c49342e39d7423">analyze</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a712c7e27f92253c99bcc20689a4e93b0">buildFrameType</a>, <a href="#a4e2e134e22f7bd3f6270ef63546e9994">getResumeFunctionCC</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab02a4d4ecc962ea09ed6c79ebc699a54">updateAsyncFuncPointerContextSize</a>.</p>

</div>
</div>

### CoroAligns {#ad49b292032d2eebe5e027ab2d4445e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;CoroAlignInst *, 2&gt; llvm::coro::Shape::CoroAligns</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Referenced by <a href="#afe664f8e39ffc3ae37c49342e39d7423">analyze</a>, <a href="#ab4ca8a1156a9b26ecee8c95d328d5739">clear</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a8543371395854bee27033b8e24836cb0">replaceFrameSizeAndAlignment</a>.</p>

</div>
</div>

### CoroAwaitSuspends {#a0b14d3f96facecc355aaac306b6279ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;CoroAwaitSuspendInst *, 4&gt; llvm::coro::Shape::CoroAwaitSuspends</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Referenced by <a href="#afe664f8e39ffc3ae37c49342e39d7423">analyze</a>, <a href="#ab4ca8a1156a9b26ecee8c95d328d5739">clear</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab68c3421a2e14ba10398bfcd82d6161e">lowerAwaitSuspends</a>.</p>

</div>
</div>

### CoroBegin {#abfb56acef5d60fefb2edc417f0bfbda0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CoroBeginInst* llvm::coro::Shape::CoroBegin = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Referenced by <a href="#afe664f8e39ffc3ae37c49342e39d7423">analyze</a>, <a href="#a917fb3f24e47a8df6464b9d288310332">cleanCoroutine</a>, <a href="#ab4ca8a1156a9b26ecee8c95d328d5739">clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#afee39cae7ff99ef86d9f4ed0ee4282f0">llvm::coro::collectSpillsAndAllocasFromInsts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a88fd8d22fd3856c5ed785a7d9f2a736e">CreateNewABI</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af0793991541abccfec5c0d8831612b7b">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::createNoAllocVariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a8bf580168c7138b15f7bfdd080416bec">doSplitCoroutine</a>, <a href="#ad7ceee8402cf34043300744bd266d69b">getAsyncCoroId</a>, <a href="#a2acb69a078f9bb3184aa59c6d4966861">getRetconCoroId</a>, <a href="#ac91071b50ec814bdcb75af662c3b8b28">getRetconResultTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a58bcd428c0ca38b723b8ef938868ec4a">llvm::coro::getSpillInsertionPt</a>, <a href="#a3660324b8035c8b52afd23e54623ddf8">getSwitchCoroId</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab7881567f602c3a94d11e2817f4464e0">handleNoSuspendCoroutine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="#ae365293b0e4b5cb45b3af280d14b26f1">invalidateCoroutine</a>, <a href="/web-llvm/docs/api/structs/llvm/corosplitpass/#a47f6589634ad33a13369ace133b9f4b2">llvm::CoroSplitPass::run</a>, <a href="#a5173556f061b7bc78184139283d1ef3b">Shape</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a76d02f8354cb0d3c8b30eb7812ae01b2">simplifySuspendPoints</a>.</p>

</div>
</div>

### CoroEnds {#adc470e92d3cd5fb8d54d7b9179841463}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AnyCoroEndInst *, 4&gt; llvm::coro::Shape::CoroEnds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Referenced by <a href="#afe664f8e39ffc3ae37c49342e39d7423">analyze</a>, <a href="#ab4ca8a1156a9b26ecee8c95d328d5739">clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a8356860a8bef082ff15df896ecec7732">eliminateSwiftErrorArgument</a>, <a href="#ae365293b0e4b5cb45b3af280d14b26f1">invalidateCoroutine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a8bd87bda26e6aac77644f79dbd06c340">llvm::coro::normalizeCoroutine</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#aa2ead3ae2cc059f459be46ce71ef20a5">removeCoroEndsFromRampFunction</a>.</p>

</div>
</div>

### CoroSizes {#a48b7ab2f26b9e2bc67de02229a1cdd1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;CoroSizeInst *, 2&gt; llvm::coro::Shape::CoroSizes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Referenced by <a href="#afe664f8e39ffc3ae37c49342e39d7423">analyze</a>, <a href="#ab4ca8a1156a9b26ecee8c95d328d5739">clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#af1eb41cd2b90362db4ffc6eb47608943">getFrameSizeForShape</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a8543371395854bee27033b8e24836cb0">replaceFrameSizeAndAlignment</a>.</p>

</div>
</div>

### CoroSuspends {#a5fd0aa934908c837c6d78097a2fd667b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AnyCoroSuspendInst *, 4&gt; llvm::coro::Shape::CoroSuspends</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#a0ee1f18526ee78ef18612b6a86dc16fc">anonymous{CoroFrame.cpp}::FrameTypeBuilder::addFieldForAllocas</a>, <a href="#afe664f8e39ffc3ae37c49342e39d7423">analyze</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a712c7e27f92253c99bcc20689a4e93b0">buildFrameType</a>, <a href="#ab4ca8a1156a9b26ecee8c95d328d5739">clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/anonymous-spillutils-cpp-/#a452155536772ef01d3c028f7284ecd2b">llvm::coro::anonymous{SpillUtils.cpp}::collectFrameAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a8bf580168c7138b15f7bfdd080416bec">doSplitCoroutine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a8356860a8bef082ff15df896ecec7732">eliminateSwiftErrorArgument</a>, <a href="#ae365293b0e4b5cb45b3af280d14b26f1">invalidateCoroutine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#aa6734dd82cf736e89074802287b0abfe">markCoroutineAsDone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a8bd87bda26e6aac77644f79dbd06c340">llvm::coro::normalizeCoroutine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a236935b2df66a03a0a54350a6b9b84bc">replaceSwiftErrorOps</a>, <a href="/web-llvm/docs/api/structs/llvm/corosplitpass/#a47f6589634ad33a13369ace133b9f4b2">llvm::CoroSplitPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a76d02f8354cb0d3c8b30eb7812ae01b2">simplifySuspendPoints</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#abb3297c94836debc08248e7ae3f47582">sinkLifetimeStartMarkers</a>.</p>

</div>
</div>

### FrameAlign {#a0a1a8e48ba1e5d845e979d5da8de597d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::coro::Shape::FrameAlign</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a712c7e27f92253c99bcc20689a4e93b0">buildFrameType</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af0793991541abccfec5c0d8831612b7b">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::createNoAllocVariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab7881567f602c3a94d11e2817f4464e0">handleNoSuspendCoroutine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a8543371395854bee27033b8e24836cb0">replaceFrameSizeAndAlignment</a> and <a href="/web-llvm/docs/api/structs/llvm/corosplitpass/#a47f6589634ad33a13369ace133b9f4b2">llvm::CoroSplitPass::run</a>.</p>

</div>
</div>

### FramePtr {#a5eac2988672b484645dcbcd706430967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::coro::Shape::FramePtr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a>, <a href="#ab4ca8a1156a9b26ecee8c95d328d5739">clear</a>, <a href="#ac406c2b5a7e2d11174becab5cb27765d">getInsertPtAfterFramePtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#aa2ead3ae2cc059f459be46ce71ef20a5">removeCoroEndsFromRampFunction</a>.</p>

</div>
</div>

### FrameSize {#a742806b2e667a87817ae171e1ec59826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::coro::Shape::FrameSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a712c7e27f92253c99bcc20689a4e93b0">buildFrameType</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af0793991541abccfec5c0d8831612b7b">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::createNoAllocVariant</a> and <a href="/web-llvm/docs/api/structs/llvm/corosplitpass/#a47f6589634ad33a13369ace133b9f4b2">llvm::CoroSplitPass::run</a>.</p>

</div>
</div>

### FrameTy {#a24c5fed9b14aed8a3b4f3828472fbab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType* llvm::coro::Shape::FrameTy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a>, <a href="#ab4ca8a1156a9b26ecee8c95d328d5739">clear</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af0793991541abccfec5c0d8831612b7b">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::createNoAllocVariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#af1eb41cd2b90362db4ffc6eb47608943">getFrameSizeForShape</a>, <a href="#a22c53726eaeafbc188994ecbc7e27674">getIndexType</a>, <a href="#a1a578073d9d2487a3806e8a51abb1b6e">getResumeFunctionType</a>, <a href="#aedc5db661c24859142b1b7a67dc05ba7">getSwitchIndexField</a>, <a href="#a2e44b079291a98a6f381ddc2f4e613d0">getSwitchResumePointerType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab7881567f602c3a94d11e2817f4464e0">handleNoSuspendCoroutine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#aa6734dd82cf736e89074802287b0abfe">markCoroutineAsDone</a>.</p>

</div>
</div>

### RetconLowering {#ace1508259ecd37ceaafb9162d3768fff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetconLoweringStorage llvm::coro::Shape::RetconLowering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Referenced by <a href="#afe664f8e39ffc3ae37c49342e39d7423">analyze</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a712c7e27f92253c99bcc20689a4e93b0">buildFrameType</a>, <a href="#a78fa8f84df72aa178f82c9421b0cf387">emitAlloc</a>, <a href="#acad2aaa7f484c978bb790533eec90ac4">emitDealloc</a>, <a href="#a4e2e134e22f7bd3f6270ef63546e9994">getResumeFunctionCC</a>, <a href="#a1a578073d9d2487a3806e8a51abb1b6e">getResumeFunctionType</a>, <a href="#a5831a89147ca4aaf1b08877d21ca931b">getRetconResumeTypes</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a3907189466613e437b0ea2731bf9b159">maybeFreeRetconStorage</a>.</p>

</div>
</div>

### SwiftErrorOps {#ae290085a52a8df4810b4e7f48dbe1ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;CallInst *, 2&gt; llvm::coro::Shape::SwiftErrorOps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Referenced by <a href="#ab4ca8a1156a9b26ecee8c95d328d5739">clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#ad7795d2b31b375031144ce50d0f6fa34">emitGetSwiftErrorValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a3d306b9a19fc37d00329692ef499b1b1">emitSetSwiftErrorValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a236935b2df66a03a0a54350a6b9b84bc">replaceSwiftErrorOps</a>.</p>

</div>
</div>

### SwitchLowering {#abe8f7906a8618f90e2a75109a778054a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SwitchLoweringStorage llvm::coro::Shape::SwitchLowering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Referenced by <a href="#afe664f8e39ffc3ae37c49342e39d7423">analyze</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a712c7e27f92253c99bcc20689a4e93b0">buildFrameType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/anonymous-spillutils-cpp-/#a452155536772ef01d3c028f7284ecd2b">llvm::coro::anonymous{SpillUtils.cpp}::collectFrameAlloca</a>, <a href="#aab0e2582dd592f549f16c9a26b9d5f42">getPromiseAlloca</a>, <a href="#aedc5db661c24859142b1b7a67dc05ba7">getSwitchIndexField</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#aa6734dd82cf736e89074802287b0abfe">markCoroutineAsDone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a8bd87bda26e6aac77644f79dbd06c340">llvm::coro::normalizeCoroutine</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a76d02f8354cb0d3c8b30eb7812ae01b2">simplifySuspendPoints</a>.</p>

</div>
</div>

### SymmetricTransfers {#a06f9098a6725a57dcb2b25cdc9fd3398}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;CallInst *, 2&gt; llvm::coro::Shape::SymmetricTransfers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a>.</p>


<p>Referenced by <a href="#ab4ca8a1156a9b26ecee8c95d328d5739">clear</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab5b261757331e18b934bba9c3d3e6b69">lowerAwaitSuspend</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroshape-h">CoroShape.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp">Coroutines.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
