---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/expandlargefpconvert-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ExpandLargeFpConvert.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/expandlargefpconvert-h">llvm/CodeGen/ExpandLargeFpConvert.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/globalsmodref-h">llvm/Analysis/GlobalsModRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/institerator-h">llvm/IR/InstIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-expandlargefpconvert-cpp-">anonymous{ExpandLargeFpConvert.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-expandlargefpconvert-cpp-/expandlargefpconvertlegacypass">ExpandLargeFpConvertLegacyPass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46482b2bd77de78d901bfa2fd727ba0e">expandFPToI</a> (Instruction *FPToI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate code to convert a fp number to integer, replacing FPToS(U)I with the generated code. <a href="#a46482b2bd77de78d901bfa2fd727ba0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a> (Instruction *IToFP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate code to convert a fp number to integer, replacing S(U)IToFP with the generated code. <a href="#a0f218e3451638c34910744dedf0b71ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b532a3420c46c6194f80f8590cd7689">scalarize</a> (Instruction *I, SmallVectorImpl&lt; Instruction * &gt; &amp;Replace)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae64f9cd0977a8b47570154312540d7d2">runImpl</a> (Function &amp;F, const TargetLowering &amp;TLI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a429bb78bde2f539cf5e6aef5a20819d0">INITIALIZE_PASS_BEGIN</a> (ExpandLargeFpConvertLegacyPass, "expand-large-fp-convert", "Expand large fp convert", false, false) INITIALIZE_PASS_END(ExpandLargeFpConvertLegacyPass</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa438561cf6560f4404be1eae7a98d76a">ExpandFpConvertBits</a>("expand-fp-convert-bits", cl::Hidden, cl::init(llvm::IntegerType::MAX_INT_BITS), cl::desc("fp convert instructions on integers with " "more than <N> bits are expanded."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp/#a80bc10e949d0743241f5cdc2c75de52a">expand</a> large fp</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ede31e560f002894d3cafea50fc7a42">convert</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp/#a80bc10e949d0743241f5cdc2c75de52a">expand</a> large fp Expand large fp</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a6e582689eec1f0144e1983e41054fb">false</a></td>
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

### expandFPToI() {#a46482b2bd77de78d901bfa2fd727ba0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void expandFPToI (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * FPToI)</td>
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

<p>Generate code to convert a fp number to integer, replacing FPToS(U)I with the generated code.</p>


<p>This currently generates code similarly to compiler-rt's implementations.</p>


<p>An example IR generated from compiler-rt/fixsfdi.c looks like below: define dso_local i64 @foo(float noundef a) local_unnamed_addr #0 { entry: %0 = bitcast float a to i32 conv.i = zext i32 %0 to i64 tobool.not = icmp sgt i32 %0, -1 conv = select i1 tobool.not, i64 1, i64 -1 and = lshr i64 conv.i, 23 shr = and i64 and, 255 and2 = and i64 conv.i, 8388607 or = or i64 and2, 8388608 cmp = icmp ult i64 shr, 127 br i1 cmp, label cleanup, label if.end</p>


<p>if.end: ; preds = entry sub = add nuw nsw i64 shr, 4294967169 conv5 = and i64 sub, 4294967232 cmp6.not = icmp eq i64 conv5, 0 br i1 cmp6.not, label if.end12, label if.then8</p>


<p>if.then8: ; preds = if.end cond11 = select i1 tobool.not, i64 9223372036854775807, i64 -9223372036854775808 br label cleanup</p>


<p>if.end12: ; preds = if.end cmp13 = icmp ult i64 shr, 150 br i1 cmp13, label if.then15, label if.else</p>


<p>if.then15: ; preds = if.end12 sub16 = sub nuw nsw i64 150, shr shr17 = lshr i64 or, sub16 mul = mul nsw i64 shr17, conv br label cleanup</p>


<p>if.else: ; preds = if.end12 sub18 = add nsw i64 shr, -150 shl = shl i64 or, sub18 mul19 = mul nsw i64 shl, conv br label cleanup</p>


<p>cleanup: ; preds = entry, if.else, if.then15, if.then8 retval.0 = phi i64 [ cond11, if.then8 ], [ mul, if.then15 ], [ mul19, if.else ], [ 0, entry ] ret i64 retval.0 }</p>


<p>Replace fp to integer with generated code.</p>


<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp">ExpandLargeFpConvert.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#abab736a0141f903dc32a6f48828ad908">llvm::IRBuilderBase::CreateBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a972c30f044db799668bdcace5544edeb">llvm::IRBuilderBase::CreateCondBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ada6d23e9d77acfc618b36af461204d2c">llvm::IRBuilderBase::CreateFPExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#afd0b5a07710757874fa84076969537b0">llvm::IRBuilderBase::CreateFPToSI</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4cac1c8f9a62a9d1079e4d0499bbb848">llvm::IRBuilderBase::CreateFPToUI</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3280551f1232a760cb7b21e85fdd5eca">llvm::IRBuilderBase::CreateICmpSGT</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a09b4daefdf5b73efba51ce7ae6cd45c5">llvm::IRBuilderBase::CreateICmpULT</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aecd40f9a16dc0ef1e0bc416599f89277">llvm::IRBuilderBase::CreateMul</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a876fb556ecea804faa2cd8ad1e498ec3">llvm::IRBuilderBase::CreatePHI</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b6a3be6451cf6a789d9305d90751c40">llvm::IRBuilderBase::CreateShl</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a92c83e803f2cf22906da0aaec44ff6d7">llvm::IRBuilderBase::CreateSub</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#add2225af2af25968f26ed4cb0db94dbe">llvm::IRBuilderBase::CreateXor</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a48ec5fcee6d2c17c723e8e67f169f948">llvm::User::dropAllReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa2ed385be8984b4306762990278eb13d">llvm::IRBuilderBase::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a49f37835a410e050b960dd936a54dd05">llvm::Type::getFP128Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a60a6d6c205f483fa96597a960f3c093b">llvm::IRBuilderBase::GetInsertBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4e5c1b91bf5e2860398e3fa35c96b5af">llvm::IRBuilderBase::GetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a13e877ef779ba7a0688081079f4f9b03">llvm::Type::getIntegerBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a95df4f20c933779306b9a936b88b99a5">llvm::IRBuilderBase::getIntN</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a31e2db8d1b315202d2c19e711b5365fd">llvm::IRBuilderBase::getIntNTy</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a9ad53d2a00a6fb861b3a048c6592b742">llvm::ConstantInt::getSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#ae0f503db91504a3f3440ab81260e4134">Mul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5542d44947f8d964b5ce3b20ea719b44">llvm::PowerOf2Ceil</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>.</p>


<p>Referenced by <a href="#ae64f9cd0977a8b47570154312540d7d2">runImpl</a>.</p>

</div>
</div>

### expandIToFP() {#a0f218e3451638c34910744dedf0b71ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void expandIToFP (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IToFP)</td>
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

<p>Generate code to convert a fp number to integer, replacing S(U)IToFP with the generated code.</p>


<p>This currently generates code similarly to compiler-rt's implementations. This implementation has an implicit assumption that integer width is larger than fp.</p>


<p>An example IR generated from compiler-rt/floatdisf.c looks like below: define dso_local float @__floatdisf(i64 noundef a) local_unnamed_addr #0 { entry: cmp = icmp eq i64 a, 0 br i1 cmp, label return, label if.end</p>


<p>if.end: ; preds = entry shr = ashr i64 a, 63 xor = xor i64 shr, a sub = sub nsw i64 xor, shr %0 = tail call i64 @llvm.ctlz.i64(i64 sub, i1 true), !range !5 cast = trunc i64 %0 to i32 sub1 = sub nuw nsw i32 64, cast sub2 = xor i32 cast, 63 cmp3 = icmp ult i32 cast, 40 br i1 cmp3, label if.then4, label if.else</p>


<p>if.then4: ; preds = if.end switch i32 sub1, label sw.default [ i32 25, label sw.bb i32 26, label sw.epilog ]</p>


<p>sw.bb: ; preds = if.then4 shl = shl i64 sub, 1 br label sw.epilog</p>


<p>sw.default: ; preds = if.then4 sub5 = sub nsw i64 38, %0 sh_prom = and i64 sub5, 4294967295 shr6 = lshr i64 sub, sh_prom shr9 = lshr i64 274877906943, %0 and = and i64 shr9, sub cmp10 = icmp ne i64 and, 0 conv11 = zext i1 cmp10 to i64 or = or i64 shr6, conv11 br label sw.epilog</p>


<p>sw.epilog: ; preds = sw.default, if.then4, sw.bb a.addr.0 = phi i64 [ or, sw.default ], [ sub, if.then4 ], [ shl, sw.bb ] %1 = lshr i64 a.addr.0, 2 %2 = and i64 %1, 1 or16 = or i64 %2, a.addr.0 inc = add nsw i64 or16, 1 %3 = and i64 inc, 67108864 tobool.not = icmp eq i64 %3, 0 spec.select.v = select i1 tobool.not, i64 2, i64 3 spec.select = ashr i64 inc, spec.select.v spec.select56 = select i1 tobool.not, i32 sub2, i32 sub1 br label if.end26</p>


<p>if.else: ; preds = if.end sub23 = add nuw nsw i64 %0, 4294967256 sh_prom24 = and i64 sub23, 4294967295 shl25 = shl i64 sub, sh_prom24 br label if.end26</p>


<p>if.end26: ; preds = sw.epilog, if.else a.addr.1 = phi i64 [ shl25, if.else ], [ spec.select, sw.epilog ] e.0 = phi i32 [ sub2, if.else ], [ spec.select56, sw.epilog ] conv27 = trunc i64 shr to i32 and28 = and i32 conv27, -2147483648 add = shl nuw nsw i32 e.0, 23 shl29 = add nuw nsw i32 add, 1065353216 conv31 = trunc i64 a.addr.1 to i32 and32 = and i32 conv31, 8388607 or30 = or i32 and32, and28 or33 = or i32 or30, shl29 %4 = bitcast i32 or33 to float br label return</p>


<p>return: ; preds = entry, if.end26 retval.0 = phi float [ %4, if.end26 ], [ 0.000000e+00, entry ] ret float retval.0 }</p>


<p>Replace integer to fp with generated code.</p>


<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp">ExpandLargeFpConvert.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#adc6a2686b807c18e4a7f7fc58e68d423">llvm::IRBuilderBase::CreateAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#abab736a0141f903dc32a6f48828ad908">llvm::IRBuilderBase::CreateBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a972c30f044db799668bdcace5544edeb">llvm::IRBuilderBase::CreateCondBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3daad285be67a14ff0a10d520966486d">llvm::IRBuilderBase::CreateFPTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8c75539a39f167f352b37ccdd788a7e4">llvm::IRBuilderBase::CreateICmpEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3280551f1232a760cb7b21e85fdd5eca">llvm::IRBuilderBase::CreateICmpSGT</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a876fb556ecea804faa2cd8ad1e498ec3">llvm::IRBuilderBase::CreatePHI</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b6a3be6451cf6a789d9305d90751c40">llvm::IRBuilderBase::CreateShl</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a92c83e803f2cf22906da0aaec44ff6d7">llvm::IRBuilderBase::CreateSub</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8b123015de85b2f41b0deda2aeaad9d3">llvm::IRBuilderBase::CreateSwitch</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#add2225af2af25968f26ed4cb0db94dbe">llvm::IRBuilderBase::CreateXor</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a48ec5fcee6d2c17c723e8e67f169f948">llvm::User::dropAllReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa2ed385be8984b4306762990278eb13d">llvm::IRBuilderBase::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ad5e0fe0efdd88f98a5b5eb512d5351c2">llvm::Type::getFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a49f37835a410e050b960dd936a54dd05">llvm::Type::getFP128Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ad9b99a13e459cb18bb386ddd610ecf8c">llvm::Type::getFPMantissaWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a60a6d6c205f483fa96597a960f3c093b">llvm::IRBuilderBase::GetInsertBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4e5c1b91bf5e2860398e3fa35c96b5af">llvm::IRBuilderBase::GetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64748b5a9f8d8dd4499f84312e2c1336">llvm::IRBuilderBase::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a95df4f20c933779306b9a936b88b99a5">llvm::IRBuilderBase::getIntN</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a31e2db8d1b315202d2c19e711b5365fd">llvm::IRBuilderBase::getIntNTy</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a9ad53d2a00a6fb861b3a048c6592b742">llvm::ConstantInt::getSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a42ce8aa34864a9d974958b9d3d36ad17">llvm::IRBuilderBase::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a75071440d60c24178371ca1299f4ef07">llvm::ConstantFP::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a468e032827ddcd10a8608e08a61323aa">llvm::Type::isBFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa0fd6bf3d33236279db7b707bba755f4">llvm::Type::isDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a8cf1f36cc41c466e66d6467e40554841">llvm::Type::isHalfTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1f68c27188f1836737bf22a62c558354">llvm::Type::isX86_FP80Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5542d44947f8d964b5ce3b20ea719b44">llvm::PowerOf2Ceil</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea76feb79109026728a20736a8c6504548">llvm::Xor</a>.</p>


<p>Referenced by <a href="#ae64f9cd0977a8b47570154312540d7d2">runImpl</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#a429bb78bde2f539cf5e6aef5a20819d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (ExpandLargeFpConvertLegacyPass, "expand-large-fp-convert", "Expand large fp convert", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp">ExpandLargeFpConvert.cpp</a>.</p>

</div>
</div>

### runImpl() {#ae64f9cd0977a8b47570154312540d7d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool runImpl (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI)</td>
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



<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp">ExpandLargeFpConvert.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#aa438561cf6560f4404be1eae7a98d76a">ExpandFpConvertBits</a>, <a href="#a46482b2bd77de78d901bfa2fd727ba0e">expandFPToI</a>, <a href="#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#abcc6b96032604f00666b0b5f2690a604">llvm::TargetLoweringBase::getMaxLargeFPConvertBitWidthSupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a8bb58e9357b2f891f98fbbce353155efa1ccefdf8a7414a6829f888e5071e0379">llvm::IntegerType::MAX_INT_BITS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a0f1c83c3d08d80b12c424962a5e94ce8a35e0c8c0b180c95d4e122e55ed62cc64">Modified</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a6b532a3420c46c6194f80f8590cd7689">scalarize</a>.</p>

</div>
</div>

### scalarize() {#a6b532a3420c46c6194f80f8590cd7689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void scalarize (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; Replace)</td>
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



<p>Definition at line 572 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp">ExpandLargeFpConvert.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5b7f6dddc76bf7954b8df6abbd974436">llvm::IRBuilderBase::CreateCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a303d984774b5c8af8ee4da0aa1960207">llvm::IRBuilderBase::CreateExtractElement</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a17320ebd77e834577a5ebd1063039625">llvm::IRBuilderBase::CreateInsertElement</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#ae64f9cd0977a8b47570154312540d7d2">runImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### convert {#a8ede31e560f002894d3cafea50fc7a42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">expand large fp Expand large fp convert</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp">ExpandLargeFpConvert.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ad69d1c99b0af08146faf9bdf2d9c8709">llvm::APFixedPoint::add</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#acb7a0970dbe748e4fec6bd94d353476c">llvm::APFixedPoint::div</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ad1188d3cd694bbba2756d1b7aaad6e19">llvm::APFixedPoint::mul</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a> and <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a6d9ba22fe2a57b958ba00d8b3382fffd">llvm::APFixedPoint::sub</a>.</p>

</div>
</div>

### ExpandFpConvertBits {#aa438561cf6560f4404be1eae7a98d76a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; ExpandFpConvertBits("expand-fp-convert-bits", cl::Hidden, cl::init(llvm::IntegerType::MAX_INT_BITS), cl::desc("fp convert instructions on integers with " "more than &lt;N&gt; bits are expanded."))</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp">ExpandLargeFpConvert.cpp</a>.</p>


<p>Referenced by <a href="#ae64f9cd0977a8b47570154312540d7d2">runImpl</a>.</p>

</div>
</div>

### false {#a2a6e582689eec1f0144e1983e41054fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">expand large fp Expand large fp false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp">ExpandLargeFpConvert.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
