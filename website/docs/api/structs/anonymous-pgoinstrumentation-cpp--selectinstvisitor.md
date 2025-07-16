---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-pgoinstrumentation-cpp-/selectinstvisitor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SelectInstVisitor` Struct Reference

<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Visitor class to visit select instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{PGOInstrumentation.cpp}::SelectInstVisitor { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed7110706f1b3233aec837c73b516f94">SelectInstVisitor</a> (Function &amp;Func, bool HasSingleByteCoverage)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7197f9b727a3517cc5d550e99fd16900">countSelects</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae22b774b8f200a0f94194f43ad35bb39">instrumentSelects</a> (unsigned *Ind, unsigned TotalNC, GlobalValue *FNV, uint64_t FHash)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb98daec33334e1d5d6921a421f7f4e0">annotateSelects</a> (PGOUseFunc *UF, unsigned *Ind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cf4e2368dd2503ba7992b09322cf97a">instrumentOneSelectInst</a> (SelectInst &amp;SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade04e51ac80ecdf0dd4c549eb91ca684">annotateOneSelectInst</a> (SelectInst &amp;SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8e851387bd5a1484316db9a34cfb477">visitSelectInst</a> (SelectInst &amp;SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71be64e014e7768c007a06eb3591e0bf">getNumOfSelectInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73a7b6c8115fb3cd7df5221c1a9489ef">F</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3298e45a2c2fb5c41ce81d94e5efc86">NSIs</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-pgoinstrumentation-cpp-/#ac08c877d41b736633cb508edd2ae970a">VisitMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b0d4d1c9cf96a8ac50082818f23ab09">Mode</a> = <a href="/web-llvm/docs/api/namespaces/anonymous-pgoinstrumentation-cpp-/#ac08c877d41b736633cb508edd2ae970aaa95eb9f0b68bdf443d603d529a3f9c74">VM_counting</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eafa4048354f47f6caa5bf0df61316c">CurCtrIdx</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a072fc66753199d461e5df2b9c3b2c09b">TotalNumCtrs</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6651382eb33ff1f51c5d0884fd383dcc">FuncNameVar</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae41b1e6922936578adcc5f24cd411725">FuncHash</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/pgousefunc">PGOUseFunc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb866db2a291ff0b10460ee488f846bd">UseFunc</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e3174088be3b57230f54c249ba009c5">HasSingleByteCoverage</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Visitor class to visit select instructions.</p>

<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SelectInstVisitor() {#aed7110706f1b3233aec837c73b516f94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PGOInstrumentation.cpp}::SelectInstVisitor::SelectInstVisitor (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Func, bool HasSingleByteCoverage)</td>
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



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>References <a href="#a73a7b6c8115fb3cd7df5221c1a9489ef">F</a> and <a href="#a4e3174088be3b57230f54c249ba009c5">HasSingleByteCoverage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### annotateOneSelectInst() {#ade04e51ac80ecdf0dd4c549eb91ca684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectInstVisitor::annotateOneSelectInst (<a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> &amp; SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3eafa4048354f47f6caa5bf0df61316c">CurCtrIdx</a>, <a href="#a73a7b6c8115fb3cd7df5221c1a9489ef">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad272ce4631595e235e560baf59dc1ffd">llvm::setProfMetadata</a> and <a href="#aeb866db2a291ff0b10460ee488f846bd">UseFunc</a>.</p>


<p>Referenced by <a href="#ad8e851387bd5a1484316db9a34cfb477">visitSelectInst</a>.</p>

</div>
</div>

### annotateSelects() {#aeb98daec33334e1d5d6921a421f7f4e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PGOInstrumentation.cpp}::SelectInstVisitor::annotateSelects (<a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/pgousefunc">PGOUseFunc</a> * UF, unsigned * Ind)</td>
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



<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>References <a href="#a3eafa4048354f47f6caa5bf0df61316c">CurCtrIdx</a>, <a href="#a73a7b6c8115fb3cd7df5221c1a9489ef">F</a>, <a href="#a5b0d4d1c9cf96a8ac50082818f23ab09">Mode</a>, <a href="#aeb866db2a291ff0b10460ee488f846bd">UseFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#a090736355958192cac4db32336c48bbd">visit</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-pgoinstrumentation-cpp-/#ac08c877d41b736633cb508edd2ae970aa9460c859e26698ee1b200da54c0da797">anonymous{PGOInstrumentation.cpp}::VM_annotate</a>.</p>

</div>
</div>

### countSelects() {#a7197f9b727a3517cc5d550e99fd16900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PGOInstrumentation.cpp}::SelectInstVisitor::countSelects ()</td>
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



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>References <a href="#a73a7b6c8115fb3cd7df5221c1a9489ef">F</a>, <a href="#a5b0d4d1c9cf96a8ac50082818f23ab09">Mode</a>, <a href="#ab3298e45a2c2fb5c41ce81d94e5efc86">NSIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#a090736355958192cac4db32336c48bbd">visit</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-pgoinstrumentation-cpp-/#ac08c877d41b736633cb508edd2ae970aaa95eb9f0b68bdf443d603d529a3f9c74">anonymous{PGOInstrumentation.cpp}::VM_counting</a>.</p>

</div>
</div>

### getNumOfSelectInsts() {#a71be64e014e7768c007a06eb3591e0bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PGOInstrumentation.cpp}::SelectInstVisitor::getNumOfSelectInsts ()</td>
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



<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Reference <a href="#ab3298e45a2c2fb5c41ce81d94e5efc86">NSIs</a>.</p>

</div>
</div>

### instrumentOneSelectInst() {#a0cf4e2368dd2503ba7992b09322cf97a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectInstVisitor::instrumentOneSelectInst (<a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> &amp; SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="#a3eafa4048354f47f6caa5bf0df61316c">CurCtrIdx</a>, <a href="#a73a7b6c8115fb3cd7df5221c1a9489ef">F</a>, <a href="#ae41b1e6922936578adcc5f24cd411725">FuncHash</a>, <a href="#a6651382eb33ff1f51c5d0884fd383dcc">FuncNameVar</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8246a9e9405ffe2a9d8d020a949c8e96">llvm::IRBuilderBase::getInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73f286a780fbb8c82c0a8574540719ea">llvm::IRBuilderBase::getInt64</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64748b5a9f8d8dd4499f84312e2c1336">llvm::IRBuilderBase::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a28bf8984fbfb08fd27df435e631e6832">llvm::ConstantExpr::getPointerBitCastOrAddrSpaceCast</a> and <a href="#a072fc66753199d461e5df2b9c3b2c09b">TotalNumCtrs</a>.</p>


<p>Referenced by <a href="#ad8e851387bd5a1484316db9a34cfb477">visitSelectInst</a>.</p>

</div>
</div>

### instrumentSelects() {#ae22b774b8f200a0f94194f43ad35bb39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PGOInstrumentation.cpp}::SelectInstVisitor::instrumentSelects (unsigned * Ind, unsigned TotalNC, <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * FNV, uint64_t FHash)</td>
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



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>References <a href="#a3eafa4048354f47f6caa5bf0df61316c">CurCtrIdx</a>, <a href="#a73a7b6c8115fb3cd7df5221c1a9489ef">F</a>, <a href="#ae41b1e6922936578adcc5f24cd411725">FuncHash</a>, <a href="#a6651382eb33ff1f51c5d0884fd383dcc">FuncNameVar</a>, <a href="#a5b0d4d1c9cf96a8ac50082818f23ab09">Mode</a>, <a href="#a072fc66753199d461e5df2b9c3b2c09b">TotalNumCtrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#a090736355958192cac4db32336c48bbd">visit</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-pgoinstrumentation-cpp-/#ac08c877d41b736633cb508edd2ae970aaffb32b62adf3065e796714676d015f10">anonymous{PGOInstrumentation.cpp}::VM_instrument</a>.</p>

</div>
</div>

### visitSelectInst() {#ad8e851387bd5a1484316db9a34cfb477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectInstVisitor::visitSelectInst (<a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> &amp; SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>References <a href="#ade04e51ac80ecdf0dd4c549eb91ca684">annotateOneSelectInst</a>, <a href="#a4e3174088be3b57230f54c249ba009c5">HasSingleByteCoverage</a>, <a href="#a0cf4e2368dd2503ba7992b09322cf97a">instrumentOneSelectInst</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a5b0d4d1c9cf96a8ac50082818f23ab09">Mode</a>, <a href="#ab3298e45a2c2fb5c41ce81d94e5efc86">NSIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a5c6c49b0010b25bd9667a936926d6a0e">PGOFunctionEntryCoverage</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a5bf34ba5f02d5ae79dd0d74703eca8cc">PGOInstrSelect</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-pgoinstrumentation-cpp-/#ac08c877d41b736633cb508edd2ae970aa9460c859e26698ee1b200da54c0da797">anonymous{PGOInstrumentation.cpp}::VM_annotate</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-pgoinstrumentation-cpp-/#ac08c877d41b736633cb508edd2ae970aaa95eb9f0b68bdf443d603d529a3f9c74">anonymous{PGOInstrumentation.cpp}::VM_counting</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-pgoinstrumentation-cpp-/#ac08c877d41b736633cb508edd2ae970aaffb32b62adf3065e796714676d015f10">anonymous{PGOInstrumentation.cpp}::VM_instrument</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CurCtrIdx {#a3eafa4048354f47f6caa5bf0df61316c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned* anonymous{PGOInstrumentation.cpp}::SelectInstVisitor::CurCtrIdx = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#ade04e51ac80ecdf0dd4c549eb91ca684">annotateOneSelectInst</a>, <a href="#aeb98daec33334e1d5d6921a421f7f4e0">annotateSelects</a>, <a href="#a0cf4e2368dd2503ba7992b09322cf97a">instrumentOneSelectInst</a> and <a href="#ae22b774b8f200a0f94194f43ad35bb39">instrumentSelects</a>.</p>

</div>
</div>

### F {#a73a7b6c8115fb3cd7df5221c1a9489ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{PGOInstrumentation.cpp}::SelectInstVisitor::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#ade04e51ac80ecdf0dd4c549eb91ca684">annotateOneSelectInst</a>, <a href="#aeb98daec33334e1d5d6921a421f7f4e0">annotateSelects</a>, <a href="#a7197f9b727a3517cc5d550e99fd16900">countSelects</a>, <a href="#a0cf4e2368dd2503ba7992b09322cf97a">instrumentOneSelectInst</a>, <a href="#ae22b774b8f200a0f94194f43ad35bb39">instrumentSelects</a> and <a href="#aed7110706f1b3233aec837c73b516f94">SelectInstVisitor</a>.</p>

</div>
</div>

### FuncHash {#ae41b1e6922936578adcc5f24cd411725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{PGOInstrumentation.cpp}::SelectInstVisitor::FuncHash = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#a0cf4e2368dd2503ba7992b09322cf97a">instrumentOneSelectInst</a> and <a href="#ae22b774b8f200a0f94194f43ad35bb39">instrumentSelects</a>.</p>

</div>
</div>

### FuncNameVar {#a6651382eb33ff1f51c5d0884fd383dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValue* anonymous{PGOInstrumentation.cpp}::SelectInstVisitor::FuncNameVar = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#a0cf4e2368dd2503ba7992b09322cf97a">instrumentOneSelectInst</a> and <a href="#ae22b774b8f200a0f94194f43ad35bb39">instrumentSelects</a>.</p>

</div>
</div>

### HasSingleByteCoverage {#a4e3174088be3b57230f54c249ba009c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PGOInstrumentation.cpp}::SelectInstVisitor::HasSingleByteCoverage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#aed7110706f1b3233aec837c73b516f94">SelectInstVisitor</a> and <a href="#ad8e851387bd5a1484316db9a34cfb477">visitSelectInst</a>.</p>

</div>
</div>

### Mode {#a5b0d4d1c9cf96a8ac50082818f23ab09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VisitMode anonymous{PGOInstrumentation.cpp}::SelectInstVisitor::Mode = <a href="/web-llvm/docs/api/namespaces/anonymous-pgoinstrumentation-cpp-/#ac08c877d41b736633cb508edd2ae970aaa95eb9f0b68bdf443d603d529a3f9c74">VM_counting</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#aeb98daec33334e1d5d6921a421f7f4e0">annotateSelects</a>, <a href="#a7197f9b727a3517cc5d550e99fd16900">countSelects</a>, <a href="#ae22b774b8f200a0f94194f43ad35bb39">instrumentSelects</a> and <a href="#ad8e851387bd5a1484316db9a34cfb477">visitSelectInst</a>.</p>

</div>
</div>

### NSIs {#ab3298e45a2c2fb5c41ce81d94e5efc86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PGOInstrumentation.cpp}::SelectInstVisitor::NSIs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#a7197f9b727a3517cc5d550e99fd16900">countSelects</a>, <a href="#a71be64e014e7768c007a06eb3591e0bf">getNumOfSelectInsts</a> and <a href="#ad8e851387bd5a1484316db9a34cfb477">visitSelectInst</a>.</p>

</div>
</div>

### TotalNumCtrs {#a072fc66753199d461e5df2b9c3b2c09b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PGOInstrumentation.cpp}::SelectInstVisitor::TotalNumCtrs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#a0cf4e2368dd2503ba7992b09322cf97a">instrumentOneSelectInst</a> and <a href="#ae22b774b8f200a0f94194f43ad35bb39">instrumentSelects</a>.</p>

</div>
</div>

### UseFunc {#aeb866db2a291ff0b10460ee488f846bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PGOUseFunc* anonymous{PGOInstrumentation.cpp}::SelectInstVisitor::UseFunc = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#ade04e51ac80ecdf0dd4c549eb91ca684">annotateOneSelectInst</a> and <a href="#aeb98daec33334e1d5d6921a421f7f4e0">annotateSelects</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
