---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-vectorcombine-cpp-/vectorcombine
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VectorCombine` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{VectorCombine.cpp}::VectorCombine { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af42fdde83649e9fea3122b691d19fa54">VectorCombine</a> (Function &amp;F, const TargetTransformInfo &amp;TTI, const DominatorTree &amp;DT, AAResults &amp;AA, AssumptionCache &amp;AC, const DataLayout *DL, TTI::TargetCostKind CostKind, bool TryEarlyFoldsOnly)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72026c9724b6de144a788bfb35de1642">run</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the entry point for all transforms. <a href="#a72026c9724b6de144a788bfb35de1642">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38adeea97a607967503cb7f1f309eb33">vectorizeLoadInsert</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77a62d14e3ebb1561628486684bc9f4f">widenSubvectorLoad</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we are loading a vector and then inserting it into a larger vector with undefined elements, try to load the larger vector and eliminate the insert. <a href="#a77a62d14e3ebb1561628486684bc9f4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/extractelementinst">ExtractElementInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a076acec5eb8e5a577e0312c628718b">getShuffleExtract</a> (ExtractElementInst *Ext0, ExtractElementInst *Ext1, unsigned PreferredExtractIndex) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine which, if any, of the inputs should be replaced by a shuffle followed by extract from a different index. <a href="#a3a076acec5eb8e5a577e0312c628718b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9094fe5f9bdd5306a70e2939ecb28630">isExtractExtractCheap</a> (ExtractElementInst *Ext0, ExtractElementInst *Ext1, const Instruction &amp;I, ExtractElementInst *&amp;ConvertToShuffle, unsigned PreferredExtractIndex)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare the relative costs of 2 extracts followed by scalar operation vs. <a href="#a9094fe5f9bdd5306a70e2939ecb28630">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a781c60411491273eafa07c5e0de414c9">foldExtExtCmp</a> (ExtractElementInst *Ext0, ExtractElementInst *Ext1, Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to reduce extract element costs by converting scalar compares to vector compares followed by extract. <a href="#a781c60411491273eafa07c5e0de414c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc6c9ec1b69d7138df20488ef39ba949">foldExtExtBinop</a> (ExtractElementInst *Ext0, ExtractElementInst *Ext1, Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to reduce extract element costs by converting scalar binops to vector binops followed by extract. <a href="#acc6c9ec1b69d7138df20488ef39ba949">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ef87097f7382ae9c2a7502441b33760">foldExtractExtract</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match an instruction with extracted vector operands. <a href="#a5ef87097f7382ae9c2a7502441b33760">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addb03cda40129caee518274dfee2fc33">foldInsExtFNeg</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to replace an extract + scalar fneg + insert with a vector fneg + shuffle. <a href="#addb03cda40129caee518274dfee2fc33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a969f57831317b0b1022f2887cb2e2115">foldInsExtVectorToShuffle</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>insert (DstVec, (extract SrcVec, ExtIdx), InsIdx) --&gt; shuffle (DstVec, SrcVec, Mask) <a href="#a969f57831317b0b1022f2887cb2e2115">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4dbd2bd1a05d3b9960d5a5a260a3390">foldBitcastShuffle</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a bitcast of a shuffle, try to bitcast the source vector to the destination type followed by shuffle. <a href="#ac4dbd2bd1a05d3b9960d5a5a260a3390">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a293fe37b40bf3918d2da556c3cfb013f">scalarizeBinopOrCmp</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match a vector binop or compare instruction with at least one inserted scalar operand and convert to scalar binop/cmp followed by insertelement. <a href="#a293fe37b40bf3918d2da556c3cfb013f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5bb7b28a64c29cc230180a592f9e8d5">scalarizeVPIntrinsic</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VP Intrinsics whose vector operands are both splat values may be simplified into the scalar version of the operation and the result splatted. <a href="#ac5bb7b28a64c29cc230180a592f9e8d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5c1bf9119242530f184c8a6b92b92b8">foldExtractedCmps</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to combine a scalar binop + 2 scalar compares of extracted elements of a vector into vector operations followed by extract. <a href="#ab5c1bf9119242530f184c8a6b92b92b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adce4786d27c1966beb70bd65b01ae2b2">foldSingleElementStore</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86fff2d788edd37f9ba0629a7217b04e">scalarizeLoadExtract</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to scalarize vector loads feeding extractelement instructions. <a href="#a86fff2d788edd37f9ba0629a7217b04e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcddbe46742d0b648c69f829ecbffce0">foldConcatOfBoolMasks</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to fold "(or (zext (bitcast X)), (shl (zext (bitcast Y)), C))" to "(bitcast (concat X, Y))" where X/Y are bitcasted from i1 mask vectors. <a href="#adcddbe46742d0b648c69f829ecbffce0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29849e0d6bfbca896837faa2c71640d0">foldPermuteOfBinops</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to convert "shuffle (binop (shuffle, shuffle)), undef" --&gt; "binop (shuffle), (shuffle)". <a href="#a29849e0d6bfbca896837faa2c71640d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a382b91de59f68c1b5e589fc705feaed8">foldShuffleOfBinops</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to convert "shuffle (binop), (binop)" into "binop (shuffle), (shuffle)". <a href="#a382b91de59f68c1b5e589fc705feaed8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fcfd40343d001e0564c27f6cef6f1f6">foldShuffleOfCastops</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to convert "shuffle (castop), (castop)" with a shared castop operand into "castop (shuffle)". <a href="#a1fcfd40343d001e0564c27f6cef6f1f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ebf659d7bd1831a388edf34050b0055">foldShuffleOfShuffles</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to convert any of: "shuffle (shuffle x, y), (shuffle y, x)" "shuffle (shuffle x, undef), (shuffle y, undef)" "shuffle (shuffle x, undef), y" "shuffle x, (shuffle y, undef)" into "shuffle x, y". <a href="#a0ebf659d7bd1831a388edf34050b0055">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeb9524045958fbd2978a1f4e7483513">foldShuffleOfIntrinsics</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to convert "shuffle (intrinsic), (intrinsic)" into "intrinsic (shuffle), (shuffle)". <a href="#afeb9524045958fbd2978a1f4e7483513">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac30405f43b6227bf3a140d5574ab1c2d">foldShuffleToIdentity</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92a1ee1e167587efe0221073af07b842">foldShuffleFromReductions</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a commutative reduction, the order of the input lanes does not alter the results. <a href="#a92a1ee1e167587efe0221073af07b842">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad81e1c39051bd6205c85dc4fde1b1bcb">foldCastFromReductions</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if its more efficient to fold: <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a6d827fc34f1b4371a0b7183d3ca5bcac">reduce(trunc(x))</a> -&gt; trunc(reduce(x)). <a href="#ad81e1c39051bd6205c85dc4fde1b1bcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a677c8593b8bac0375c5103296157e132">foldSelectShuffle</a> (Instruction &amp;I, bool FromReduction=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method looks for groups of shuffles acting on binops, of the form: x = shuffle ... y = shuffle ... a = binop x, y b = binop x, y shuffle a, b, selectmask We may, especially if the shuffle is wider than legal, be able to convert the shuffle to a form where only parts of a and b need to be computed. <a href="#a677c8593b8bac0375c5103296157e132">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37161c0307410e3c67bbca148756c039">shrinkType</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if instruction depends on ZExt and this ZExt can be moved after the instruction. <a href="#a37161c0307410e3c67bbca148756c039">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab329053cbdf161a6aeb628e0f604d842">replaceValue</a> (Value &amp;Old, Value &amp;New)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7641ed3f636b8199715561ac85d5a467">eraseInstruction</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0be67aae39318544352d6f27e794225">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a941cdd2cd4957e5d60c17807518bf0ba">Builder</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74a6b5fbb66c61103f989dc7afb3c219">TTI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addc4d97da4f076c7f791b9b1eaca44d8">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a240fde8d62f16480acbac3a8b1041447">AA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1c2e109f2b0f8bf9c99e91effd6c314">AC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a9220a292918c1a11f0b95880aaea7d">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2633360d200b9c4d68e39861d49b3817">CostKind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eda4e8641a59a32d0f0628e0c890960">TryEarlyFoldsOnly</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If true, only perform beneficial early IR transforms. <a href="#a5eda4e8641a59a32d0f0628e0c890960">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructionworklist">InstructionWorklist</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd6deaf09c48e15368e889ac014d34b5">Worklist</a></td>
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


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VectorCombine() {#af42fdde83649e9fea3122b691d19fa54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{VectorCombine.cpp}::VectorCombine::VectorCombine (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp; AA, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> * DL, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, bool TryEarlyFoldsOnly)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a72026c9724b6de144a788bfb35de1642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the entry point for all transforms.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> manager differences are handled in the callers of this function.</p>


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#a64031271d3f937bf5b936488adb55307">DisableVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5c88132322ca3f46f242f7c023a57010">llvm::Instruction::isBinaryOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a627b2f86ac433d829482d5a5a0f50668">llvm::isInstructionTriviallyDead</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### eraseInstruction() {#a7641ed3f636b8199715561ac85d5a467}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{VectorCombine.cpp}::VectorCombine::eraseInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### foldBitcastShuffle() {#ac4dbd2bd1a05d3b9960d5a5a260a3390}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::foldBitcastShuffle (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is a bitcast of a shuffle, try to bitcast the source vector to the destination type followed by shuffle.</p>


<p>This can enable further transforms by moving bitcasts or shuffles together.</p>


<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### foldCastFromReductions() {#ad81e1c39051bd6205c85dc4fde1b1bcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::foldCastFromReductions (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if its more efficient to fold: <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a6d827fc34f1b4371a0b7183d3ca5bcac">reduce(trunc(x))</a> -&gt; trunc(reduce(x)).</p>


<p><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a6d827fc34f1b4371a0b7183d3ca5bcac">reduce(sext(x))</a> -&gt; sext(reduce(x)). <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a6d827fc34f1b4371a0b7183d3ca5bcac">reduce(zext(x))</a> -&gt; zext(reduce(x)).</p>


<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### foldConcatOfBoolMasks() {#adcddbe46742d0b648c69f829ecbffce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::foldConcatOfBoolMasks (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to fold "(or (zext (bitcast X)), (shl (zext (bitcast Y)), C))" to "(bitcast (concat X, Y))" where X/Y are bitcasted from i1 mask vectors.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### foldExtExtBinop() {#acc6c9ec1b69d7138df20488ef39ba949}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorCombine::foldExtExtBinop (<a href="/web-llvm/docs/api/classes/llvm/extractelementinst">ExtractElementInst</a> * Ext0, <a href="/web-llvm/docs/api/classes/llvm/extractelementinst">ExtractElementInst</a> * Ext1, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to reduce extract element costs by converting scalar binops to vector binops followed by extract.</p>


<p>bo (ext0 V0, C), (ext1 V1, C)</p>


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### foldExtExtCmp() {#a781c60411491273eafa07c5e0de414c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorCombine::foldExtExtCmp (<a href="/web-llvm/docs/api/classes/llvm/extractelementinst">ExtractElementInst</a> * Ext0, <a href="/web-llvm/docs/api/classes/llvm/extractelementinst">ExtractElementInst</a> * Ext1, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to reduce extract element costs by converting scalar compares to vector compares followed by extract.</p>


<p>cmp (ext0 V0, C), (ext1 V1, C)</p>


<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### foldExtractedCmps() {#ab5c1bf9119242530f184c8a6b92b92b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::foldExtractedCmps (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to combine a scalar binop + 2 scalar compares of extracted elements of a vector into vector operations followed by extract.</p>


<p>Note: The SLP pass may miss this pattern because of implementation problems.</p>


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### foldExtractExtract() {#a5ef87097f7382ae9c2a7502441b33760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::foldExtractExtract (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match an instruction with extracted vector operands.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### foldInsExtFNeg() {#addb03cda40129caee518274dfee2fc33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::foldInsExtFNeg (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to replace an extract + scalar fneg + insert with a vector fneg + shuffle.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### foldInsExtVectorToShuffle() {#a969f57831317b0b1022f2887cb2e2115}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::foldInsExtVectorToShuffle (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>insert (DstVec, (extract SrcVec, ExtIdx), InsIdx) --&gt; shuffle (DstVec, SrcVec, Mask)</p>

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### foldPermuteOfBinops() {#a29849e0d6bfbca896837faa2c71640d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::foldPermuteOfBinops (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to convert "shuffle (binop (shuffle, shuffle)), undef" --&gt; "binop (shuffle), (shuffle)".</p>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### foldSelectShuffle() {#a677c8593b8bac0375c5103296157e132}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::foldSelectShuffle (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, bool FromReduction=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method looks for groups of shuffles acting on binops, of the form: x = shuffle ... y = shuffle ... a = binop x, y b = binop x, y shuffle a, b, selectmask We may, especially if the shuffle is wider than legal, be able to convert the shuffle to a form where only parts of a and b need to be computed.</p>


<p>On architectures with no obvious "select" shuffle, this can reduce the total number of operations if the target reports them as cheaper.</p>


<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### foldShuffleFromReductions() {#a92a1ee1e167587efe0221073af07b842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::foldShuffleFromReductions (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a commutative reduction, the order of the input lanes does not alter the results.</p>


<p>We can use this to remove certain shuffles feeding the reduction, removing the need to shuffle at all.</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### foldShuffleOfBinops() {#a382b91de59f68c1b5e589fc705feaed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::foldShuffleOfBinops (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to convert "shuffle (binop), (binop)" into "binop (shuffle), (shuffle)".</p>


<p>Try to convert "shuffle (cmpop), (cmpop)" into "cmpop (shuffle), (shuffle)".</p>


<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### foldShuffleOfCastops() {#a1fcfd40343d001e0564c27f6cef6f1f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::foldShuffleOfCastops (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to convert "shuffle (castop), (castop)" with a shared castop operand into "castop (shuffle)".</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### foldShuffleOfIntrinsics() {#afeb9524045958fbd2978a1f4e7483513}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::foldShuffleOfIntrinsics (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to convert "shuffle (intrinsic), (intrinsic)" into "intrinsic (shuffle), (shuffle)".</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### foldShuffleOfShuffles() {#a0ebf659d7bd1831a388edf34050b0055}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::foldShuffleOfShuffles (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to convert any of: "shuffle (shuffle x, y), (shuffle y, x)" "shuffle (shuffle x, undef), (shuffle y, undef)" "shuffle (shuffle x, undef), y" "shuffle x, (shuffle y, undef)" into "shuffle x, y".</p>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### foldShuffleToIdentity() {#ac30405f43b6227bf3a140d5574ab1c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::foldShuffleToIdentity (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### foldSingleElementStore() {#adce4786d27c1966beb70bd65b01ae2b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::foldSingleElementStore (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### getShuffleExtract() {#a3a076acec5eb8e5a577e0312c628718b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExtractElementInst * VectorCombine::getShuffleExtract (<a href="/web-llvm/docs/api/classes/llvm/extractelementinst">ExtractElementInst</a> * Ext0, <a href="/web-llvm/docs/api/classes/llvm/extractelementinst">ExtractElementInst</a> * Ext1, unsigned PreferredExtractIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine which, if any, of the inputs should be replaced by a shuffle followed by extract from a different index.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### isExtractExtractCheap() {#a9094fe5f9bdd5306a70e2939ecb28630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::isExtractExtractCheap (<a href="/web-llvm/docs/api/classes/llvm/extractelementinst">ExtractElementInst</a> * Ext0, <a href="/web-llvm/docs/api/classes/llvm/extractelementinst">ExtractElementInst</a> * Ext1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/extractelementinst">ExtractElementInst</a> *&amp; ConvertToShuffle, unsigned PreferredExtractIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compare the relative costs of 2 extracts followed by scalar operation vs.</p>


<p>vector operation(s) followed by extract. Return true if the existing instructions are cheaper than a vector alternative. Otherwise, return false and if one of the extracts should be transformed to a shufflevector, set <span class="doxyComputerOutput">ConvertToShuffle</span> to that extract instruction.</p>


<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### replaceValue() {#ab329053cbdf161a6aeb628e0f604d842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{VectorCombine.cpp}::VectorCombine::replaceValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; Old, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; New)</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### scalarizeBinopOrCmp() {#a293fe37b40bf3918d2da556c3cfb013f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::scalarizeBinopOrCmp (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match a vector binop or compare instruction with at least one inserted scalar operand and convert to scalar binop/cmp followed by insertelement.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### scalarizeLoadExtract() {#a86fff2d788edd37f9ba0629a7217b04e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::scalarizeLoadExtract (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to scalarize vector loads feeding extractelement instructions.</p>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### scalarizeVPIntrinsic() {#ac5bb7b28a64c29cc230180a592f9e8d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::scalarizeVPIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>VP Intrinsics whose vector operands are both splat values may be simplified into the scalar version of the operation and the result splatted.</p>


<p>This can lead to scalarization down the line.</p>


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### shrinkType() {#a37161c0307410e3c67bbca148756c039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::shrinkType (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if instruction depends on ZExt and this ZExt can be moved after the instruction.</p>


<p>Move ZExt if it is profitable. For example: logic(zext(x),y) -&gt; zext(logic(x,trunc(y))) lshr((zext(x),y) -&gt; zext(lshr(x,trunc(y))) <a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a> model calculations takes into account if zext(x) has other users and whether it can be propagated through them too.</p>


<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### vectorizeLoadInsert() {#a38adeea97a607967503cb7f1f309eb33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::vectorizeLoadInsert (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### widenSubvectorLoad() {#a77a62d14e3ebb1561628486684bc9f4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorCombine::widenSubvectorLoad (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If we are loading a vector and then inserting it into a larger vector with undefined elements, try to load the larger vector and eliminate the insert.</p>


<p>This removes a shuffle in IR and may allow combining of other loaded values.</p>


<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a240fde8d62f16480acbac3a8b1041447}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAResults&amp; anonymous{VectorCombine.cpp}::VectorCombine::AA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### AC {#ae1c2e109f2b0f8bf9c99e91effd6c314}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache&amp; anonymous{VectorCombine.cpp}::VectorCombine::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### Builder {#a941cdd2cd4957e5d60c17807518bf0ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRBuilder anonymous{VectorCombine.cpp}::VectorCombine::Builder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### CostKind {#a2633360d200b9c4d68e39861d49b3817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TTI::TargetCostKind anonymous{VectorCombine.cpp}::VectorCombine::CostKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### DL {#a9a9220a292918c1a11f0b95880aaea7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout* anonymous{VectorCombine.cpp}::VectorCombine::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### DT {#addc4d97da4f076c7f791b9b1eaca44d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DominatorTree&amp; anonymous{VectorCombine.cpp}::VectorCombine::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### F {#ab0be67aae39318544352d6f27e794225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{VectorCombine.cpp}::VectorCombine::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### TryEarlyFoldsOnly {#a5eda4e8641a59a32d0f0628e0c890960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{VectorCombine.cpp}::VectorCombine::TryEarlyFoldsOnly</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If true, only perform beneficial early IR transforms.</p>


<p>Do not introduce new vector operations.</p>


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### TTI {#a74a6b5fbb66c61103f989dc7afb3c219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetTransformInfo&amp; anonymous{VectorCombine.cpp}::VectorCombine::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

### Worklist {#afd6deaf09c48e15368e889ac014d34b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionWorklist anonymous{VectorCombine.cpp}::VectorCombine::Worklist</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp">VectorCombine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
