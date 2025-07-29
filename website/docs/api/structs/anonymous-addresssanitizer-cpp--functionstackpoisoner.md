---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `FunctionStackPoisoner` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instvisitor">InstVisitor&lt;SubClass, RetTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for instruction visitors. <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22469895240423b61ee2b39822d5c0af">FunctionStackPoisoner</a> (Function &amp;F, AddressSanitizer &amp;ASan, RuntimeCallInserter &amp;RTCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d9d3b77ad59887d486351a427b585b0">runOnFunction</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf9b16e74216c278e3362f8e84c16ab0">copyArgsPassedByValToAllocas</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2abcf486d1ecbb52d28309b221d6e93">processDynamicAllocas</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5fb89357898044869d600aef33cd1ba">createDynamicAllocasInitStorage</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10bdecf66bc72577ab6c3cc964a076b7">visitReturnInst</a> (ReturnInst &amp;RI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect all Ret instructions, or the musttail call instruction if it precedes the return instruction. <a href="#a10bdecf66bc72577ab6c3cc964a076b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa896496e66721145430011f6ff3021cd">visitResumeInst</a> (ResumeInst &amp;RI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect all Resume instructions. <a href="#aa896496e66721145430011f6ff3021cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d46cb46ca03244c80471051959180eb">visitCleanupReturnInst</a> (CleanupReturnInst &amp;CRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect all <a href="/web-llvm/docs/api/classes/llvm/catchreturninst">CatchReturnInst</a> instructions. <a href="#a2d46cb46ca03244c80471051959180eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab62218bb90bcf921250b9e15b771519d">unpoisonDynamicAllocasBeforeInst</a> (Instruction *InstBefore, Value *SavedStack)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46b8e1495b7d2175e14c470a1e8d6892">unpoisonDynamicAllocas</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c1978d516a0154dd7f006e502ab4cfa">handleDynamicAllocaCall</a> (AllocaInst *AI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d3b181e57e15921dd726d62c5f68a5c">visitAllocaInst</a> (AllocaInst &amp;AI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect Alloca instructions we want (and can) handle. <a href="#a2d3b181e57e15921dd726d62c5f68a5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a307e0ed6d4058b4486ae85bbc1908015">visitIntrinsicInst</a> (IntrinsicInst &amp;II)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect lifetime intrinsic calls to check for use-after-scope errors. <a href="#a307e0ed6d4058b4486ae85bbc1908015">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a549c93c786b6052ba5e485c8eed99a33">visitCallBase</a> (CallBase &amp;CB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e899fce2d5eb5d59204369bb5328878">initializeCallbacks</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4f1a33698e2466ce414169501f01cf4">copyToShadow</a> (ArrayRef&lt; uint8_t &gt; ShadowMask, ArrayRef&lt; uint8_t &gt; ShadowBytes, IRBuilder&lt;&gt; &amp;IRB, Value *ShadowBase)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37064f808b1971939c4076441e36f79d">copyToShadow</a> (ArrayRef&lt; uint8_t &gt; ShadowMask, ArrayRef&lt; uint8_t &gt; ShadowBytes, size_t Begin, size_t End, IRBuilder&lt;&gt; &amp;IRB, Value *ShadowBase)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20e0bf83ea626a73aedc5bc770c461bd">copyToShadowInline</a> (ArrayRef&lt; uint8_t &gt; ShadowMask, ArrayRef&lt; uint8_t &gt; ShadowBytes, size_t Begin, size_t End, IRBuilder&lt;&gt; &amp;IRB, Value *ShadowBase)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a299eb6fe46b875b6f4f3b16ed6255f66">poisonAlloca</a> (Value *V, uint64_t Size, IRBuilder&lt;&gt; &amp;IRB, bool DoPoison)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98d7c2e28dffebb3542fd7c608e6b4cc">createAllocaForLayout</a> (IRBuilder&lt;&gt; &amp;IRB, const ASanStackFrameLayout &amp;L, bool Dynamic)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7497538730b6264d4783b4cbd71db816">createPHI</a> (IRBuilder&lt;&gt; &amp;IRB, Value *Cond, Value *ValueIfTrue, Instruction *ThenTerm, Value *ValueIfFalse)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a069c9f01d5b2e44e5171beae7f71b62b">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer">AddressSanitizer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cf315d5c0ee6b5a3212d0da8ab95361">ASan</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/runtimecallinserter">RuntimeCallInserter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6658c9ec8a5872994fee162488df739c">RTCI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dibuilder">DIBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1846db5a2df4a8c900560be95363210d">DIB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07bc11db490f2edf7839493076c56cb0">C</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c513a8365fda3ff1b3d103e7a52ac26">IntptrTy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf5c2780ad835c54c27248ed826c61e3">IntptrPtrTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/shadowmapping">ShadowMapping</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a994ce80af04048616ca5954e257d6723">Mapping</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7b0b16192f320acab41cea291ab89af">AllocaVec</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4f03fc1e1d45f5bab36586281790978">StaticAllocasToMoveUp</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73c4bbaeb91bf3a238b7b0ce80358601">RetVec</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47e2de0b4b9f5aa2f4dbac5934918332">AsanStackMallocFunc</a>[kMaxAsanStackMallocSizeClass+1]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46862a84496d12848de821de87be3cc3">AsanStackFreeFunc</a>[kMaxAsanStackMallocSizeClass+1]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e0e5d7f6bd2776c14ebd7d9da5913b9">AsanSetShadowFunc</a>[0x100] = {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a129445d4046d1bb9112ae575997c63cb">AsanPoisonStackMemoryFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe4c5b51b8f9aa8c954504023b4c3164">AsanUnpoisonStackMemoryFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4bcb221f841432521314e7b60c5db2c">AsanAllocaPoisonFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eec6ba17e8f3a985fc2103aadeb95f2">AsanAllocasUnpoisonFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/allocapoisoncall">AllocaPoisonCall</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc8c21ea67c0f1d6c30c46a92c39b7ce">DynamicAllocaPoisonCallVec</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/allocapoisoncall">AllocaPoisonCall</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2488dfb5dc557ef2572c0968fbe9c48b">StaticAllocaPoisonCallVec</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06f2eb7cc598cb7f4b9c71f7297899ad">HasUntracedLifetimeIntrinsic</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9c6e2f693408658584fa84e7b4f9833">DynamicAllocaVec</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> *, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58ac19be3b0c63885b1ce9e4082b6f29">StackRestoreVec</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8318591e05d8e62436dee43551e5a115">DynamicAllocaLayout</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d3920fe2be39cc356f1eb8117bb2a3a">LocalEscapeCall</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a568149a261a1175e1ca710fd701bd4f8">HasInlineAsm</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37e62c009b4b8ee7e5854c795bde1ae1">HasReturnsTwiceCall</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c399c0c45426b1c1f0970e28ca70b98">PoisonStack</a></td>
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


<p>Definition at line 994 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FunctionStackPoisoner() {#a22469895240423b61ee2b39822d5c0af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::FunctionStackPoisoner (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer">AddressSanitizer</a> &amp; ASan, <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/runtimecallinserter">RuntimeCallInserter</a> &amp; RTCI)</td>
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



<p>Definition at line 1034 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="#a0cf315d5c0ee6b5a3212d0da8ab95361">ASan</a>, <a href="#a07bc11db490f2edf7839493076c56cb0">C</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a9123bbb6c01ba4b0e0ef3547a5132cd1">ClStack</a>, <a href="#a1846db5a2df4a8c900560be95363210d">DIB</a>, <a href="#a069c9f01d5b2e44e5171beae7f71b62b">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="#acf5c2780ad835c54c27248ed826c61e3">IntptrPtrTy</a>, <a href="#a4c513a8365fda3ff1b3d103e7a52ac26">IntptrTy</a>, <a href="#a994ce80af04048616ca5954e257d6723">Mapping</a>, <a href="#a5c399c0c45426b1c1f0970e28ca70b98">PoisonStack</a> and <a href="#a6658c9ec8a5872994fee162488df739c">RTCI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### copyArgsPassedByValToAllocas() {#acf9b16e74216c278e3362f8e84c16ab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionStackPoisoner::copyArgsPassedByValToAllocas ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1078 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="#a0cf315d5c0ee6b5a3212d0da8ab95361">ASan</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae9f2730f66215fdb82f4e41e45124811">llvm::IRBuilderBase::CreateMemCpy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a069c9f01d5b2e44e5171beae7f71b62b">F</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a62ee7ece4986606d41363bc1f70d5ab2">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode</a> and <a href="/web-llvm/docs/api/classes/llvm/allocainst/#af3bb24b322533dbe8a63c84b18568fe1">llvm::AllocaInst::setAlignment</a>.</p>


<p>Referenced by <a href="#a6d9d3b77ad59887d486351a427b585b0">runOnFunction</a>.</p>

</div>
</div>

### copyToShadow() {#aa4f1a33698e2466ce414169501f01cf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionStackPoisoner::copyToShadow (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; ShadowMask, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; ShadowBytes, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ShadowBase)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1223 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="#aa4f1a33698e2466ce414169501f01cf4">copyToShadow</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#aa4f1a33698e2466ce414169501f01cf4">copyToShadow</a> and <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a>.</p>

</div>
</div>

### copyToShadow() {#a37064f808b1971939c4076441e36f79d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionStackPoisoner::copyToShadow (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; ShadowMask, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; ShadowBytes, size_t Begin, size_t End, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ShadowBase)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1225 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="#a0cf315d5c0ee6b5a3212d0da8ab95361">ASan</a>, <a href="#a6e0e5d7f6bd2776c14ebd7d9da5913b9">AsanSetShadowFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a20e0bf83ea626a73aedc5bc770c461bd">copyToShadowInline</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fabbb9957d8adae962b153273c16bce571">llvm::Done</a>, <a href="#a4c513a8365fda3ff1b3d103e7a52ac26">IntptrTy</a>, <a href="#a6658c9ec8a5872994fee162488df739c">RTCI</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### copyToShadowInline() {#a20e0bf83ea626a73aedc5bc770c461bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionStackPoisoner::copyToShadowInline (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; ShadowMask, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; ShadowBytes, size_t Begin, size_t End, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ShadowBase)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1228 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="#a0cf315d5c0ee6b5a3212d0da8ab95361">ASan</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad4e4b11a1bf18be51b28b7fadfaa97d6">llvm::IRBuilderBase::CreateAlignedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="#a069c9f01d5b2e44e5171beae7f71b62b">F</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a95df4f20c933779306b9a936b88b99a5">llvm::IRBuilderBase::getIntN</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="#a4c513a8365fda3ff1b3d103e7a52ac26">IntptrTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp/#a434449d5a0f4b334aca9163b13b6286ba02b848adda8d7d33a2b25d87dbef1d75">Poison</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#a37064f808b1971939c4076441e36f79d">copyToShadow</a>.</p>

</div>
</div>

### createAllocaForLayout() {#a98d7c2e28dffebb3542fd7c608e6b4cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * FunctionStackPoisoner::createAllocaForLayout (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/asanstackframelayout">ASanStackFrameLayout</a> &amp; L, bool Dynamic)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1234 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#adbb45684e8c1f7cc79db81a276e70471">ClRealignStack</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3ef26a11123d639b64307cc3c1b869b9">llvm::IRBuilderBase::CreatePointerCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca971fd8cc345d8bd9f92e9f7d88fdf20c">llvm::Dynamic</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64748b5a9f8d8dd4499f84312e2c1336">llvm::IRBuilderBase::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="#a4c513a8365fda3ff1b3d103e7a52ac26">IntptrTy</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a36e31f42170be95fc392dad696d9ba19">llvm::AllocaInst::isStaticAlloca</a> and <a href="/web-llvm/docs/api/classes/llvm/allocainst/#af3bb24b322533dbe8a63c84b18568fe1">llvm::AllocaInst::setAlignment</a>.</p>


<p>Referenced by <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a>.</p>

</div>
</div>

### createDynamicAllocasInitStorage() {#ad5fb89357898044869d600aef33cd1ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionStackPoisoner::createDynamicAllocasInitStorage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1086 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a8318591e05d8e62436dee43551e5a115">DynamicAllocaLayout</a>, <a href="#a069c9f01d5b2e44e5171beae7f71b62b">F</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a> and <a href="#a4c513a8365fda3ff1b3d103e7a52ac26">IntptrTy</a>.</p>


<p>Referenced by <a href="#ac2abcf486d1ecbb52d28309b221d6e93">processDynamicAllocas</a>.</p>

</div>
</div>

### createPHI() {#a7497538730b6264d4783b4cbd71db816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode * FunctionStackPoisoner::createPHI (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ValueIfTrue, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ThenTerm, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ValueIfFalse)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1236 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a876fb556ecea804faa2cd8ad1e498ec3">llvm::IRBuilderBase::CreatePHI</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="#a4c513a8365fda3ff1b3d103e7a52ac26">IntptrTy</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>


<p>Referenced by <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a>.</p>

</div>
</div>

### handleDynamicAllocaCall() {#a2c1978d516a0154dd7f006e502ab4cfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionStackPoisoner::handleDynamicAllocaCall (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * AI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1145 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="#ae4bcb221f841432521314e7b60c5db2c">AsanAllocaPoisonFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac79ca3c2d2d74cf33684397a91846564">llvm::IRBuilderBase::CreateIntCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aecd40f9a16dc0ef1e0bc416599f89277">llvm::IRBuilderBase::CreateMul</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aae2c1bf70058f3665edaec525457030c">llvm::IRBuilderBase::CreatePtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a92c83e803f2cf22906da0aaec44ff6d7">llvm::IRBuilderBase::CreateSub</a>, <a href="#a8318591e05d8e62436dee43551e5a115">DynamicAllocaLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="#a069c9f01d5b2e44e5171beae7f71b62b">F</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a42438d0a43720a6571c9138224481754">llvm::AllocaInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a9b5ec84ea363eca9e35ddca20a5313af">llvm::AllocaInst::getAllocatedType</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#af4283a4cef4e2b88f565d827d5857e14">llvm::AllocaInst::getArraySize</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a5d19f3955a23e8eb2a974efcc8fb19da">llvm::AllocaInst::getType</a>, <a href="#a4c513a8365fda3ff1b3d103e7a52ac26">IntptrTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a6da7b2b680f4518d9d5545432e701ba1">kAllocaRzSize</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="#a6658c9ec8a5872994fee162488df739c">RTCI</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#af3bb24b322533dbe8a63c84b18568fe1">llvm::AllocaInst::setAlignment</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#ac2abcf486d1ecbb52d28309b221d6e93">processDynamicAllocas</a>.</p>

</div>
</div>

### initializeCallbacks() {#a3e899fce2d5eb5d59204369bb5328878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionStackPoisoner::initializeCallbacks (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1218 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a273ffd11c1ebf40fc70e3b22009adabda68eec46437c384d8dad18d5464ebc35c">llvm::Always</a>, <a href="#a0cf315d5c0ee6b5a3212d0da8ab95361">ASan</a>, <a href="#ae4bcb221f841432521314e7b60c5db2c">AsanAllocaPoisonFunc</a>, <a href="#a7eec6ba17e8f3a985fc2103aadeb95f2">AsanAllocasUnpoisonFunc</a>, <a href="#a129445d4046d1bb9112ae575997c63cb">AsanPoisonStackMemoryFunc</a>, <a href="#a6e0e5d7f6bd2776c14ebd7d9da5913b9">AsanSetShadowFunc</a>, <a href="#a46862a84496d12848de821de87be3cc3">AsanStackFreeFunc</a>, <a href="#a47e2de0b4b9f5aa2f4dbac5934918332">AsanStackMallocFunc</a>, <a href="#abe4c5b51b8f9aa8c954504023b4c3164">AsanUnpoisonStackMemoryFunc</a>, <a href="#a07bc11db490f2edf7839493076c56cb0">C</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad0243f1634f75e231041023ffaa8501a">llvm::IRBuilderBase::getVoidTy</a>, <a href="#a4c513a8365fda3ff1b3d103e7a52ac26">IntptrTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#addbdc1734f12bc122f2b204052f426df">kAsanAllocaPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#afd65995ac50736f33beadc3c0549ce0b">kAsanAllocasUnpoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a9de96b20be410e7c2014587a070465d4">kAsanPoisonStackMemoryName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a2bec6b8d5a441c0918bbdd1be9df32b3">kAsanSetShadowPrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a21dae1495bdaa52cff0efeff2bb65742">kAsanStackFreeNameTemplate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a7827de59665600c15eebeb456731627c">kAsanStackMallocAlwaysNameTemplate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a311ac214c991fe60e693899d731e311e">kAsanStackMallocNameTemplate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#aa6ae2abfa7c1477f42010a614aa2e20b">kAsanUnpoisonStackMemoryName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#acba05c6df950ff8712fa2194a2b83c87">kMaxAsanStackMallocSizeClass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a273ffd11c1ebf40fc70e3b22009adabdabc366f2d0ba3d681e7a3899917c5d3de">llvm::Runtime</a>.</p>


<p>Referenced by <a href="#a6d9d3b77ad59887d486351a427b585b0">runOnFunction</a>.</p>

</div>
</div>

### poisonAlloca() {#a299eb6fe46b875b6f4f3b16ed6255f66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionStackPoisoner::poisonAlloca (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, uint64_t Size, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, bool DoPoison)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1232 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="#a129445d4046d1bb9112ae575997c63cb">AsanPoisonStackMemoryFunc</a>, <a href="#abe4c5b51b8f9aa8c954504023b4c3164">AsanUnpoisonStackMemoryFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3ef26a11123d639b64307cc3c1b869b9">llvm::IRBuilderBase::CreatePointerCast</a>, <a href="#a4c513a8365fda3ff1b3d103e7a52ac26">IntptrTy</a>, <a href="#a6658c9ec8a5872994fee162488df739c">RTCI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#ac2abcf486d1ecbb52d28309b221d6e93">processDynamicAllocas</a>.</p>

</div>
</div>

### processDynamicAllocas() {#ac2abcf486d1ecbb52d28309b221d6e93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionStackPoisoner::processDynamicAllocas ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1084 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="#a0cf315d5c0ee6b5a3212d0da8ab95361">ASan</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#aacabf2f74c684a07a8d7b499d252f8c9">ClInstrumentDynamicAllocas</a>, <a href="#ad5fb89357898044869d600aef33cd1ba">createDynamicAllocasInitStorage</a>, <a href="#adc8c21ea67c0f1d6c30c46a92c39b7ce">DynamicAllocaPoisonCallVec</a>, <a href="#ac9c6e2f693408658584fa84e7b4f9833">DynamicAllocaVec</a>, <a href="#a2c1978d516a0154dd7f006e502ab4cfa">handleDynamicAllocaCall</a>, <a href="#a299eb6fe46b875b6f4f3b16ed6255f66">poisonAlloca</a> and <a href="#a46b8e1495b7d2175e14c470a1e8d6892">unpoisonDynamicAllocas</a>.</p>


<p>Referenced by <a href="#a6d9d3b77ad59887d486351a427b585b0">runOnFunction</a>.</p>

</div>
</div>

### processStaticAllocas() {#a914ea1510476a800508ae70d159bd8c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionStackPoisoner::processStaticAllocas ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1083 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="#ab7b0b16192f320acab41cea291ab89af">AllocaVec</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a6472489551b8960cc115a93d95eef9f6a4ce0a0358c0de36a6ea4413d7abcbca8">llvm::DIExpression::ApplyOffset</a>, <a href="#a0cf315d5c0ee6b5a3212d0da8ab95361">ASan</a>, <a href="#a46862a84496d12848de821de87be3cc3">AsanStackFreeFunc</a>, <a href="#a47e2de0b4b9f5aa2f4dbac5934918332">AsanStackMallocFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ab65506fece0b5302fe804c49e6580446">ClDynamicAllocaStack</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5443261ddc0795520b7c673e11af38f3">llvm::ComputeASanStackFrameDescription</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9c3dc14da623315dbade0f0d23c8976a">llvm::ComputeASanStackFrameLayout</a>, <a href="#aa4f1a33698e2466ce414169501f01cf4">copyToShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="#a98d7c2e28dffebb3542fd7c608e6b4cc">createAllocaForLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8c75539a39f167f352b37ccdd788a7e4">llvm::IRBuilderBase::CreateICmpEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="#a7497538730b6264d4783b4cbd71db816">createPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3ef26a11123d639b64307cc3c1b869b9">llvm::IRBuilderBase::CreatePointerCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a15889f1df360601e4f92325b39882a34">llvm::createPrivateGlobalForString</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a6472489551b8960cc115a93d95eef9f6a18f3c7099f5b8bfe10361a97ee34a5c9">llvm::DIExpression::DerefBefore</a>, <a href="#a1846db5a2df4a8c900560be95363210d">DIB</a>, <a href="#a069c9f01d5b2e44e5171beae7f71b62b">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a0050ea5bb47a2b75ed9e8239bcd469a6">findStoresToUninstrumentedArgAllocas</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a2cd6efecbc36daba036d332c2556b668">genName</a>, <a href="/web-llvm/docs/api/classes/llvm/debugloc/#a4ff1bb484be62f8dac94fc087f72f524">llvm::DebugLoc::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab73bb6948312ca0f98055c6a74c37045">llvm::IRBuilderBase::getPtrTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a575e3a33ce947932f93b30172ca12f05">llvm::GetShadowBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a14a462c7b5d011363ae9c50a15595609">llvm::GetShadowBytesAfterScope</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a5d19f3955a23e8eb2a974efcc8fb19da">llvm::AllocaInst::getType</a>, <a href="#a568149a261a1175e1ca710fd701bd4f8">HasInlineAsm</a>, <a href="#a37e62c009b4b8ee7e5854c795bde1ae1">HasReturnsTwiceCall</a>, <a href="#acf5c2780ad835c54c27248ed826c61e3">IntptrPtrTy</a>, <a href="#a4c513a8365fda3ff1b3d103e7a52ac26">IntptrTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a27766fe2066043a2c55cc0becdcdd9f1">kAsanOptionDetectUseAfterReturn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaec439e7453d5235457273e9d3739718">llvm::kAsanStackUseAfterReturnMagic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#abd89ac2b95ec4f9f9b87cf28f156322d">kCurrentStackFrameMagic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#acba05c6df950ff8712fa2194a2b83c87">kMaxAsanStackMallocSizeClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#aaf5f0e81eb832fe48c6dc33db623a03c">kMaxStackMallocSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#afb368a1d773581543db2f164baf7fbdf">kMinStackMallocSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#af955cd27ba6d5632e02d374282c4afae">kRetiredStackFrameMagic</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a5d3920fe2be39cc356f1eb8117bb2a3a">LocalEscapeCall</a>, <a href="#a994ce80af04048616ca5954e257d6723">Mapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a273ffd11c1ebf40fc70e3b22009adabda6e7b34fa59e1bd229b207892956dc41c">llvm::Never</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afae608ddbbaa668b04aac083a6683245">llvm::replaceDbgDeclare</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="#a73c4bbaeb91bf3a238b7b0ce80358601">RetVec</a>, <a href="#a6658c9ec8a5872994fee162488df739c">RTCI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a273ffd11c1ebf40fc70e3b22009adabdabc366f2d0ba3d681e7a3899917c5d3de">llvm::Runtime</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad957413955739c91204c96e33e0cc933">llvm::SplitBlockAndInsertIfThen</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7ac00229d8c59902686f52ed061cdc80">llvm::SplitBlockAndInsertIfThenElse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a956c8ddbdae78e48e5a76c33430a4ef6">StackMallocSizeClass</a>, <a href="#a2488dfb5dc557ef2572c0968fbe9c48b">StaticAllocaPoisonCallVec</a> and <a href="#ae4f03fc1e1d45f5bab36586281790978">StaticAllocasToMoveUp</a>.</p>


<p>Referenced by <a href="#a6d9d3b77ad59887d486351a427b585b0">runOnFunction</a>.</p>

</div>
</div>

### runOnFunction() {#a6d9d3b77ad59887d486351a427b585b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::runOnFunction ()</td>
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



<p>Definition at line 1044 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="#ab7b0b16192f320acab41cea291ab89af">AllocaVec</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a635e0541e4c0f8a4c5faba9e9c94aebc">ClDebugStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a3ad807be99d9d4ce4b6a2038719b015c">ClRedzoneByvalArgs</a>, <a href="#acf9b16e74216c278e3362f8e84c16ab0">copyArgsPassedByValToAllocas</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e19a09aeed4c56617c284e099c81de">llvm::depth_first</a>, <a href="#adc8c21ea67c0f1d6c30c46a92c39b7ce">DynamicAllocaPoisonCallVec</a>, <a href="#ac9c6e2f693408658584fa84e7b4f9833">DynamicAllocaVec</a>, <a href="#a069c9f01d5b2e44e5171beae7f71b62b">F</a>, <a href="#a06f2eb7cc598cb7f4b9c71f7297899ad">HasUntracedLifetimeIntrinsic</a>, <a href="#a3e899fce2d5eb5d59204369bb5328878">initializeCallbacks</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a5c399c0c45426b1c1f0970e28ca70b98">PoisonStack</a>, <a href="#ac2abcf486d1ecbb52d28309b221d6e93">processDynamicAllocas</a>, <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a>, <a href="#a2488dfb5dc557ef2572c0968fbe9c48b">StaticAllocaPoisonCallVec</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#a090736355958192cac4db32336c48bbd">visit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a489ae04c136c4b088d849d7d6dc20965">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentFunction</a>.</p>

</div>
</div>

### unpoisonDynamicAllocas() {#a46b8e1495b7d2175e14c470a1e8d6892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::unpoisonDynamicAllocas ()</td>
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



<p>Definition at line 1126 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="#a8318591e05d8e62436dee43551e5a115">DynamicAllocaLayout</a>, <a href="#a73c4bbaeb91bf3a238b7b0ce80358601">RetVec</a>, <a href="#a58ac19be3b0c63885b1ce9e4082b6f29">StackRestoreVec</a> and <a href="#ab62218bb90bcf921250b9e15b771519d">unpoisonDynamicAllocasBeforeInst</a>.</p>


<p>Referenced by <a href="#ac2abcf486d1ecbb52d28309b221d6e93">processDynamicAllocas</a>.</p>

</div>
</div>

### unpoisonDynamicAllocasBeforeInst() {#ab62218bb90bcf921250b9e15b771519d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::unpoisonDynamicAllocasBeforeInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InstBefore, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SavedStack)</td>
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



<p>Definition at line 1104 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="#a7eec6ba17e8f3a985fc2103aadeb95f2">AsanAllocasUnpoisonFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aae2c1bf70058f3665edaec525457030c">llvm::IRBuilderBase::CreatePtrToInt</a>, <a href="#a8318591e05d8e62436dee43551e5a115">DynamicAllocaLayout</a>, <a href="#a4c513a8365fda3ff1b3d103e7a52ac26">IntptrTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a6658c9ec8a5872994fee162488df739c">RTCI</a>.</p>


<p>Referenced by <a href="#a46b8e1495b7d2175e14c470a1e8d6892">unpoisonDynamicAllocas</a>.</p>

</div>
</div>

### visitAllocaInst() {#a2d3b181e57e15921dd726d62c5f68a5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::visitAllocaInst (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; AI)</td>
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

<p>Collect Alloca instructions we want (and can) handle.</p>

<p>Definition at line 1148 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="#ab7b0b16192f320acab41cea291ab89af">AllocaVec</a>, <a href="#a0cf315d5c0ee6b5a3212d0da8ab95361">ASan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ac9c6e2f693408658584fa84e7b4f9833">DynamicAllocaVec</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a9b5ec84ea363eca9e35ddca20a5313af">llvm::AllocaInst::getAllocatedType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a36e31f42170be95fc392dad696d9ba19">llvm::AllocaInst::isStaticAlloca</a> and <a href="#ae4f03fc1e1d45f5bab36586281790978">StaticAllocasToMoveUp</a>.</p>

</div>
</div>

### visitCallBase() {#a549c93c786b6052ba5e485c8eed99a33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::visitCallBase (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
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



<p>Definition at line 1210 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="#a0cf315d5c0ee6b5a3212d0da8ab95361">ASan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a568149a261a1175e1ca710fd701bd4f8">HasInlineAsm</a> and <a href="#a37e62c009b4b8ee7e5854c795bde1ae1">HasReturnsTwiceCall</a>.</p>

</div>
</div>

### visitCleanupReturnInst() {#a2d46cb46ca03244c80471051959180eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::visitCleanupReturnInst (<a href="/web-llvm/docs/api/classes/llvm/cleanupreturninst">CleanupReturnInst</a> &amp; CRI)</td>
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

<p>Collect all <a href="/web-llvm/docs/api/classes/llvm/catchreturninst">CatchReturnInst</a> instructions.</p>

<p>Definition at line 1102 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Reference <a href="#a73c4bbaeb91bf3a238b7b0ce80358601">RetVec</a>.</p>

</div>
</div>

### visitIntrinsicInst() {#a307e0ed6d4058b4486ae85bbc1908015}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::visitIntrinsicInst (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; II)</td>
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

<p>Collect lifetime intrinsic calls to check for use-after-scope errors.</p>

<p>Definition at line 1173 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="#a0cf315d5c0ee6b5a3212d0da8ab95361">ASan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#aacabf2f74c684a07a8d7b499d252f8c9">ClInstrumentDynamicAllocas</a>, <a href="#adc8c21ea67c0f1d6c30c46a92c39b7ce">DynamicAllocaPoisonCallVec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21fe87bf00db76089c043fed6a23fb76">llvm::findAllocaForValue</a>, <a href="#a06f2eb7cc598cb7f4b9c71f7297899ad">HasUntracedLifetimeIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#a4c513a8365fda3ff1b3d103e7a52ac26">IntptrTy</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a36e31f42170be95fc392dad696d9ba19">llvm::AllocaInst::isStaticAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a5b75b94b0d81c2ae458192b4a6544e18">llvm::ConstantInt::isValueValidForType</a>, <a href="#a5d3920fe2be39cc356f1eb8117bb2a3a">LocalEscapeCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#a58ac19be3b0c63885b1ce9e4082b6f29">StackRestoreVec</a> and <a href="#a2488dfb5dc557ef2572c0968fbe9c48b">StaticAllocaPoisonCallVec</a>.</p>

</div>
</div>

### visitResumeInst() {#aa896496e66721145430011f6ff3021cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::visitResumeInst (<a href="/web-llvm/docs/api/classes/llvm/resumeinst">ResumeInst</a> &amp; RI)</td>
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

<p>Collect all Resume instructions.</p>

<p>Definition at line 1099 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Reference <a href="#a73c4bbaeb91bf3a238b7b0ce80358601">RetVec</a>.</p>

</div>
</div>

### visitReturnInst() {#a10bdecf66bc72577ab6c3cc964a076b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::visitReturnInst (<a href="/web-llvm/docs/api/classes/llvm/returninst">ReturnInst</a> &amp; RI)</td>
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

<p>Collect all Ret instructions, or the musttail call instruction if it precedes the return instruction.</p>

<p>Definition at line 1091 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a> and <a href="#a73c4bbaeb91bf3a238b7b0ce80358601">RetVec</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AllocaVec {#ab7b0b16192f320acab41cea291ab89af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AllocaInst *, 16&gt; anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::AllocaVec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1004 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a>, <a href="#a6d9d3b77ad59887d486351a427b585b0">runOnFunction</a> and <a href="#a2d3b181e57e15921dd726d62c5f68a5c">visitAllocaInst</a>.</p>

</div>
</div>

### ASan {#a0cf315d5c0ee6b5a3212d0da8ab95361}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddressSanitizer&amp; anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::ASan</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 996 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#acf9b16e74216c278e3362f8e84c16ab0">copyArgsPassedByValToAllocas</a>, <a href="#a37064f808b1971939c4076441e36f79d">copyToShadow</a>, <a href="#a20e0bf83ea626a73aedc5bc770c461bd">copyToShadowInline</a>, <a href="#a22469895240423b61ee2b39822d5c0af">FunctionStackPoisoner</a>, <a href="#a3e899fce2d5eb5d59204369bb5328878">initializeCallbacks</a>, <a href="#ac2abcf486d1ecbb52d28309b221d6e93">processDynamicAllocas</a>, <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a>, <a href="#a2d3b181e57e15921dd726d62c5f68a5c">visitAllocaInst</a>, <a href="#a549c93c786b6052ba5e485c8eed99a33">visitCallBase</a> and <a href="#a307e0ed6d4058b4486ae85bbc1908015">visitIntrinsicInst</a>.</p>

</div>
</div>

### AsanAllocaPoisonFunc {#ae4bcb221f841432521314e7b60c5db2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::AsanAllocaPoisonFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1012 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a2c1978d516a0154dd7f006e502ab4cfa">handleDynamicAllocaCall</a> and <a href="#a3e899fce2d5eb5d59204369bb5328878">initializeCallbacks</a>.</p>

</div>
</div>

### AsanAllocasUnpoisonFunc {#a7eec6ba17e8f3a985fc2103aadeb95f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::AsanAllocasUnpoisonFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1012 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a3e899fce2d5eb5d59204369bb5328878">initializeCallbacks</a> and <a href="#ab62218bb90bcf921250b9e15b771519d">unpoisonDynamicAllocasBeforeInst</a>.</p>

</div>
</div>

### AsanPoisonStackMemoryFunc {#a129445d4046d1bb9112ae575997c63cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::AsanPoisonStackMemoryFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1011 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a3e899fce2d5eb5d59204369bb5328878">initializeCallbacks</a> and <a href="#a299eb6fe46b875b6f4f3b16ed6255f66">poisonAlloca</a>.</p>

</div>
</div>

### AsanSetShadowFunc {#a6e0e5d7f6bd2776c14ebd7d9da5913b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::AsanSetShadowFunc[0x100] = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1010 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a37064f808b1971939c4076441e36f79d">copyToShadow</a> and <a href="#a3e899fce2d5eb5d59204369bb5328878">initializeCallbacks</a>.</p>

</div>
</div>

### AsanStackFreeFunc {#a46862a84496d12848de821de87be3cc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::AsanStackFreeFunc[kMaxAsanStackMallocSizeClass+1]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1009 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a3e899fce2d5eb5d59204369bb5328878">initializeCallbacks</a> and <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a>.</p>

</div>
</div>

### AsanStackMallocFunc {#a47e2de0b4b9f5aa2f4dbac5934918332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::AsanStackMallocFunc[kMaxAsanStackMallocSizeClass+1]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1008 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a3e899fce2d5eb5d59204369bb5328878">initializeCallbacks</a> and <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a>.</p>

</div>
</div>

### AsanUnpoisonStackMemoryFunc {#abe4c5b51b8f9aa8c954504023b4c3164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::AsanUnpoisonStackMemoryFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1011 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a3e899fce2d5eb5d59204369bb5328878">initializeCallbacks</a> and <a href="#a299eb6fe46b875b6f4f3b16ed6255f66">poisonAlloca</a>.</p>

</div>
</div>

### C {#a07bc11db490f2edf7839493076c56cb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext* anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::C</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 999 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a22469895240423b61ee2b39822d5c0af">FunctionStackPoisoner</a> and <a href="#a3e899fce2d5eb5d59204369bb5328878">initializeCallbacks</a>.</p>

</div>
</div>

### DIB {#a1846db5a2df4a8c900560be95363210d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIBuilder anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::DIB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 998 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a22469895240423b61ee2b39822d5c0af">FunctionStackPoisoner</a> and <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a>.</p>

</div>
</div>

### DynamicAllocaLayout {#a8318591e05d8e62436dee43551e5a115}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst* anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::DynamicAllocaLayout = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1027 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#ad5fb89357898044869d600aef33cd1ba">createDynamicAllocasInitStorage</a>, <a href="#a2c1978d516a0154dd7f006e502ab4cfa">handleDynamicAllocaCall</a>, <a href="#a46b8e1495b7d2175e14c470a1e8d6892">unpoisonDynamicAllocas</a> and <a href="#ab62218bb90bcf921250b9e15b771519d">unpoisonDynamicAllocasBeforeInst</a>.</p>

</div>
</div>

### DynamicAllocaPoisonCallVec {#adc8c21ea67c0f1d6c30c46a92c39b7ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AllocaPoisonCall, 8&gt; anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::DynamicAllocaPoisonCallVec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1021 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#ac2abcf486d1ecbb52d28309b221d6e93">processDynamicAllocas</a>, <a href="#a6d9d3b77ad59887d486351a427b585b0">runOnFunction</a> and <a href="#a307e0ed6d4058b4486ae85bbc1908015">visitIntrinsicInst</a>.</p>

</div>
</div>

### DynamicAllocaVec {#ac9c6e2f693408658584fa84e7b4f9833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AllocaInst *, 1&gt; anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::DynamicAllocaVec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1025 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#ac2abcf486d1ecbb52d28309b221d6e93">processDynamicAllocas</a>, <a href="#a6d9d3b77ad59887d486351a427b585b0">runOnFunction</a> and <a href="#a2d3b181e57e15921dd726d62c5f68a5c">visitAllocaInst</a>.</p>

</div>
</div>

### F {#a069c9f01d5b2e44e5171beae7f71b62b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 995 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#acf9b16e74216c278e3362f8e84c16ab0">copyArgsPassedByValToAllocas</a>, <a href="#a20e0bf83ea626a73aedc5bc770c461bd">copyToShadowInline</a>, <a href="#ad5fb89357898044869d600aef33cd1ba">createDynamicAllocasInitStorage</a>, <a href="#a22469895240423b61ee2b39822d5c0af">FunctionStackPoisoner</a>, <a href="#a2c1978d516a0154dd7f006e502ab4cfa">handleDynamicAllocaCall</a>, <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a> and <a href="#a6d9d3b77ad59887d486351a427b585b0">runOnFunction</a>.</p>

</div>
</div>

### HasInlineAsm {#a568149a261a1175e1ca710fd701bd4f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::HasInlineAsm = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1030 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a> and <a href="#a549c93c786b6052ba5e485c8eed99a33">visitCallBase</a>.</p>

</div>
</div>

### HasReturnsTwiceCall {#a37e62c009b4b8ee7e5854c795bde1ae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::HasReturnsTwiceCall = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1031 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a> and <a href="#a549c93c786b6052ba5e485c8eed99a33">visitCallBase</a>.</p>

</div>
</div>

### HasUntracedLifetimeIntrinsic {#a06f2eb7cc598cb7f4b9c71f7297899ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::HasUntracedLifetimeIntrinsic = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1023 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a6d9d3b77ad59887d486351a427b585b0">runOnFunction</a> and <a href="#a307e0ed6d4058b4486ae85bbc1908015">visitIntrinsicInst</a>.</p>

</div>
</div>

### IntptrPtrTy {#acf5c2780ad835c54c27248ed826c61e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::IntptrPtrTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1001 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a22469895240423b61ee2b39822d5c0af">FunctionStackPoisoner</a> and <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a>.</p>

</div>
</div>

### IntptrTy {#a4c513a8365fda3ff1b3d103e7a52ac26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::IntptrTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1000 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a37064f808b1971939c4076441e36f79d">copyToShadow</a>, <a href="#a20e0bf83ea626a73aedc5bc770c461bd">copyToShadowInline</a>, <a href="#a98d7c2e28dffebb3542fd7c608e6b4cc">createAllocaForLayout</a>, <a href="#ad5fb89357898044869d600aef33cd1ba">createDynamicAllocasInitStorage</a>, <a href="#a7497538730b6264d4783b4cbd71db816">createPHI</a>, <a href="#a22469895240423b61ee2b39822d5c0af">FunctionStackPoisoner</a>, <a href="#a2c1978d516a0154dd7f006e502ab4cfa">handleDynamicAllocaCall</a>, <a href="#a3e899fce2d5eb5d59204369bb5328878">initializeCallbacks</a>, <a href="#a299eb6fe46b875b6f4f3b16ed6255f66">poisonAlloca</a>, <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a>, <a href="#ab62218bb90bcf921250b9e15b771519d">unpoisonDynamicAllocasBeforeInst</a> and <a href="#a307e0ed6d4058b4486ae85bbc1908015">visitIntrinsicInst</a>.</p>

</div>
</div>

### LocalEscapeCall {#a5d3920fe2be39cc356f1eb8117bb2a3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrinsicInst* anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::LocalEscapeCall = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1028 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a> and <a href="#a307e0ed6d4058b4486ae85bbc1908015">visitIntrinsicInst</a>.</p>

</div>
</div>

### Mapping {#a994ce80af04048616ca5954e257d6723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ShadowMapping anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::Mapping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1002 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a22469895240423b61ee2b39822d5c0af">FunctionStackPoisoner</a> and <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a>.</p>

</div>
</div>

### PoisonStack {#a5c399c0c45426b1c1f0970e28ca70b98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::PoisonStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1032 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a22469895240423b61ee2b39822d5c0af">FunctionStackPoisoner</a> and <a href="#a6d9d3b77ad59887d486351a427b585b0">runOnFunction</a>.</p>

</div>
</div>

### RetVec {#a73c4bbaeb91bf3a238b7b0ce80358601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *, 8&gt; anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::RetVec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1006 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a>, <a href="#a46b8e1495b7d2175e14c470a1e8d6892">unpoisonDynamicAllocas</a>, <a href="#a2d46cb46ca03244c80471051959180eb">visitCleanupReturnInst</a>, <a href="#aa896496e66721145430011f6ff3021cd">visitResumeInst</a> and <a href="#a10bdecf66bc72577ab6c3cc964a076b7">visitReturnInst</a>.</p>

</div>
</div>

### RTCI {#a6658c9ec8a5872994fee162488df739c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeCallInserter&amp; anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::RTCI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 997 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a37064f808b1971939c4076441e36f79d">copyToShadow</a>, <a href="#a22469895240423b61ee2b39822d5c0af">FunctionStackPoisoner</a>, <a href="#a2c1978d516a0154dd7f006e502ab4cfa">handleDynamicAllocaCall</a>, <a href="#a299eb6fe46b875b6f4f3b16ed6255f66">poisonAlloca</a>, <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a> and <a href="#ab62218bb90bcf921250b9e15b771519d">unpoisonDynamicAllocasBeforeInst</a>.</p>

</div>
</div>

### StackRestoreVec {#a58ac19be3b0c63885b1ce9e4082b6f29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;IntrinsicInst *, 1&gt; anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::StackRestoreVec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1026 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a46b8e1495b7d2175e14c470a1e8d6892">unpoisonDynamicAllocas</a> and <a href="#a307e0ed6d4058b4486ae85bbc1908015">visitIntrinsicInst</a>.</p>

</div>
</div>

### StaticAllocaPoisonCallVec {#a2488dfb5dc557ef2572c0968fbe9c48b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AllocaPoisonCall, 8&gt; anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::StaticAllocaPoisonCallVec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1022 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a>, <a href="#a6d9d3b77ad59887d486351a427b585b0">runOnFunction</a> and <a href="#a307e0ed6d4058b4486ae85bbc1908015">visitIntrinsicInst</a>.</p>

</div>
</div>

### StaticAllocasToMoveUp {#ae4f03fc1e1d45f5bab36586281790978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AllocaInst *, 16&gt; anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::StaticAllocasToMoveUp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1005 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a914ea1510476a800508ae70d159bd8c0">processStaticAllocas</a> and <a href="#a2d3b181e57e15921dd726d62c5f68a5c">visitAllocaInst</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
