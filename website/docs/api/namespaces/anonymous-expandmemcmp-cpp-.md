---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-expandmemcmp-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{ExpandMemCmp.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{ExpandMemCmp.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-expandmemcmp-cpp-/memcmpexpansion">MemCmpExpansion</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-expandmemcmp-cpp-/expandmemcmplegacypass">ExpandMemCmpLegacyPass</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa507b512719f5e8d2b31c99f5534541b">expandMemCmp</a> (CallInst *CI, const TargetTransformInfo *TTI, const TargetLowering *TLI, const DataLayout *DL, ProfileSummaryInfo *PSI, BlockFrequencyInfo *BFI, DomTreeUpdater *DTU, const bool IsBCmp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We want to transform: call = call signext i32 @memcmp(i8* %0, i8* %1, i64 15) To: loadbb: %0 = bitcast i32* buffer2 to i8* %1 = bitcast i32* buffer1 to i8* %2 = bitcast i8* %1 to i64* %3 = bitcast i8* %0 to i64* %4 = load i64, i64* %2 %5 = load i64, i64* %3 %6 = call i64 @llvm.bswap.i64(i64 %4) %7 = call i64 @llvm.bswap.i64(i64 %5) %8 = sub i64 %6, %7 %9 = icmp ne i64 %8, 0 br i1 %9, label res_block, label loadbb1 res_block: ; preds = loadbb2, loadbb1, loadbb phi.src1 = phi i64 [ %6, loadbb ], [ %22, loadbb1 ], [ %36, loadbb2 ] phi.src2 = phi i64 [ %7, loadbb ], [ %23, loadbb1 ], [ %37, loadbb2 ] %10 = icmp ult i64 phi.src1, phi.src2 %11 = select i1 %10, i32 -1, i32 1 br label endblock loadbb1: ; preds = loadbb %12 = bitcast i32* buffer2 to i8* %13 = bitcast i32* buffer1 to i8* %14 = bitcast i8* %13 to i32* %15 = bitcast i8* %12 to i32* %16 = getelementptr i32, i32* %14, i32 2 %17 = getelementptr i32, i32* %15, i32 2 %18 = load i32, i32* %16 %19 = load i32, i32* %17 %20 = call i32 @llvm.bswap.i32(i32 %18) %21 = call i32 @llvm.bswap.i32(i32 %19) %22 = zext i32 %20 to i64 %23 = zext i32 %21 to i64 %24 = sub i64 %22, %23 %25 = icmp ne i64 %24, 0 br i1 %25, label res_block, label loadbb2 loadbb2: ; preds = loadbb1 %26 = bitcast i32* buffer2 to i8* %27 = bitcast i32* buffer1 to i8* %28 = bitcast i8* %27 to i16* %29 = bitcast i8* %26 to i16* %30 = getelementptr i16, i16* %28, i16 6 %31 = getelementptr i16, i16* %29, i16 6 %32 = load i16, i16* %30 %33 = load i16, i16* %31 %34 = call i16 @llvm.bswap.i16(i16 %32) %35 = call i16 @llvm.bswap.i16(i16 %33) %36 = zext i16 %34 to i64 %37 = zext i16 %35 to i64 %38 = sub i64 %36, %37 %39 = icmp ne i64 %38, 0 br i1 %39, label res_block, label loadbb3 loadbb3: ; preds = loadbb2 %40 = bitcast i32* buffer2 to i8* %41 = bitcast i32* buffer1 to i8* %42 = getelementptr i8, i8* %41, i8 14 %43 = getelementptr i8, i8* %40, i8 14 %44 = load i8, i8* %42 %45 = load i8, i8* %43 %46 = zext i8 %44 to i32 %47 = zext i8 %45 to i32 %48 = sub i32 %46, %47 br label endblock endblock: ; preds = res_block, loadbb3 phi.res = phi i32 [ %48, loadbb3 ], [ %11, res_block ] ret i32 phi.res. <a href="#aa507b512719f5e8d2b31c99f5534541b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8309872ede007a47eebce4974ab341c">runOnBlock</a> (BasicBlock &amp;BB, const TargetLibraryInfo *TLI, const TargetTransformInfo *TTI, const TargetLowering *TL, const DataLayout &amp;DL, ProfileSummaryInfo *PSI, BlockFrequencyInfo *BFI, DomTreeUpdater *DTU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ed6e9933878fa5790bdacff6d5a907b">runImpl</a> (Function &amp;F, const TargetLibraryInfo *TLI, const TargetTransformInfo *TTI, const TargetLowering *TL, ProfileSummaryInfo *PSI, BlockFrequencyInfo *BFI, DominatorTree *DT)</td>
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


<div class="doxySectionDef">

## Functions

### expandMemCmp() {#aa507b512719f5e8d2b31c99f5534541b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ExpandMemCmp.cpp}::expandMemCmp (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> * DL, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> * DTU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool IsBCmp)</td>
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

<p>We want to transform: call = call signext i32 @memcmp(i8* %0, i8* %1, i64 15) To: loadbb: %0 = bitcast i32* buffer2 to i8* %1 = bitcast i32* buffer1 to i8* %2 = bitcast i8* %1 to i64* %3 = bitcast i8* %0 to i64* %4 = load i64, i64* %2 %5 = load i64, i64* %3 %6 = call i64 @llvm.bswap.i64(i64 %4) %7 = call i64 @llvm.bswap.i64(i64 %5) %8 = sub i64 %6, %7 %9 = icmp ne i64 %8, 0 br i1 %9, label res_block, label loadbb1 res_block: ; preds = loadbb2, loadbb1, loadbb phi.src1 = phi i64 [ %6, loadbb ], [ %22, loadbb1 ], [ %36, loadbb2 ] phi.src2 = phi i64 [ %7, loadbb ], [ %23, loadbb1 ], [ %37, loadbb2 ] %10 = icmp ult i64 phi.src1, phi.src2 %11 = select i1 %10, i32 -1, i32 1 br label endblock loadbb1: ; preds = loadbb %12 = bitcast i32* buffer2 to i8* %13 = bitcast i32* buffer1 to i8* %14 = bitcast i8* %13 to i32* %15 = bitcast i8* %12 to i32* %16 = getelementptr i32, i32* %14, i32 2 %17 = getelementptr i32, i32* %15, i32 2 %18 = load i32, i32* %16 %19 = load i32, i32* %17 %20 = call i32 @llvm.bswap.i32(i32 %18) %21 = call i32 @llvm.bswap.i32(i32 %19) %22 = zext i32 %20 to i64 %23 = zext i32 %21 to i64 %24 = sub i64 %22, %23 %25 = icmp ne i64 %24, 0 br i1 %25, label res_block, label loadbb2 loadbb2: ; preds = loadbb1 %26 = bitcast i32* buffer2 to i8* %27 = bitcast i32* buffer1 to i8* %28 = bitcast i8* %27 to i16* %29 = bitcast i8* %26 to i16* %30 = getelementptr i16, i16* %28, i16 6 %31 = getelementptr i16, i16* %29, i16 6 %32 = load i16, i16* %30 %33 = load i16, i16* %31 %34 = call i16 @llvm.bswap.i16(i16 %32) %35 = call i16 @llvm.bswap.i16(i16 %33) %36 = zext i16 %34 to i64 %37 = zext i16 %35 to i64 %38 = sub i64 %36, %37 %39 = icmp ne i64 %38, 0 br i1 %39, label res_block, label loadbb3 loadbb3: ; preds = loadbb2 %40 = bitcast i32* buffer2 to i8* %41 = bitcast i32* buffer1 to i8* %42 = getelementptr i8, i8* %41, i8 14 %43 = getelementptr i8, i8* %40, i8 14 %44 = load i8, i8* %42 %45 = load i8, i8* %43 %46 = zext i8 %44 to i32 %47 = zext i8 %45 to i32 %48 = sub i32 %46, %47 br label endblock endblock: ; preds = res_block, loadbb3 phi.res = phi i32 [ %48, loadbb3 ], [ %11, res_block ] ret i32 phi.res.</p>

<p>Definition at line 830 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandmemcmp-cpp">ExpandMemCmp.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a085f53470d0661bff051248317d06cd6">Expansion</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#ac09a21c371a9c535cbc13e8f82503aec">llvm::ConstantInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a548cfb9440f36ba67fc5566b8e967fc6">llvm::Function::hasMinSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c4687f9c44e149d4893bd81b7ddce3b">llvm::isOnlyUsedInZeroEqualityComparison</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandmemcmp-cpp/#a51790d9628455ee57b760bde7bd6fd8c">MaxLoadsPerMemcmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandmemcmp-cpp/#a1ad14dfca7a03c8e70aa21a325592025">MaxLoadsPerMemcmpOptSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandmemcmp-cpp/#a750c724c24f5a348d38e97c930193499">MemCmpEqZeroNumLoadsPerBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3af72f14ea20f2c762c751d2d49e5ea3">llvm::shouldOptimizeForSize</a>.</p>


<p>Referenced by <a href="#ab8309872ede007a47eebce4974ab341c">runOnBlock</a>.</p>

</div>
</div>

### runImpl() {#a1ed6e9933878fa5790bdacff6d5a907b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses anonymous{ExpandMemCmp.cpp}::runImpl (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> * TL, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
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



<p>Definition at line 964 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandmemcmp-cpp">ExpandMemCmp.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ab8309872ede007a47eebce4974ab341c">runOnBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a42108fe3c2695cb429e6fe312908fa0d">llvm::SimplifyInstructionsInBlock</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-expandmemcmp-cpp-/expandmemcmplegacypass/#a744c97bd2b03802d78ec941f5c7b9d16">anonymous{ExpandMemCmp.cpp}::ExpandMemCmpLegacyPass::runOnFunction</a>.</p>

</div>
</div>

### runOnBlock() {#ab8309872ede007a47eebce4974ab341c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ExpandMemCmp.cpp}::runOnBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> * TL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> * DTU)</td>
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



<p>Definition at line 945 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandmemcmp-cpp">ExpandMemCmp.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#aa507b512719f5e8d2b31c99f5534541b">expandMemCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a97cfbbed8869e3582142012a071a9052">llvm::TargetLibraryInfo::getLibFunc</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a1ed6e9933878fa5790bdacff6d5a907b">runImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/expandmemcmp-cpp">ExpandMemCmp.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
