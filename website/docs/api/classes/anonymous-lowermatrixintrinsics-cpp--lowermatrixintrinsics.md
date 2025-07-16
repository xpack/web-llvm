---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LowerMatrixIntrinsics` Class Reference

<p><a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics">LowerMatrixIntrinsics</a> contains the methods used to lower matrix intrinsics. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecb18b3bdad8c28a5e4b0dcf73c17211">LowerMatrixIntrinsics</a> (Function &amp;F, TargetTransformInfo &amp;TTI, FunctionAnalysisManager *AM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af44a0d4c944c50fe30fad03d97e9f66f">getNumOps</a> (Type *VT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34a9fad9290819f56c761e0a17ca7058">isMinimal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this the minimal version executed in the backend pipelines. <a href="#a34a9fad9290819f56c761e0a17ca7058">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a0644b7c29287b0ea96ec3524e092e4">getNumOps</a> (Type *ST, unsigned N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the estimated number of vector ops required for an operation on <span class="doxyComputerOutput">VT</span> * N. <a href="#a0a0644b7c29287b0ea96ec3524e092e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">MatrixTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad5def33faf75944be159808071d9698">getMatrix</a> (Value *MatrixVal, const ShapeInfo &amp;SI, IRBuilder&lt;&gt; &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the set of vectors that a matrix value is lowered to. <a href="#aad5def33faf75944be159808071d9698">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae165cb587ec7f72cf62df6623eba91e7">setShapeInfo</a> (Value *V, ShapeInfo Shape)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">V</span> already has a known shape return false. <a href="#ae165cb587ec7f72cf62df6623eba91e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5033b68f601a44246af550c825892a5">supportsShapeInfo</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if shape information can be used for <span class="doxyComputerOutput">V</span>. <a href="#ad5033b68f601a44246af550c825892a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf1371d869d3a7468c48401a2a321b26">propagateShapeForward</a> (SmallVectorImpl&lt; Instruction * &gt; &amp;WorkList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Propagate the shape information of instructions to their users. <a href="#adf1371d869d3a7468c48401a2a321b26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a611115d09f3dd3ef310f70c87a8ba402">propagateShapeBackward</a> (SmallVectorImpl&lt; Instruction * &gt; &amp;WorkList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Propagate the shape to operands of instructions with shape information. <a href="#a611115d09f3dd3ef310f70c87a8ba402">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47ed1ed3cecee1de815ef53eace647b1">distributeTransposes</a> (Value *Op0, ShapeInfo Shape0, Value *Op1, ShapeInfo Shape1, MatrixBuilder &amp;Builder, function_ref&lt; Instruction *(Value *, ShapeInfo, Value *, ShapeInfo)&gt; Operation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>(Op0 op Op1)^T -&gt; Op0^T op Op1^T Transpose <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span> of shape <span class="doxyComputerOutput">Shape0</span> and <span class="doxyComputerOutput">Shape1</span>, then use them on both sides of <span class="doxyComputerOutput">Operation</span>. <a href="#a47ed1ed3cecee1de815ef53eace647b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b46fe24407e1a38fdf96093359165c1">eraseFromParentAndRemoveFromShapeMap</a> (Instruction *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase <span class="doxyComputerOutput">Inst</span> from both ShapeMap (if an entry exists) and erase <span class="doxyComputerOutput">Inst</span> itself. <a href="#a7b46fe24407e1a38fdf96093359165c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a410a078c88ab7a1e5a4ce7362adc3efa">eraseFromParentAndMove</a> (Value *V, BasicBlock::reverse_iterator &amp;II, BasicBlock &amp;BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase <span class="doxyComputerOutput">V</span> from <span class="doxyComputerOutput">BB</span> and move \II forward to avoid invalidating iterators. <a href="#a410a078c88ab7a1e5a4ce7362adc3efa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90987ac6a5075492b12b46acd6e9814c">updateShapeAndReplaceAllUsesWith</a> (Instruction &amp;Old, Value *New)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new entry to ShapeMap for <span class="doxyComputerOutput">New</span> with <span class="doxyComputerOutput">Old's</span> shape info, erase the entry for <span class="doxyComputerOutput">Old</span> and replace all uses of <span class="doxyComputerOutput">Old</span> with <span class="doxyComputerOutput">New</span>. <a href="#a90987ac6a5075492b12b46acd6e9814c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a911ac5931b86191e44f407ef00132dd2">sinkTranspose</a> (Instruction &amp;I, BasicBlock::reverse_iterator &amp;II)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sink a top-level transpose inside matmuls and adds. <a href="#a911ac5931b86191e44f407ef00132dd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e4c82e1d5800196765f95dbf8b48e6e">liftTranspose</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab02410035de7d54b1abc168a9d48e809">optimizeTransposes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try moving transposes in order to fold them away or into multiplies. <a href="#ab02410035de7d54b1abc168a9d48e809">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49a46654ca2c32ce99be52de089052f8">Visit</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4abe522bf135a7628b059cf5fc0be127">VisitCallInst</a> (CallInst *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace intrinsic calls. <a href="#a4abe522bf135a7628b059cf5fc0be127">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbbb137bc7dc3b49d14cd4fd73a75dcf">getAlignForIndex</a> (unsigned Idx, Value *Stride, Type *ElementTy, MaybeAlign A) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the alignment for a column/row <span class="doxyComputerOutput">Idx</span> with <span class="doxyComputerOutput">Stride</span> between them. <a href="#afbbb137bc7dc3b49d14cd4fd73a75dcf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">MatrixTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d31f8dc135425bc0f938f13bcca4a0a">loadMatrix</a> (Type *Ty, Value *Ptr, MaybeAlign MAlign, Value *Stride, bool IsVolatile, ShapeInfo Shape, IRBuilder&lt;&gt; &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Load a matrix with <span class="doxyComputerOutput">Shape</span> starting at <span class="doxyComputerOutput">Ptr</span> and using <span class="doxyComputerOutput">Stride</span> between vectors. <a href="#a5d31f8dc135425bc0f938f13bcca4a0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">MatrixTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8322b8934ca2ae69762c7056c3bf358">loadMatrix</a> (Value *MatrixPtr, MaybeAlign Align, bool IsVolatile, ShapeInfo MatrixShape, Value *I, Value *J, ShapeInfo ResultShape, Type *EltTy, IRBuilder&lt;&gt; &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads a sub-matrix with shape <span class="doxyComputerOutput">ResultShape</span> from a <span class="doxyComputerOutput">R</span> x <span class="doxyComputerOutput">C</span> matrix, starting at <span class="doxyComputerOutput">MatrixPtr</span>[I][J]. <a href="#aa8322b8934ca2ae69762c7056c3bf358">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b51a567be126f7919bef1c351d859e2">LowerLoad</a> (Instruction *Inst, Value *Ptr, MaybeAlign Align, Value *Stride, bool IsVolatile, ShapeInfo Shape)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower a load instruction with shape information. <a href="#a1b51a567be126f7919bef1c351d859e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a237ac9d59f45a0b7c18296704e005a6c">LowerColumnMajorLoad</a> (CallInst *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lowers llvm.matrix.column.major.load. <a href="#a237ac9d59f45a0b7c18296704e005a6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af928743a3a7070559bd992164e601a19">storeMatrix</a> (const MatrixTy &amp;StoreVal, Value *MatrixPtr, MaybeAlign MAlign, bool IsVolatile, ShapeInfo MatrixShape, Value *I, Value *J, Type *EltTy, IRBuilder&lt;&gt; &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores a sub-matrix <span class="doxyComputerOutput">StoreVal</span> into the <span class="doxyComputerOutput">R</span> x <span class="doxyComputerOutput">C</span> matrix starting at <span class="doxyComputerOutput">MatrixPtr</span>[I][J]. <a href="#af928743a3a7070559bd992164e601a19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">MatrixTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9fae87b41835eff9f16de8aa6b11239">storeMatrix</a> (Type *Ty, MatrixTy StoreVal, Value *Ptr, MaybeAlign MAlign, Value *Stride, bool IsVolatile, IRBuilder&lt;&gt; &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Store matrix <span class="doxyComputerOutput">StoreVal</span> starting at <span class="doxyComputerOutput">Ptr</span> and using <span class="doxyComputerOutput">Stride</span> between vectors. <a href="#ac9fae87b41835eff9f16de8aa6b11239">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fb1dea3dcd9b6517ad7c8a6a7269366">LowerStore</a> (Instruction *Inst, Value *Matrix, Value *Ptr, MaybeAlign A, Value *Stride, bool IsVolatile, ShapeInfo Shape)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower a store instruction with shape information. <a href="#a6fb1dea3dcd9b6517ad7c8a6a7269366">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c72146be47366faa66bbe3fa93abf2a">LowerColumnMajorStore</a> (CallInst *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lowers llvm.matrix.column.major.store. <a href="#a4c72146be47366faa66bbe3fa93abf2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fa9a9154ccdb8775496f8b47315515e">insertVector</a> (Value *Col, unsigned I, Value *Block, IRBuilder&lt;&gt; &amp;Builder)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a573504490eecc9679fda893af5bc01fb">createMulAdd</a> (Value *Sum, Value *A, Value *B, bool UseFPOp, IRBuilder&lt;&gt; &amp;Builder, bool AllowContraction, unsigned &amp;NumComputeOps)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f5b1f0925dc2dbb62f05681772ca912">finalizeLowering</a> (Instruction *Inst, MatrixTy Matrix, IRBuilder&lt;&gt; &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache <span class="doxyComputerOutput">Matrix</span> as result of <span class="doxyComputerOutput">Inst</span> and update the uses of <span class="doxyComputerOutput">Inst</span>. <a href="#a7f5b1f0925dc2dbb62f05681772ca912">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3118e33ed28deca370645b8b909fa5a">lowerDotProduct</a> (CallInst *MatMul, SmallPtrSet&lt; Instruction *, 16 &gt; &amp;FusedInsts, FastMathFlags FMF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Special case for MatMul lowering. <a href="#ab3118e33ed28deca370645b8b909fa5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab04f9a9acf8cd97627dc9b522188b0e8">emitMatrixMultiply</a> (MatrixTy &amp;Result, const MatrixTy &amp;A, const MatrixTy &amp;B, IRBuilder&lt;&gt; &amp;Builder, bool IsTiled, bool IsScalarMatrixTransposed, FastMathFlags FMF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute <span class="doxyComputerOutput">Result</span> += <span class="doxyComputerOutput">A</span> * <span class="doxyComputerOutput">B</span> for input matrices with left-associating addition. <a href="#ab04f9a9acf8cd97627dc9b522188b0e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d8410ca3fc6fb227416067d3c2535d2">getNonAliasingPointer</a> (LoadInst *Load, StoreInst *Store, CallInst *MatMul)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensure that the memory in <span class="doxyComputerOutput">Load</span> does not alias <span class="doxyComputerOutput">Store</span> by potentially copying it to a new location. <a href="#a7d8410ca3fc6fb227416067d3c2535d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdf2ba7931aca786fe764e4361610d3e">isFusionProfitable</a> (CallInst *MatMul)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MatrixTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a897ffb621380e9230778c792ca27d9c4">getZeroMatrix</a> (Type *EltType, unsigned R, unsigned C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fb67d47830d47e72144d7456dbb7fa0">createTiledLoops</a> (CallInst *MatMul, Value *LPtr, ShapeInfo LShape, Value *RPtr, ShapeInfo RShape, StoreInst *Store)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a133fc35b714b7fc4b5a0935c811ed37a">emitSIMDTiling</a> (CallInst *MatMul, LoadInst *LoadOp0, LoadInst *LoadOp1, StoreInst *Store, SmallPtrSetImpl&lt; Instruction * &gt; &amp;FusedInsts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ae0da674977e2cd46d8df703e7dbab1">LowerMatrixMultiplyFused</a> (CallInst *MatMul, SmallPtrSetImpl&lt; Instruction * &gt; &amp;FusedInsts, SmallVector&lt; IntrinsicInst *, 16 &gt; &amp;LifetimeEnds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to lower matrix multiply chains by fusing operations. <a href="#a7ae0da674977e2cd46d8df703e7dbab1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d7b7ecce18021429495c1db66a025ee">LowerMultiply</a> (CallInst *MatMul)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lowers llvm.matrix.multiply. <a href="#a6d7b7ecce18021429495c1db66a025ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadb2a52a94fd7cf1e3f1643e0f5e2934">LowerTranspose</a> (CallInst *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lowers llvm.matrix.transpose. <a href="#aadb2a52a94fd7cf1e3f1643e0f5e2934">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49e11eb7774b75fb97d50d78ed1de951">VisitLoad</a> (LoadInst *Inst, Value *Ptr, IRBuilder&lt;&gt; &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower load instructions, if shape information is available. <a href="#a49e11eb7774b75fb97d50d78ed1de951">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae35d90f9a44c556c4a984b1fd6fae199">VisitStore</a> (StoreInst *Inst, Value *StoredVal, Value *Ptr, IRBuilder&lt;&gt; &amp;Builder)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6977569e4724e3cb0b65e13d0e2a8eb">VisitBinaryOperator</a> (BinaryOperator *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower binary operators, if shape information is available. <a href="#aa6977569e4724e3cb0b65e13d0e2a8eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a851ca1290a8ae078a9e084871aa2e9d7">VisitUnaryOperator</a> (UnaryOperator *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower unary operators, if shape information is available. <a href="#a851ca1290a8ae078a9e084871aa2e9d7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6dacd24677f234d2f1849a8ae1de0ba">Func</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeea840b9eda5b2219baff5a17d112507">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a756f227274ae71540b93f77e12bcef9e">TTI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f1ed500d85d49ed48bc749ae9ad2ee2">AM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87f782c71abaeba81e931fe09f0f1e75">AA</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e392a8f54c9ac71adec3ef9081444a1">DT</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae52578f9fcc9152060dd884fc8482d17">LI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accf064712b3ba2991d1fc9790bf3eba2">ORE</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, ShapeInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a8d00ede246fcdc5c5b4d89489ef960">ShapeMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps instructions to their shape information. <a href="#a6a8d00ede246fcdc5c5b4d89489ef960">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56f516dfbddab41939051b0bc1e244d4">ToRemove</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of instructions to remove. <a href="#a56f516dfbddab41939051b0bc1e244d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, MatrixTy &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a9c27b7faf686491eaeeb56c5f9cce7">Inst2ColumnMatrix</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from instructions to their produced column matrix. <a href="#a9a9c27b7faf686491eaeeb56c5f9cce7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af90d0cc1bdb2afda617c972591f1e7d6">getFastMathFlags</a> (Instruction *Inst)</td>
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

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics">LowerMatrixIntrinsics</a> contains the methods used to lower matrix intrinsics.</p>


<p>Currently, the lowering for each matrix intrinsic is done as follows:</p>


<ol class="doxyList" type="1">
<li>Propagate the shape information from intrinsics to connected instructions.</li>
<li>Lower instructions with shape information (assuming column-major layout). The lowering works similarly using row-major layout. 2.1. Get column vectors for each argument. If we already lowered the definition of an argument, use the produced column vectors directly. If not, split the operand vector containing an embedded matrix into a set of column vectors, 2.2. Lower the instruction in terms of column major operations, which yields a set of column vectors containing result matrix. Note that we lower all instructions that have shape information. Besides the intrinsics, this includes stores for example. 2.3. Update uses of the lowered instruction. If we have shape information for a user, there is nothing to do, as we will look up the result column matrix when lowering the user. For other uses, we embed the result matrix in a flat vector and update the use. 2.4. Cache the result column matrix for the instruction we lowered</li>
<li>After we lowered all instructions in a function, remove the now obsolete instructions.</li>
</ol>

<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LowerMatrixIntrinsics() {#aecb18b3bdad8c28a5e4b0dcf73c17211}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMatrixIntrinsics (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> * AM)</td>
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



<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createMulAdd() {#a573504490eecc9679fda893af5bc01fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::createMulAdd (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Sum, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * A, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * B, bool UseFPOp, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, bool AllowContraction, unsigned &amp; NumComputeOps)</td>
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



<p>Definition at line 1309 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a395795410abf1a79bdb31fdcd955e286">llvm::IRBuilderBase::CreateFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae33cfb24f8bc0f6aa80c3a49e3769f6d">llvm::IRBuilderBase::CreateFMul</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aecd40f9a16dc0ef1e0bc416599f89277">llvm::IRBuilderBase::CreateMul</a>, <a href="#af44a0d4c944c50fe30fad03d97e9f66f">getNumOps</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#ae0f503db91504a3f3440ab81260e4134">Mul</a>.</p>


<p>Referenced by <a href="#ab04f9a9acf8cd97627dc9b522188b0e8">emitMatrixMultiply</a>.</p>

</div>
</div>

### createTiledLoops() {#a1fb67d47830d47e72144d7456dbb7fa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::createTiledLoops (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * MatMul, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LPtr, ShapeInfo LShape, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RPtr, ShapeInfo RShape, <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * Store)</td>
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



<p>Definition at line 1765 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55c9054d63d1c6a39e9c09ba13a482fa">llvm::addStringMetadataToLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/tileinfo/#a3159a958f6b4f8b6d76d34964649237c">llvm::TileInfo::ColumnLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a876fb556ecea804faa2cd8ad1e498ec3">llvm::IRBuilderBase::CreatePHI</a>, <a href="/web-llvm/docs/api/structs/llvm/tileinfo/#a8547d158fd9eb8e0cb27673ac3034a1c">llvm::TileInfo::CreateTiledLoops</a>, <a href="#ab04f9a9acf8cd97627dc9b522188b0e8">emitMatrixMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero/#abfa1cf8b4348407b167f93bc7c01055f">llvm::ConstantAggregateZero::get</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a79c007dcf9fff57e1569e778d7885b5e">llvm::BasicBlock::getSingleSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/tileinfo/matrixloop/#a03990917c56ea04671e917df0af4712e">llvm::TileInfo::MatrixLoop::Header</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/tileinfo/matrixloop/#a464218a0338b692115d6551d58662650">llvm::TileInfo::MatrixLoop::Index</a>, <a href="/web-llvm/docs/api/structs/llvm/tileinfo/#acf6bd724509861d665d98379be763344">llvm::TileInfo::KLoop</a>, <a href="/web-llvm/docs/api/structs/llvm/tileinfo/matrixloop/#acd6ee479ad8f1fa417086ed7f4321ba3">llvm::TileInfo::MatrixLoop::Latch</a>, <a href="#a5d31f8dc135425bc0f938f13bcca4a0a">loadMatrix</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/llvm/tileinfo/#a3e06087e90c0e4057bdc3fe3b0ec5904">llvm::TileInfo::RowLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a>, <a href="#af928743a3a7070559bd992164e601a19">storeMatrix</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#af1138294df67ee063ee3b7632a2f843f">TileSize</a>.</p>


<p>Referenced by <a href="#a133fc35b714b7fc4b5a0935c811ed37a">emitSIMDTiling</a>.</p>

</div>
</div>

### distributeTransposes() {#a47ed1ed3cecee1de815ef53eace647b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::distributeTransposes (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, ShapeInfo Shape0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, ShapeInfo Shape1, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder">MatrixBuilder</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *(<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, ShapeInfo, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, ShapeInfo)&gt; Operation)</td>
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

<p>(Op0 op Op1)^T -&gt; Op0^T op Op1^T Transpose <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span> of shape <span class="doxyComputerOutput">Shape0</span> and <span class="doxyComputerOutput">Shape1</span>, then use them on both sides of <span class="doxyComputerOutput">Operation</span>.</p>

<p>Definition at line 738 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#a5342cc18cecbb68eff164826df1476e0">llvm::MatrixBuilder::CreateMatrixTranspose</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a5b2aa9d3f9f3a7b2d123fef7c5328b8f">Operation</a> and <a href="#ae165cb587ec7f72cf62df6623eba91e7">setShapeInfo</a>.</p>


<p>Referenced by <a href="#a911ac5931b86191e44f407ef00132dd2">sinkTranspose</a>.</p>

</div>
</div>

### emitMatrixMultiply() {#ab04f9a9acf8cd97627dc9b522188b0e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::emitMatrixMultiply (MatrixTy &amp; Result, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MatrixTy &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MatrixTy &amp; B, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, bool IsTiled, bool IsScalarMatrixTransposed, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF)</td>
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

<p>Compute <span class="doxyComputerOutput">Result</span> += <span class="doxyComputerOutput">A</span> * <span class="doxyComputerOutput">B</span> for input matrices with left-associating addition.</p>


<p>We can fold a transpose into the operand that is used to extract scalars. This is the first operands with row-major and the second with column-major. If <span class="doxyComputerOutput">IsScalarMatrixTransposed</span> we assume the appropriate operand is transposed.</p>


<p>Definition at line 1552 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ad8c80fc37943fda4be56cf1e0b6cb145">llvm::FastMathFlags::allowContract</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/tarwriter-cpp/#aac035f4156e2604bfa42ba22c17b83ee">BlockSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a303d984774b5c8af8ee4da0aa1960207">llvm::IRBuilderBase::CreateExtractElement</a>, <a href="#a573504490eecc9679fda893af5bc01fb">createMulAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a40ed7274ff11f079e5b5eae34c818c51">llvm::IRBuilderBase::CreateVectorSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a75cf62ffe10261611bab4d74598ab0e4">insertVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166a183020fbea95c99db23f6d3594f4c4af">llvm::TargetTransformInfo::RGK_FixedWidthVector</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6370e29617c71c8081bbbc68d6058403">llvm::IRBuilderBase::setFastMathFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a5b9bf50c6579a978e5c1104bf8787651">llvm::Splat</a>.</p>


<p>Referenced by <a href="#a1fb67d47830d47e72144d7456dbb7fa0">createTiledLoops</a>, <a href="#a133fc35b714b7fc4b5a0935c811ed37a">emitSIMDTiling</a>, <a href="#a7ae0da674977e2cd46d8df703e7dbab1">LowerMatrixMultiplyFused</a> and <a href="#a6d7b7ecce18021429495c1db66a025ee">LowerMultiply</a>.</p>

</div>
</div>

### emitSIMDTiling() {#a133fc35b714b7fc4b5a0935c811ed37a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::emitSIMDTiling (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * MatMul, <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LoadOp0, <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LoadOp1, <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * Store, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; FusedInsts)</td>
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



<p>Definition at line 1824 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#abf221949fc61d1494af06b50731bdc90af695e73139b1c1d06d77655104370f00">ColumnMajor</a>, <a href="#a1fb67d47830d47e72144d7456dbb7fa0">createTiledLoops</a>, <a href="#ab04f9a9acf8cd97627dc9b522188b0e8">emitMatrixMultiply</a>, <a href="#a7b46fe24407e1a38fdf96093359165c1">eraseFromParentAndRemoveFromShapeMap</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#af51c113a039c82f6870df5dc9666b5e3">llvm::LoadInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73f286a780fbb8c82c0a8574540719ea">llvm::IRBuilderBase::getInt64</a>, <a href="#a7d8410ca3fc6fb227416067d3c2535d2">getNonAliasingPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a897ffb621380e9230778c792ca27d9c4">getZeroMatrix</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a7c779ce2ba55bc94f52014fc25f3d520">llvm::Value::hasNUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#acdf2ba7931aca786fe764e4361610d3e">isFusionProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2eccc19f9061eeb7ad1e30e21f76034d">llvm::LoadInst::isVolatile</a>, <a href="#a5d31f8dc135425bc0f938f13bcca4a0a">loadMatrix</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#af65c97118cdb2629b72d9eeb2f218372">MatrixLayout</a>, <a href="#af928743a3a7070559bd992164e601a19">storeMatrix</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#af1138294df67ee063ee3b7632a2f843f">TileSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#a88f67c4895623017a9a4ad120d0f3265">TileUseLoops</a>.</p>


<p>Referenced by <a href="#a7ae0da674977e2cd46d8df703e7dbab1">LowerMatrixMultiplyFused</a>.</p>

</div>
</div>

### eraseFromParentAndMove() {#a410a078c88ab7a1e5a4ce7362adc3efa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::eraseFromParentAndMove (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a6d3231fb84ed4182ec22e9442a87dbf8">BasicBlock::reverse_iterator</a> &amp; II, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB)</td>
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

<p>Erase <span class="doxyComputerOutput">V</span> from <span class="doxyComputerOutput">BB</span> and move \II forward to avoid invalidating iterators.</p>

<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a7b46fe24407e1a38fdf96093359165c1">eraseFromParentAndRemoveFromShapeMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a9237251072bf6816163abc2d053212ee">llvm::BasicBlock::rend</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a>.</p>


<p>Referenced by <a href="#a911ac5931b86191e44f407ef00132dd2">sinkTranspose</a>.</p>

</div>
</div>

### eraseFromParentAndRemoveFromShapeMap() {#a7b46fe24407e1a38fdf96093359165c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::eraseFromParentAndRemoveFromShapeMap (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
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

<p>Erase <span class="doxyComputerOutput">Inst</span> from both ShapeMap (if an entry exists) and erase <span class="doxyComputerOutput">Inst</span> itself.</p>

<p>Definition at line 756 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>.</p>


<p>Referenced by <a href="#a133fc35b714b7fc4b5a0935c811ed37a">emitSIMDTiling</a>, <a href="#a410a078c88ab7a1e5a4ce7362adc3efa">eraseFromParentAndMove</a>, <a href="#a6e4c82e1d5800196765f95dbf8b48e6e">liftTranspose</a> and <a href="#ab3118e33ed28deca370645b8b909fa5a">lowerDotProduct</a>.</p>

</div>
</div>

### finalizeLowering() {#a7f5b1f0925dc2dbb62f05681772ca912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::finalizeLowering (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, MatrixTy Matrix, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder)</td>
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

<p>Cache <span class="doxyComputerOutput">Matrix</span> as result of <span class="doxyComputerOutput">Inst</span> and update the uses of <span class="doxyComputerOutput">Inst</span>.</p>


<p>For users with shape information, there's nothing to do: they will use the cached value when they are lowered. For other users, <span class="doxyComputerOutput">Matrix</span> is flattened and the uses are updated to use it. Also marks <span class="doxyComputerOutput">Inst</span> for deletion.</p>


<p>Definition at line 1338 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp/#a8989acb71bd355e02bcf3a930b5e54ea">Matrix</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>


<p>Referenced by <a href="#a1b51a567be126f7919bef1c351d859e2">LowerLoad</a>, <a href="#a7ae0da674977e2cd46d8df703e7dbab1">LowerMatrixMultiplyFused</a>, <a href="#a6d7b7ecce18021429495c1db66a025ee">LowerMultiply</a>, <a href="#a6fb1dea3dcd9b6517ad7c8a6a7269366">LowerStore</a>, <a href="#aadb2a52a94fd7cf1e3f1643e0f5e2934">LowerTranspose</a>, <a href="#aa6977569e4724e3cb0b65e13d0e2a8eb">VisitBinaryOperator</a> and <a href="#a851ca1290a8ae078a9e084871aa2e9d7">VisitUnaryOperator</a>.</p>

</div>
</div>

### getAlignForIndex() {#afbbb137bc7dc3b49d14cd4fd73a75dcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getAlignForIndex (unsigned Idx, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Stride, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementTy, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> A)</td>
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

<p>Compute the alignment for a column/row <span class="doxyComputerOutput">Idx</span> with <span class="doxyComputerOutput">Stride</span> between them.</p>


<p>The address at <span class="doxyComputerOutput">Idx</span> == 0 has alignment <span class="doxyComputerOutput">A</span>. If <span class="doxyComputerOutput">Stride</span> is a <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a>, reduce the initial alignment based on the byte offset. For non-ConstantInt strides, return the common alignment of the initial alignment and the element size in bytes.</p>


<p>Definition at line 1134 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd6aa057934751aaac54e5c18bcc18eb">llvm::commonAlignment</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#a5d31f8dc135425bc0f938f13bcca4a0a">loadMatrix</a> and <a href="#ac9fae87b41835eff9f16de8aa6b11239">storeMatrix</a>.</p>

</div>
</div>

### getMatrix() {#aad5def33faf75944be159808071d9698}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MatrixTy anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getMatrix (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * MatrixVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ShapeInfo &amp; SI, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder)</td>
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

<p>Return the set of vectors that a matrix value is lowered to.</p>


<p>If we lowered <span class="doxyComputerOutput">MatrixVal</span>, just return the cache result matrix. Otherwise split the flat vector <span class="doxyComputerOutput">MatrixVal</span> containing a matrix with shape <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a></span> into vectors.</p>


<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af00a6f39da9d94ec387a366ade60aea5">llvm::createSequentialMask</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a2f1d58ac35de4475017aca6c5bda6d44">getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a7ae0da674977e2cd46d8df703e7dbab1">LowerMatrixMultiplyFused</a>, <a href="#a6d7b7ecce18021429495c1db66a025ee">LowerMultiply</a>, <a href="#a6fb1dea3dcd9b6517ad7c8a6a7269366">LowerStore</a>, <a href="#aadb2a52a94fd7cf1e3f1643e0f5e2934">LowerTranspose</a>, <a href="#aa6977569e4724e3cb0b65e13d0e2a8eb">VisitBinaryOperator</a> and <a href="#a851ca1290a8ae078a9e084871aa2e9d7">VisitUnaryOperator</a>.</p>

</div>
</div>

### getNonAliasingPointer() {#a7d8410ca3fc6fb227416067d3c2535d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getNonAliasingPointer (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * Load, <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * Store, <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * MatMul)</td>
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

<p>Ensure that the memory in <span class="doxyComputerOutput">Load</span> does not alias <span class="doxyComputerOutput">Store</span> by potentially copying it to a new location.</p>


<p>This new or otherwise the original location is returned.</p>


<p>Definition at line 1636 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a972c30f044db799668bdcace5544edeb">llvm::IRBuilderBase::CreateCondBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a09b4daefdf5b73efba51ce7ae6cd45c5">llvm::IRBuilderBase::CreateICmpULT</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae9f2730f66215fdb82f4e41e45124811">llvm::IRBuilderBase::CreateMemCpy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a876fb556ecea804faa2cd8ad1e498ec3">llvm::IRBuilderBase::CreatePHI</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aae2c1bf70058f3665edaec525457030c">llvm::IRBuilderBase::CreatePtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a18e5a3f1d71ba10a624f2a8e5121cf1f">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a42438d0a43720a6571c9138224481754">llvm::AllocaInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a584bce969457b34c7ac5037d5c549371">llvm::IRBuilderBase::getIntPtrTy</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a9550ce4a179e46db37f653ce28feca7a">llvm::MemoryLocation::Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a39f7ff959874bf38f3e14aa0b2622da0">llvm::MemoryLocation::Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="#a133fc35b714b7fc4b5a0935c811ed37a">emitSIMDTiling</a>.</p>

</div>
</div>

### getNumOps() {#af44a0d4c944c50fe30fad03d97e9f66f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getNumOps (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * VT)</td>
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



<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#af44a0d4c944c50fe30fad03d97e9f66f">getNumOps</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a573504490eecc9679fda893af5bc01fb">createMulAdd</a>, <a href="#af44a0d4c944c50fe30fad03d97e9f66f">getNumOps</a>, <a href="#a5d31f8dc135425bc0f938f13bcca4a0a">loadMatrix</a>, <a href="#ac9fae87b41835eff9f16de8aa6b11239">storeMatrix</a>, <a href="#aa6977569e4724e3cb0b65e13d0e2a8eb">VisitBinaryOperator</a> and <a href="#a851ca1290a8ae078a9e084871aa2e9d7">VisitUnaryOperator</a>.</p>

</div>
</div>

### getNumOps() {#a0a0644b7c29287b0ea96ec3524e092e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getNumOps (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ST, unsigned N)</td>
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

<p>Return the estimated number of vector ops required for an operation on <span class="doxyComputerOutput">VT</span> * N.</p>

<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166a183020fbea95c99db23f6d3594f4c4af">llvm::TargetTransformInfo::RGK_FixedWidthVector</a>.</p>

</div>
</div>

### getZeroMatrix() {#a897ffb621380e9230778c792ca27d9c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MatrixTy anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getZeroMatrix (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * EltType, unsigned R, unsigned C)</td>
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



<p>Definition at line 1757 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero/#abfa1cf8b4348407b167f93bc7c01055f">llvm::ConstantAggregateZero::get</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a133fc35b714b7fc4b5a0935c811ed37a">emitSIMDTiling</a>.</p>

</div>
</div>

### insertVector() {#a1fa9a9154ccdb8775496f8b47315515e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::insertVector (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Col, unsigned I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Block, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder)</td>
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



<p>Definition at line 1279 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af00a6f39da9d94ec387a366ade60aea5">llvm::createSequentialMask</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### isFusionProfitable() {#acdf2ba7931aca786fe764e4361610d3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::isFusionProfitable (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * MatMul)</td>
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



<p>Definition at line 1721 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#a053e31c808de70c3ce24bdab299ecb2f">ForceFusion</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166a183020fbea95c99db23f6d3594f4c4af">llvm::TargetTransformInfo::RGK_FixedWidthVector</a>.</p>


<p>Referenced by <a href="#a133fc35b714b7fc4b5a0935c811ed37a">emitSIMDTiling</a>.</p>

</div>
</div>

### isMinimal() {#a34a9fad9290819f56c761e0a17ca7058}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::isMinimal ()</td>
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

<p>Is this the minimal version executed in the backend pipelines.</p>

<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>Referenced by <a href="#a49a46654ca2c32ce99be52de089052f8">Visit</a>.</p>

</div>
</div>

### liftTranspose() {#a6e4c82e1d5800196765f95dbf8b48e6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::liftTranspose (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 889 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowermatrixintrinsics-cpp-/#abb6c70c6f3c205d6a0b73be4534c0de5">anonymous{LowerMatrixIntrinsics.cpp}::computeShapeInfoForInst</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a395795410abf1a79bdb31fdcd955e286">llvm::IRBuilderBase::CreateFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#ac4d302983f7d34c7555b016c5901341a">llvm::MatrixBuilder::CreateMatrixMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#a5342cc18cecbb68eff164826df1476e0">llvm::MatrixBuilder::CreateMatrixTranspose</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a7b46fe24407e1a38fdf96093359165c1">eraseFromParentAndRemoveFromShapeMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3aa1f5d3cd54d36e7e47f401a0118aeb">llvm::PatternMatch::m_ConstantInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a4ea054dc4c7dd6b5a27eaf33b7fa20b5">llvm::PatternMatch::m_FAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="#ae165cb587ec7f72cf62df6623eba91e7">setShapeInfo</a> and <a href="#a90987ac6a5075492b12b46acd6e9814c">updateShapeAndReplaceAllUsesWith</a>.</p>


<p>Referenced by <a href="#ab02410035de7d54b1abc168a9d48e809">optimizeTransposes</a>.</p>

</div>
</div>

### loadMatrix() {#a5d31f8dc135425bc0f938f13bcca4a0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MatrixTy anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::loadMatrix (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> MAlign, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Stride, bool IsVolatile, ShapeInfo Shape, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder)</td>
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

<p>Load a matrix with <span class="doxyComputerOutput">Shape</span> starting at <span class="doxyComputerOutput">Ptr</span> and using <span class="doxyComputerOutput">Stride</span> between vectors.</p>

<p>Definition at line 1151 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowermatrixintrinsics-cpp-/#a827ab2e54dd47060734cc255e8af3bb9">anonymous{LowerMatrixIntrinsics.cpp}::computeVectorAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3313ae2d314fb689cebdaf062d86eec5">llvm::IRBuilderBase::CreateAlignedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="#afbbb137bc7dc3b49d14cd4fd73a75dcf">getAlignForIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a95df4f20c933779306b9a936b88b99a5">llvm::IRBuilderBase::getIntN</a>, <a href="#af44a0d4c944c50fe30fad03d97e9f66f">getNumOps</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">llvm::Vector</a>.</p>


<p>Referenced by <a href="#a1fb67d47830d47e72144d7456dbb7fa0">createTiledLoops</a>, <a href="#a133fc35b714b7fc4b5a0935c811ed37a">emitSIMDTiling</a>, <a href="#aa8322b8934ca2ae69762c7056c3bf358">loadMatrix</a> and <a href="#a1b51a567be126f7919bef1c351d859e2">LowerLoad</a>.</p>

</div>
</div>

### loadMatrix() {#aa8322b8934ca2ae69762c7056c3bf358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MatrixTy anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::loadMatrix (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * MatrixPtr, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> Align, bool IsVolatile, ShapeInfo MatrixShape, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * J, ShapeInfo ResultShape, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * EltTy, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder)</td>
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

<p>Loads a sub-matrix with shape <span class="doxyComputerOutput">ResultShape</span> from a <span class="doxyComputerOutput">R</span> x <span class="doxyComputerOutput">C</span> matrix, starting at <span class="doxyComputerOutput">MatrixPtr</span>[I][J].</p>

<p>Definition at line 1174 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73e0482b96d9d0cdfcc90c0a34f5b0db">llvm::IRBuilderBase::CreateGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aecd40f9a16dc0ef1e0bc416599f89277">llvm::IRBuilderBase::CreateMul</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73f286a780fbb8c82c0a8574540719ea">llvm::IRBuilderBase::getInt64</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a5d31f8dc135425bc0f938f13bcca4a0a">loadMatrix</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### LowerColumnMajorLoad() {#a237ac9d59f45a0b7c18296704e005a6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerColumnMajorLoad (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * Inst)</td>
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

<p>Lowers llvm.matrix.column.major.load.</p>


<p>The intrinsic loads a matrix from memory using a stride between columns.</p>


<p>Definition at line 1204 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#abf221949fc61d1494af06b50731bdc90af695e73139b1c1d06d77655104370f00">ColumnMajor</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a7713a45c8983df00c3975444b94e69ae">llvm::CallBase::getParamAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a47413709ef916baf36607da462d93ccc">LowerLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#af65c97118cdb2629b72d9eeb2f218372">MatrixLayout</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#a4abe522bf135a7628b059cf5fc0be127">VisitCallInst</a>.</p>

</div>
</div>

### LowerColumnMajorStore() {#a4c72146be47366faa66bbe3fa93abf2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerColumnMajorStore (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * Inst)</td>
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

<p>Lowers llvm.matrix.column.major.store.</p>


<p>The intrinsic store a matrix back memory using a stride between columns.</p>


<p>Definition at line 1267 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#abf221949fc61d1494af06b50731bdc90af695e73139b1c1d06d77655104370f00">ColumnMajor</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a7713a45c8983df00c3975444b94e69ae">llvm::CallBase::getParamAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a05914158f39e230548b1b743eee2e5f6">LowerStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp/#a8989acb71bd355e02bcf3a930b5e54ea">Matrix</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#af65c97118cdb2629b72d9eeb2f218372">MatrixLayout</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#a4abe522bf135a7628b059cf5fc0be127">VisitCallInst</a>.</p>

</div>
</div>

### lowerDotProduct() {#ab3118e33ed28deca370645b8b909fa5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::lowerDotProduct (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * MatMul, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 16 &gt; &amp; FusedInsts, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF)</td>
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

<p>Special case for MatMul lowering.</p>


<p>Prevents scalar loads of row-major vectors Lowers to vector reduction add instead of sequential add if reassocation is enabled.</p>


<p>Definition at line 1358 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a9f3a7d3a575da12ac2fec17849b7b916">llvm::FastMathFlags::allowReassoc</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#abf221949fc61d1494af06b50731bdc90af695e73139b1c1d06d77655104370f00">ColumnMajor</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a55e749d466d9f4f85f52f218b0ca04b3">llvm::IRBuilderBase::CreateAddReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a09180737dfe9015739f3dedfe7da2883">llvm::IRBuilderBase::CreateFAddReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae33cfb24f8bc0f6aa80c3a49e3769f6d">llvm::IRBuilderBase::CreateFMul</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a17320ebd77e834577a5ebd1063039625">llvm::IRBuilderBase::CreateInsertElement</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aecd40f9a16dc0ef1e0bc416599f89277">llvm::IRBuilderBase::CreateMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a7b46fe24407e1a38fdf96093359165c1">eraseFromParentAndRemoveFromShapeMap</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a57207993e2fe6ec98912e8072e4600bc">llvm::InstructionCost::getInvalid</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0698afabe907d2d3b87889d2e0349d47">llvm::PatternMatch::m_BinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#afc43bc5ec4b20c7c5d663bef90da6066">llvm::PatternMatch::m_CombineOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6a512a71ae0746953ca6585669a4d47c">llvm::PatternMatch::m_Load</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2471be3f1b50002f54bf45c590d8d41b">llvm::PatternMatch::m_SpecificInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#af65c97118cdb2629b72d9eeb2f218372">MatrixLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#ae0f503db91504a3f3440ab81260e4134">Mul</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5ca8aa62fa8b3fe5bc0e8fbe5d8b8b7a">llvm::Instruction::setFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ecaa9e18b2636661e341804da24971997df">llvm::TargetTransformInfo::SK_Splice</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">llvm::TargetTransformInfo::TCK_RecipThroughput</a>.</p>


<p>Referenced by <a href="#a49a46654ca2c32ce99be52de089052f8">Visit</a>.</p>

</div>
</div>

### LowerLoad() {#a1b51a567be126f7919bef1c351d859e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerLoad (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> Align, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Stride, bool IsVolatile, ShapeInfo Shape)</td>
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

<p>Lower a load instruction with shape information.</p>

<p>Definition at line 1192 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="#a7f5b1f0925dc2dbb62f05681772ca912">finalizeLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a5d31f8dc135425bc0f938f13bcca4a0a">loadMatrix</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### LowerMatrixMultiplyFused() {#a7ae0da674977e2cd46d8df703e7dbab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMatrixMultiplyFused (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * MatMul, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; FusedInsts, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> *, 16 &gt; &amp; LifetimeEnds)</td>
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

<p>Try to lower matrix multiply chains by fusing operations.</p>


<p>Call finalizeLowering on lowered instructions. Instructions that are completely eliminated by fusion are added to <span class="doxyComputerOutput">FusedInsts</span>.</p>


<p>Definition at line 1893 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#abf221949fc61d1494af06b50731bdc90af695e73139b1c1d06d77655104370f00">ColumnMajor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ab04f9a9acf8cd97627dc9b522188b0e8">emitMatrixMultiply</a>, <a href="#a133fc35b714b7fc4b5a0935c811ed37a">emitSIMDTiling</a>, <a href="#a7f5b1f0925dc2dbb62f05681772ca912">finalizeLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#a90758d8fbf34c21c81a4096a78f9fa61">FuseMatrix</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a18e5a3f1d71ba10a624f2a8e5121cf1f">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#afc51de08aefeeaabc77fefacc869dbd4">llvm::MemoryLocation::getForArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="#aad5def33faf75944be159808071d9698">getMatrix</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#af65c97118cdb2629b72d9eeb2f218372">MatrixLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a54507f01d7d06127068ee0663233511d">llvm::Instruction::moveAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a9550ce4a179e46db37f653ce28feca7a">llvm::MemoryLocation::Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a158da2b6d3d938aaa15b6acd00150e2c">llvm::Value::user_begin</a>.</p>


<p>Referenced by <a href="#a49a46654ca2c32ce99be52de089052f8">Visit</a>.</p>

</div>
</div>

### LowerMultiply() {#a6d7b7ecce18021429495c1db66a025ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMultiply (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * MatMul)</td>
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

<p>Lowers llvm.matrix.multiply.</p>

<p>Definition at line 2039 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ab04f9a9acf8cd97627dc9b522188b0e8">emitMatrixMultiply</a>, <a href="#a7f5b1f0925dc2dbb62f05681772ca912">finalizeLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="#aad5def33faf75944be159808071d9698">getMatrix</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="#a4abe522bf135a7628b059cf5fc0be127">VisitCallInst</a>.</p>

</div>
</div>

### LowerStore() {#a6fb1dea3dcd9b6517ad7c8a6a7269366}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerStore (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Matrix, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> A, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Stride, bool IsVolatile, ShapeInfo Shape)</td>
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

<p>Lower a store instruction with shape information.</p>

<p>Definition at line 1254 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a7f5b1f0925dc2dbb62f05681772ca912">finalizeLowering</a>, <a href="#aad5def33faf75944be159808071d9698">getMatrix</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp/#a8989acb71bd355e02bcf3a930b5e54ea">Matrix</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="#af928743a3a7070559bd992164e601a19">storeMatrix</a>.</p>

</div>
</div>

### LowerTranspose() {#aadb2a52a94fd7cf1e3f1643e0f5e2934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerTranspose (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * Inst)</td>
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

<p>Lowers llvm.matrix.transpose.</p>

<p>Definition at line 2065 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a303d984774b5c8af8ee4da0aa1960207">llvm::IRBuilderBase::CreateExtractElement</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a17320ebd77e834577a5ebd1063039625">llvm::IRBuilderBase::CreateInsertElement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="#a7f5b1f0925dc2dbb62f05681772ca912">finalizeLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="#aad5def33faf75944be159808071d9698">getMatrix</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a4abe522bf135a7628b059cf5fc0be127">VisitCallInst</a>.</p>

</div>
</div>

### optimizeTransposes() {#ab02410035de7d54b1abc168a9d48e809}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::optimizeTransposes ()</td>
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

<p>Try moving transposes in order to fold them away or into multiplies.</p>

<p>Definition at line 947 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#a6e4c82e1d5800196765f95dbf8b48e6e">liftTranspose</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a> and <a href="#a911ac5931b86191e44f407ef00132dd2">sinkTranspose</a>.</p>


<p>Referenced by <a href="#a49a46654ca2c32ce99be52de089052f8">Visit</a>.</p>

</div>
</div>

### propagateShapeBackward() {#a611115d09f3dd3ef310f70c87a8ba402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; Instruction *, 32 &gt; anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::propagateShapeBackward (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; WorkList)</td>
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

<p>Propagate the shape to operands of instructions with shape information.</p>


<p><span class="doxyComputerOutput">Worklist</span> contains the instruction for which we already know the shape.</p>


<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowermatrixintrinsics-cpp-/#a3503dfc307947e3d17f8e243dea3db50">anonymous{LowerMatrixIntrinsics.cpp}::isUniformShape</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ae165cb587ec7f72cf62df6623eba91e7">setShapeInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#ac2f338c3f467b3d09613e190d73044a5">users</a>.</p>


<p>Referenced by <a href="#a49a46654ca2c32ce99be52de089052f8">Visit</a>.</p>

</div>
</div>

### propagateShapeForward() {#adf1371d869d3a7468c48401a2a321b26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; Instruction *, 32 &gt; anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::propagateShapeForward (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; WorkList)</td>
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

<p>Propagate the shape information of instructions to their users.</p>


<p>The work list contains instructions for which we can compute the shape, either based on the information provided by matrix intrinsics or known shapes of operands.</p>


<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowermatrixintrinsics-cpp-/#abb6c70c6f3c205d6a0b73be4534c0de5">anonymous{LowerMatrixIntrinsics.cpp}::computeShapeInfoForInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ae165cb587ec7f72cf62df6623eba91e7">setShapeInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="#a49a46654ca2c32ce99be52de089052f8">Visit</a>.</p>

</div>
</div>

### setShapeInfo() {#ae165cb587ec7f72cf62df6623eba91e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::setShapeInfo (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, ShapeInfo Shape)</td>
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

<p>If <span class="doxyComputerOutput">V</span> already has a known shape return false.</p>


<p>Otherwise set the shape for instructions that support it.</p>


<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="#ad5033b68f601a44246af550c825892a5">supportsShapeInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#a19d18edd6ffdafb20f0fd91a5963d0f8">VerifyShapeInfo</a>.</p>


<p>Referenced by <a href="#a47ed1ed3cecee1de815ef53eace647b1">distributeTransposes</a>, <a href="#a6e4c82e1d5800196765f95dbf8b48e6e">liftTranspose</a>, <a href="#a611115d09f3dd3ef310f70c87a8ba402">propagateShapeBackward</a>, <a href="#adf1371d869d3a7468c48401a2a321b26">propagateShapeForward</a> and <a href="#a911ac5931b86191e44f407ef00132dd2">sinkTranspose</a>.</p>

</div>
</div>

### sinkTranspose() {#a911ac5931b86191e44f407ef00132dd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::sinkTranspose (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a6d3231fb84ed4182ec22e9442a87dbf8">BasicBlock::reverse_iterator</a> &amp; II)</td>
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

<p>Sink a top-level transpose inside matmuls and adds.</p>


<p>This creates and erases instructions as needed, and returns the newly created instruction while updating the iterator to avoid invalidation. If this returns nullptr, no new instruction was created.</p>


<p>Definition at line 795 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a395795410abf1a79bdb31fdcd955e286">llvm::IRBuilderBase::CreateFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae33cfb24f8bc0f6aa80c3a49e3769f6d">llvm::IRBuilderBase::CreateFMul</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#ac4d302983f7d34c7555b016c5901341a">llvm::MatrixBuilder::CreateMatrixMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aecd40f9a16dc0ef1e0bc416599f89277">llvm::IRBuilderBase::CreateMul</a>, <a href="#a47ed1ed3cecee1de815ef53eace647b1">distributeTransposes</a>, <a href="#a410a078c88ab7a1e5a4ce7362adc3efa">eraseFromParentAndMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#a6a2164e5aeea9c3e9a02eab3747efd8c">isSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#a93a97c876de2b13925eedd660ac411f9">m_AnyAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#ad3ea8483bb698ffc64dc1adf7c84a098">m_AnyMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3aa1f5d3cd54d36e7e47f401a0118aeb">llvm::PatternMatch::m_ConstantInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#ae0f503db91504a3f3440ab81260e4134">Mul</a>, <a href="#ae165cb587ec7f72cf62df6623eba91e7">setShapeInfo</a> and <a href="#a90987ac6a5075492b12b46acd6e9814c">updateShapeAndReplaceAllUsesWith</a>.</p>


<p>Referenced by <a href="#ab02410035de7d54b1abc168a9d48e809">optimizeTransposes</a>.</p>

</div>
</div>

### storeMatrix() {#af928743a3a7070559bd992164e601a19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::storeMatrix (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MatrixTy &amp; StoreVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * MatrixPtr, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> MAlign, bool IsVolatile, ShapeInfo MatrixShape, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * J, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * EltTy, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder)</td>
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

<p>Stores a sub-matrix <span class="doxyComputerOutput">StoreVal</span> into the <span class="doxyComputerOutput">R</span> x <span class="doxyComputerOutput">C</span> matrix starting at <span class="doxyComputerOutput">MatrixPtr</span>[I][J].</p>

<p>Definition at line 1216 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73e0482b96d9d0cdfcc90c0a34f5b0db">llvm::IRBuilderBase::CreateGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aecd40f9a16dc0ef1e0bc416599f89277">llvm::IRBuilderBase::CreateMul</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73f286a780fbb8c82c0a8574540719ea">llvm::IRBuilderBase::getInt64</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#af928743a3a7070559bd992164e601a19">storeMatrix</a>.</p>


<p>Referenced by <a href="#a1fb67d47830d47e72144d7456dbb7fa0">createTiledLoops</a>, <a href="#a133fc35b714b7fc4b5a0935c811ed37a">emitSIMDTiling</a>, <a href="#a6fb1dea3dcd9b6517ad7c8a6a7269366">LowerStore</a> and <a href="#af928743a3a7070559bd992164e601a19">storeMatrix</a>.</p>

</div>
</div>

### storeMatrix() {#ac9fae87b41835eff9f16de8aa6b11239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MatrixTy anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::storeMatrix (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, MatrixTy StoreVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> MAlign, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Stride, bool IsVolatile, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder)</td>
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

<p>Store matrix <span class="doxyComputerOutput">StoreVal</span> starting at <span class="doxyComputerOutput">Ptr</span> and using <span class="doxyComputerOutput">Stride</span> between vectors.</p>

<p>Definition at line 1232 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowermatrixintrinsics-cpp-/#a827ab2e54dd47060734cc255e8af3bb9">anonymous{LowerMatrixIntrinsics.cpp}::computeVectorAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad4e4b11a1bf18be51b28b7fadfaa97d6">llvm::IRBuilderBase::CreateAlignedStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="#afbbb137bc7dc3b49d14cd4fd73a75dcf">getAlignForIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a95df4f20c933779306b9a936b88b99a5">llvm::IRBuilderBase::getIntN</a>, <a href="#af44a0d4c944c50fe30fad03d97e9f66f">getNumOps</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### supportsShapeInfo() {#ad5033b68f601a44246af550c825892a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::supportsShapeInfo (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Returns true if shape information can be used for <span class="doxyComputerOutput">V</span>.</p>


<p>The supported instructions must match the instructions that can be lowered by this pass.</p>


<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-lowermatrixintrinsics-cpp-/#a3503dfc307947e3d17f8e243dea3db50">anonymous{LowerMatrixIntrinsics.cpp}::isUniformShape</a>.</p>


<p>Referenced by <a href="#ae165cb587ec7f72cf62df6623eba91e7">setShapeInfo</a> and <a href="#a90987ac6a5075492b12b46acd6e9814c">updateShapeAndReplaceAllUsesWith</a>.</p>

</div>
</div>

### updateShapeAndReplaceAllUsesWith() {#a90987ac6a5075492b12b46acd6e9814c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::updateShapeAndReplaceAllUsesWith (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Old, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * New)</td>
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

<p>Add a new entry to ShapeMap for <span class="doxyComputerOutput">New</span> with <span class="doxyComputerOutput">Old's</span> shape info, erase the entry for <span class="doxyComputerOutput">Old</span> and replace all uses of <span class="doxyComputerOutput">Old</span> with <span class="doxyComputerOutput">New</span>.</p>

<p>Definition at line 778 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a> and <a href="#ad5033b68f601a44246af550c825892a5">supportsShapeInfo</a>.</p>


<p>Referenced by <a href="#a6e4c82e1d5800196765f95dbf8b48e6e">liftTranspose</a> and <a href="#a911ac5931b86191e44f407ef00132dd2">sinkTranspose</a>.</p>

</div>
</div>

### Visit() {#a49a46654ca2c32ce99be52de089052f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::Visit ()</td>
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



<p>Definition at line 969 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/remarkgenerator/#afa50ad465c63aba4cc83c1e37248a860">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::RemarkGenerator::emitRemarks</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#af8a50544090e81ac83601aff8f4b0142">llvm::SmallPtrSetImplBase::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#a34384400167eb6ebf71fa89d98ba03bc">llvm::SmallSet&lt; T, N, C &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#a75a2d2ad3b3dce6702750d570ee8f343">llvm::SmallSet&lt; T, N, C &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="#a34a9fad9290819f56c761e0a17ca7058">isMinimal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ab3118e33ed28deca370645b8b909fa5a">lowerDotProduct</a>, <a href="#a7ae0da674977e2cd46d8df703e7dbab1">LowerMatrixMultiplyFused</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6a512a71ae0746953ca6585669a4d47c">llvm::PatternMatch::m_Load</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a00ad7932f192b7c4702d78902155536d">llvm::PatternMatch::m_Store</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="#ab02410035de7d54b1abc168a9d48e809">optimizeTransposes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#ad734989a4b7c85c8b529f7f7d2da1327">PrintAfterTransposeOpt</a>, <a href="#a611115d09f3dd3ef310f70c87a8ba402">propagateShapeBackward</a>, <a href="#adf1371d869d3a7468c48401a2a321b26">propagateShapeForward</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>, <a href="#aa6977569e4724e3cb0b65e13d0e2a8eb">VisitBinaryOperator</a>, <a href="#a4abe522bf135a7628b059cf5fc0be127">VisitCallInst</a>, <a href="#a49e11eb7774b75fb97d50d78ed1de951">VisitLoad</a>, <a href="#ae35d90f9a44c556c4a984b1fd6fae199">VisitStore</a> and <a href="#a851ca1290a8ae078a9e084871aa2e9d7">VisitUnaryOperator</a>.</p>

</div>
</div>

### VisitBinaryOperator() {#aa6977569e4724e3cb0b65e13d0e2a8eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::VisitBinaryOperator (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * Inst)</td>
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

<p>Lower binary operators, if shape information is available.</p>

<p>Definition at line 2127 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a395795410abf1a79bdb31fdcd955e286">llvm::IRBuilderBase::CreateFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae33cfb24f8bc0f6aa80c3a49e3769f6d">llvm::IRBuilderBase::CreateFMul</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a14c7156dcfce46bd2b9542daee95d9c1">llvm::IRBuilderBase::CreateFSub</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aecd40f9a16dc0ef1e0bc416599f89277">llvm::IRBuilderBase::CreateMul</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a92c83e803f2cf22906da0aaec44ff6d7">llvm::IRBuilderBase::CreateSub</a>, <a href="#a7f5b1f0925dc2dbb62f05681772ca912">finalizeLowering</a>, <a href="#aad5def33faf75944be159808071d9698">getMatrix</a>, <a href="#af44a0d4c944c50fe30fad03d97e9f66f">getNumOps</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6370e29617c71c8081bbbc68d6058403">llvm::IRBuilderBase::setFastMathFlags</a>.</p>


<p>Referenced by <a href="#a49a46654ca2c32ce99be52de089052f8">Visit</a>.</p>

</div>
</div>

### VisitCallInst() {#a4abe522bf135a7628b059cf5fc0be127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::VisitCallInst (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * Inst)</td>
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

<p>Replace intrinsic calls.</p>

<p>Definition at line 1106 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4d0a7baab8d078065b2de10e3460892a">llvm::Function::getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a900a32da3983469187b1848189681705">llvm::Function::isIntrinsic</a>, <a href="#a237ac9d59f45a0b7c18296704e005a6c">LowerColumnMajorLoad</a>, <a href="#a4c72146be47366faa66bbe3fa93abf2a">LowerColumnMajorStore</a>, <a href="#a6d7b7ecce18021429495c1db66a025ee">LowerMultiply</a> and <a href="#aadb2a52a94fd7cf1e3f1643e0f5e2934">LowerTranspose</a>.</p>


<p>Referenced by <a href="#a49a46654ca2c32ce99be52de089052f8">Visit</a>.</p>

</div>
</div>

### VisitLoad() {#a49e11eb7774b75fb97d50d78ed1de951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::VisitLoad (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * Inst, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder)</td>
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

<p>Lower load instructions, if shape information is available.</p>

<p>Definition at line 2103 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loadinst/#af51c113a039c82f6870df5dc9666b5e3">llvm::LoadInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73f286a780fbb8c82c0a8574540719ea">llvm::IRBuilderBase::getInt64</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2eccc19f9061eeb7ad1e30e21f76034d">llvm::LoadInst::isVolatile</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a47413709ef916baf36607da462d93ccc">LowerLoad</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#a49a46654ca2c32ce99be52de089052f8">Visit</a>.</p>

</div>
</div>

### VisitStore() {#ae35d90f9a44c556c4a984b1fd6fae199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::VisitStore (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * Inst, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * StoredVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder)</td>
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



<p>Definition at line 2114 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/storeinst/#a3b47950858d6ed72efd1010a35b81caa">llvm::StoreInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73f286a780fbb8c82c0a8574540719ea">llvm::IRBuilderBase::getInt64</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#ae3098a2ed52ddc6b853a3006ea646b7e">llvm::StoreInst::isVolatile</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a05914158f39e230548b1b743eee2e5f6">LowerStore</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#a49a46654ca2c32ce99be52de089052f8">Visit</a>.</p>

</div>
</div>

### VisitUnaryOperator() {#a851ca1290a8ae078a9e084871aa2e9d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::VisitUnaryOperator (<a href="/web-llvm/docs/api/classes/llvm/unaryoperator">UnaryOperator</a> * Inst)</td>
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

<p>Lower unary operators, if shape information is available.</p>

<p>Definition at line 2178 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae44006b91094939f6ea72655e8312504">llvm::IRBuilderBase::CreateFNeg</a>, <a href="#a7f5b1f0925dc2dbb62f05681772ca912">finalizeLowering</a>, <a href="#aad5def33faf75944be159808071d9698">getMatrix</a>, <a href="#af44a0d4c944c50fe30fad03d97e9f66f">getNumOps</a>, <a href="/web-llvm/docs/api/classes/llvm/unaryoperator/#a7cece7ddf076c1dccc81f743e3b7bd36">llvm::UnaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6370e29617c71c8081bbbc68d6058403">llvm::IRBuilderBase::setFastMathFlags</a>.</p>


<p>Referenced by <a href="#a49a46654ca2c32ce99be52de089052f8">Visit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a87f782c71abaeba81e931fe09f0f1e75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasAnalysis* anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::AA = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>

</div>
</div>

### AM {#a2f1ed500d85d49ed48bc749ae9ad2ee2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAnalysisManager* anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::AM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>

</div>
</div>

### DL {#aeea840b9eda5b2219baff5a17d112507}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>

</div>
</div>

### DT {#a9e392a8f54c9ac71adec3ef9081444a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::DT = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>

</div>
</div>

### Func {#ad6dacd24677f234d2f1849a8ae1de0ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::Func</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>

</div>
</div>

### Inst2ColumnMatrix {#a9a9c27b7faf686491eaeeb56c5f9cce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;Value *, MatrixTy&gt; anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::Inst2ColumnMatrix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from instructions to their produced column matrix.</p>

<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>

</div>
</div>

### LI {#ae52578f9fcc9152060dd884fc8482d17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>

</div>
</div>

### ORE {#accf064712b3ba2991d1fc9790bf3eba2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter* anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::ORE = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>

</div>
</div>

### ShapeMap {#a6a8d00ede246fcdc5c5b4d89489ef960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, ShapeInfo&gt; anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::ShapeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps instructions to their shape information.</p>


<p>The shape information describes the shape to be used while lowering. This matches the shape of the result value of the instruction, with the only exceptions being store instructions and the matrix_column_major_store intrinsics. For those, the shape information indicates that those instructions should be lowered using shape information as well. Note that extra care is needed when erasing or RAUW'ing a value that is present in ShapeMap. If the replacement is also a matrix operation, use updateShapeAndReplaceAllUsesWith to make sure the replacement is added to ShapeMap. We don't use <a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a>, as there are also cases where we do not want to add shape information for a replacement instruction. When directly erasing a value with an entry in ShapeMap, use eraseFromParentAndRemoveFromShapeMap to make sure ShapeMap is also updated accordingly.</p>


<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>

</div>
</div>

### ToRemove {#a56f516dfbddab41939051b0bc1e244d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *, 16&gt; anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::ToRemove</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of instructions to remove.</p>


<p>While lowering, we are not replacing all users of a lowered instruction, if shape information is available and those need to be removed after we finished lowering.</p>


<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>

</div>
</div>

### TTI {#a756f227274ae71540b93f77e12bcef9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetTransformInfo&amp; anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getFastMathFlags() {#af90d0cc1bdb2afda617c972591f1e7d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastMathFlags anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getFastMathFlags (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
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



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
