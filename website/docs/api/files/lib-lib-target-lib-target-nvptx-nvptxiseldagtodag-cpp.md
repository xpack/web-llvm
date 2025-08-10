---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `NVPTXISelDAGToDAG.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptx-h">NVPTX.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxutilities-h">NVPTXUtilities.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">llvm/CodeGen/ISDOpcodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">llvm/CodeGen/SelectionDAGNodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "llvm/IR/IntrinsicsNVPTX.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/nvvmintrinsicutils-h">llvm/IR/NVVMIntrinsicUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/atomicordering-h">llvm/Support/AtomicOrdering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetintrinsicinfo-h">llvm/Target/TargetIntrinsicInfo.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-nvptxiseldagtodag-cpp-">anonymous{NVPTXISelDAGToDAG.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-nvptxiseldagtodag-cpp-/operationorderings">OperationOrderings</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab87de12dbe371e55d57b68c96a657432">getPTXCmpMode</a> (const CondCodeSDNode &amp;CondCode, bool FTZ)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ab9f5d7a4da7c32c7047da3d08c0f22">getCodeAddrSpace</a> (MemSDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd0157878175238e15a984de366313af">canLowerToLDG</a> (MemSDNode *N, const NVPTXSubtarget &amp;Subtarget, unsigned CodeAddrSpace, MachineFunction *F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2d8fba895d682f06bdfa1da9216fc48">getFenceOp</a> (NVPTX::Ordering O, NVPTX::Scope S, NVPTXSubtarget const *T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8492753960d752b07bc16f2328b0814">pickOpcodeForVT</a> (MVT::SimpleValueType VT, unsigned Opcode_i8, unsigned Opcode_i16, unsigned Opcode_i32, std::optional&lt; unsigned &gt; Opcode_i64, unsigned Opcode_f32, std::optional&lt; unsigned &gt; Opcode_f64)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d963dea45bb93b0a3dce47d04d1b959">getLdStRegType</a> (EVT VT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29988f8c45f50b4105d67b49ff0bd66e">isVectorElementTypeUpsized</a> (EVT EltVT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f3c1ae4858b86cca14c693cb98af79b">pickOpcodeForVectorStParam</a> (SmallVector&lt; SDValue, 8 &gt; &amp;Ops, unsigned NumElts, MVT::SimpleValueType MemTy, SelectionDAG *CurDAG, SDLoc DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14d4a2641dea2b6b929db904339cbb0a">isAddLike</a> (const SDValue V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac688df8cf1f1e144eb4fc140f4e9992f">GetCpAsyncBulkTensorS2GOpcode</a> (size_t Dim, bool IsShared32, bool IsCacheHint, bool IsIm2Col, bool IsReduce=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1ee7b07b8f0584afa2b83310603b7e2">GetCpAsyncBulkTensorG2SOpcode</a> (size_t Dim, bool IsShared32, bool IsMultiCast, bool IsCacheHint, bool IsIm2Col)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1db17237d853c77135d34258235cda7">GetCpAsyncBulkTensorPrefetchOpcode</a> (size_t Dim, bool IsCacheHint, bool IsIm2Col)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4febf7c53836e7bca48be0327db78d85">GetDimsFromIntrinsic</a> (unsigned IID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94429cfb79e342c93eb6091d2eced7c2">EnableRsqrtOpt</a>("nvptx-rsqrt-approx-opt", cl::init(true), cl::Hidden, cl::desc("Enable reciprocal sqrt optimization"))</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"nvptx-isel"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf9235cddac26ff3f81e8c56849bcaac">PASS_NAME</a>&nbsp;&nbsp;&nbsp;"NVPTX DAG-&gt;DAG <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Selection"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f38231ccf7bbd165e394043553b8e19">getOpcV2H</a>(ty, opKind0, opKind1)&nbsp;&nbsp;&nbsp;  NVPTX::StoreParamV2##ty##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##opKind0##opKind1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26044ead664497cfd3c0c5d15fb79376">getOpcV2H1</a>(ty, opKind0, isImm1)&nbsp;&nbsp;&nbsp;  (isImm1) ? <a href="#a3f38231ccf7bbd165e394043553b8e19">getOpcV2H</a>(ty, opKind0, i) : <a href="#a3f38231ccf7bbd165e394043553b8e19">getOpcV2H</a>(ty, opKind0, r)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92ffdac526e53a7e6f848b7bd25c216f">getOpcodeForVectorStParamV2</a>(ty, isimm)&nbsp;&nbsp;&nbsp;  (isimm[0]) ? <a href="#a26044ead664497cfd3c0c5d15fb79376">getOpcV2H1</a>(ty, i, isimm[1]) : <a href="#a26044ead664497cfd3c0c5d15fb79376">getOpcV2H1</a>(ty, r, isimm[1])</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63a7517728d74ee42f0e0c124a8b9af4">getOpcV4H</a>(ty, opKind0, opKind1, opKind2, opKind3)&nbsp;&nbsp;&nbsp;  NVPTX::StoreParamV4##ty##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##opKind0##opKind1##opKind2##opKind3</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06ba1d2f43d7ea53f6fe9106292d162b">getOpcV4H3</a>(ty, opKind0, opKind1, opKind2, isImm3)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee4b51eec918ef753f47c88e8b06f10e">getOpcV4H2</a>(ty, opKind0, opKind1, isImm2, isImm3)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a309bf3ec9bbf6c2d8acc00833449791d">getOpcV4H1</a>(ty, opKind0, isImm1, isImm2, isImm3)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a382988ec321024fedbacfb3279355b6a">getOpcodeForVectorStParamV4</a>(ty, isimm)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01114896848a62f9dc80bb6058743141">getOpcodeForVectorStParam</a>(n, ty, isimm)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77df5d4f07bea183cef503b97100cbde">CP_ASYNC_BULK_TENSOR_OPCODE</a>(dir, dim, mode, is_s32, suffix)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ec299c3fc4b8d019ad7a992d2fb4b77">CP_ASYNC_BULK_TENSOR_OPCODE_S2G_IMPL</a>(op, dim, mode, is_ch, is_s32)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade167e42b5f74fa526b5a712d8a6d7b5">GET_CP_ASYNC_BULK_TENSOR_OPCODE_S2G</a>(dim, mode, is_reduce, is_ch, is_s32)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab96b98af09825bebe6de2cd8398756f">GET_CP_ASYNC_BULK_TENSOR_OPCODE_G2S</a>(dim, mode, is_mc, is_ch, is_s32)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b7c5d4c57c69f906b62ca96441bf2ad">GET_CP_ASYNC_BULK_TENSOR_OPCODE_PREFETCH</a>(dim, mode, is_ch)&nbsp;&nbsp;&nbsp;...</td>
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

### canLowerToLDG() {#afd0157878175238e15a984de366313af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canLowerToLDG (<a href="/web-llvm/docs/api/classes/llvm/memsdnode">MemSDNode</a> * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/nvptxsubtarget">NVPTXSubtarget</a> &amp; Subtarget, unsigned CodeAddrSpace, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * F)</td>
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



<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc66c148bcd950ffcc3ab83989eb70bd">llvm::getUnderlyingObjects</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#a33cca915c8026e43ecc98a96089a6b86a1db64802d3774048124b6d35acbb48b8">llvm::NVPTX::Global</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxsubtarget/#ac2dc06bfd1e4225a6b53c3ac1eb36c2f">llvm::NVPTXSubtarget::hasLDG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3b262676b70a4f6a243e0133ba6a057">llvm::isKernelFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getCodeAddrSpace() {#a0ab9f5d7a4da7c32c7047da3d08c0f22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int getCodeAddrSpace (<a href="/web-llvm/docs/api/classes/llvm/memsdnode">MemSDNode</a> * N)</td>
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



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/nvptxas/#ad7d00b71af84502be65ae2de3f8d91dcaa7701b34c71eb9e5350dc4d064e1f277">llvm::NVPTXAS::ADDRESS_SPACE_CONST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptxas/#ad7d00b71af84502be65ae2de3f8d91dca6c5cbbdf5d30037891306aa6f4924861">llvm::NVPTXAS::ADDRESS_SPACE_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptxas/#ad7d00b71af84502be65ae2de3f8d91dcaceddeb6fcb76cf8bc90c36c67921458d">llvm::NVPTXAS::ADDRESS_SPACE_GLOBAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptxas/#ad7d00b71af84502be65ae2de3f8d91dca5422550a7a085ef37ff834c019121b9b">llvm::NVPTXAS::ADDRESS_SPACE_LOCAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptxas/#ad7d00b71af84502be65ae2de3f8d91dca145cc11601487c71350537df3e7c3a12">llvm::NVPTXAS::ADDRESS_SPACE_PARAM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptxas/#ad7d00b71af84502be65ae2de3f8d91dca84ed6691f422fcd91883fe2c2f9e6520">llvm::NVPTXAS::ADDRESS_SPACE_SHARED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#a33cca915c8026e43ecc98a96089a6b86a78523d34068fb7d8996627878dd5ba19">llvm::NVPTX::Const</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#a33cca915c8026e43ecc98a96089a6b86aa39dce0fae417c281c73ce59bf74f23d">llvm::NVPTX::Generic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#a33cca915c8026e43ecc98a96089a6b86a1db64802d3774048124b6d35acbb48b8">llvm::NVPTX::Global</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#a33cca915c8026e43ecc98a96089a6b86afa222eeb9d903482895b95ece2b983b7">llvm::NVPTX::Local</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#a33cca915c8026e43ecc98a96089a6b86a2f6244cb6b1966052e52af35d910cf8d">llvm::NVPTX::Param</a> and <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#a33cca915c8026e43ecc98a96089a6b86a54c619e65d06a9f19b7bb89cef76b1a9">llvm::NVPTX::Shared</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxiseldagtodag-cpp-/#a4b394d4c4aa365db793d44aa627bec7a">anonymous{NVPTXISelDAGToDAG.cpp}::getOperationOrderings</a>.</p>

</div>
</div>

### GetCpAsyncBulkTensorG2SOpcode() {#ab1ee7b07b8f0584afa2b83310603b7e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GetCpAsyncBulkTensorG2SOpcode (size_t Dim, bool IsShared32, bool IsMultiCast, bool IsCacheHint, bool IsIm2Col)</td>
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



<p>Definition at line 2902 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#aab96b98af09825bebe6de2cd8398756f">GET_CP_ASYNC_BULK_TENSOR_OPCODE_G2S</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### GetCpAsyncBulkTensorPrefetchOpcode() {#aa1db17237d853c77135d34258235cda7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GetCpAsyncBulkTensorPrefetchOpcode (size_t Dim, bool IsCacheHint, bool IsIm2Col)</td>
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



<p>Definition at line 2944 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a9b7c5d4c57c69f906b62ca96441bf2ad">GET_CP_ASYNC_BULK_TENSOR_OPCODE_PREFETCH</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### GetCpAsyncBulkTensorS2GOpcode() {#ac688df8cf1f1e144eb4fc140f4e9992f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GetCpAsyncBulkTensorS2GOpcode (size_t Dim, bool IsShared32, bool IsCacheHint, bool IsIm2Col, bool IsReduce=false)</td>
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



<p>Definition at line 2860 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#ade167e42b5f74fa526b5a712d8a6d7b5">GET_CP_ASYNC_BULK_TENSOR_OPCODE_S2G</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### GetDimsFromIntrinsic() {#a4febf7c53836e7bca48be0327db78d85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t GetDimsFromIntrinsic (unsigned IID)</td>
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



<p>Definition at line 2977 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getFenceOp() {#ac2d8fba895d682f06bdfa1da9216fc48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int getFenceOp (NVPTX::Ordering O, NVPTX::Scope S, <a href="/web-llvm/docs/api/classes/llvm/nvptxsubtarget">NVPTXSubtarget</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * T)</td>
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



<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#adcf87377f3df8d9008825b7fc46f4f01a049c4a51b6abaec68a318a3167fffab0">llvm::NVPTX::Acquire</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#adcf87377f3df8d9008825b7fc46f4f01a26dda733942c66d9cb2dc8238553997e">llvm::NVPTX::AcquireRelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#abd325b49b8e2f00c0370b1c68cf51557abc608f966fee23eee5f3589a2aba4885">llvm::NVPTX::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#abd325b49b8e2f00c0370b1c68cf51557a2f28817471f8380496f40c1c375c4e56">llvm::NVPTX::Cluster</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#abd325b49b8e2f00c0370b1c68cf51557a67abb9e8dc09f85f29d80f83816cc1fc">llvm::NVPTX::Device</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#adcf87377f3df8d9008825b7fc46f4f01a8392068ab98bc624c0f367e662639412">llvm::NVPTX::NotAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#adcf87377f3df8d9008825b7fc46f4f01a1897d7bdf307cfe860a93305d7b53f2d">llvm::NVPTX::Relaxed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#adcf87377f3df8d9008825b7fc46f4f01a00c1ec0cc5d8e908c81e0f31af1aac13">llvm::NVPTX::RelaxedMMIO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#adcf87377f3df8d9008825b7fc46f4f01ac9b2103fef41f5e9b1d44dc5beb90f81">llvm::NVPTX::Release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#adcf87377f3df8d9008825b7fc46f4f01ad9751ec400c96e6c2b104cc6c9859a71">llvm::NVPTX::SequentiallyConsistent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#abd325b49b8e2f00c0370b1c68cf51557a1faa2f7d3da4de57eaafa85a9a7cae24">llvm::NVPTX::System</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#abd325b49b8e2f00c0370b1c68cf51557a464696eb6092395b24545604b7895ade">llvm::NVPTX::Thread</a> and <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#adcf87377f3df8d9008825b7fc46f4f01abccad5ae872ddb0c9b447c03602e8eab">llvm::NVPTX::Volatile</a>.</p>

</div>
</div>

### getLdStRegType() {#a5d963dea45bb93b0a3dce47d04d1b959}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getLdStRegType (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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



<p>Definition at line 859 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/ptxldstinstcode/#a0c4e2aa2235abdd10d2beffa32cd9b14aa8d7a04ea7f61b2ae1250844cfc54941">llvm::NVPTX::PTXLdStInstCode::Float</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3cb888a2ce8e95e0d9769687a5e2f7d8">llvm::EVT::isFloatingPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/ptxldstinstcode/#a0c4e2aa2235abdd10d2beffa32cd9b14a0198fed90551f808b7a382645423973e">llvm::NVPTX::PTXLdStInstCode::Unsigned</a> and <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/ptxldstinstcode/#a0c4e2aa2235abdd10d2beffa32cd9b14a448371f2dc276c5057e976c8a436ceb6">llvm::NVPTX::PTXLdStInstCode::Untyped</a>.</p>

</div>
</div>

### getPTXCmpMode() {#ab87de12dbe371e55d57b68c96a657432}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getPTXCmpMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/condcodesdnode">CondCodeSDNode</a> &amp; CondCode, bool FTZ)</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/ptxcmpmode/#a13b9c6223f7f34fde0411c28a2bc8ee0a758150fd7bba5b66467c54d6b19ad955">llvm::NVPTX::PTXCmpMode::FTZ_FLAG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4">llvm::ISD::SETEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a7f47862de23f7210f88ccf98ae1efbe4">llvm::ISD::SETGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a5ad12b466e3a5900d0c307b301465d25">llvm::ISD::SETGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ab49f81c2ecbbff3d0fbe55dd46353774">llvm::ISD::SETLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a6f05a09edb671910f85f8665981cbde9">llvm::ISD::SETLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a71f916390487bb109d9968c72553eaf4">llvm::ISD::SETO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a08c31033acfb9d6f0bc4a8a82cc26862">llvm::ISD::SETOEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ac7bb30d4918c1ee9dd208083154e109f">llvm::ISD::SETOGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a31d1e24e08b255d6aa290d67d16ce2c9">llvm::ISD::SETOGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a1febf3bac2f3d7d98ec19f1ff5c385ea">llvm::ISD::SETOLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a20257a4d3833cf88afd42caeaed70dde">llvm::ISD::SETOLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a57c68bf7ef20bd558854a24d5b0c1e72">llvm::ISD::SETONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a0deb50cd2f3f8e4a94eef4cdf769b848">llvm::ISD::SETUEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a9dff1dcbac65852b71473818c11869b1">llvm::ISD::SETUGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a292be4a9782030bfad637581d25a5897">llvm::ISD::SETUGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ac538f0b432df970cbaaf6b81d777c6a7">llvm::ISD::SETULE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a473200f06bdd611fdbed43d908b84305">llvm::ISD::SETULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a0d1546187d4d526fcbdd43183689075e">llvm::ISD::SETUNE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a48a334bbe606d5e82c9cd84eaa127b50">llvm::ISD::SETUO</a>.</p>

</div>
</div>

### isAddLike() {#a14d4a2641dea2b6b929db904339cbb0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isAddLike (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> V)</td>
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



<p>Definition at line 2516 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>.</p>

</div>
</div>

### isVectorElementTypeUpsized() {#a29988f8c45f50b4105d67b49ff0bd66e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isVectorElementTypeUpsized (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> EltVT)</td>
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



<p>Definition at line 993 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1744746d4913273ac648d203faed8df6">llvm::Isv2x16VT</a>.</p>

</div>
</div>

### pickOpcodeForVectorStParam() {#a5f3c1ae4858b86cca14c693cb98af79b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned pickOpcodeForVectorStParam (<a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, 8 &gt; &amp; Ops, unsigned NumElts, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64d">MVT::SimpleValueType</a> MemTy, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * CurDAG, <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> DL)</td>
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



<p>Definition at line 2065 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#affe0a8af32c1d4e53b07959b240641b4">F32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a563bbae35885ba289017e47ec57235fa">F64</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfpsdnode/#a8f3c3a82532c2aa02fe40a8384248770">llvm::ConstantFPSDNode::getConstantFPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a2fc96a0a5ba1e0161d95f4b7771e8216">llvm::ConstantSDNode::getConstantIntValue</a>, <a href="#a01114896848a62f9dc80bb6058743141">getOpcodeForVectorStParam</a>, <a href="#a92ffdac526e53a7e6f848b7bd25c216f">getOpcodeForVectorStParamV2</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab9856a279fcd6ef723300b24a69a6500">llvm::SelectionDAG::getTargetConstantFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### pickOpcodeForVT() {#ac8492753960d752b07bc16f2328b0814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; pickOpcodeForVT (<a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64d">MVT::SimpleValueType</a> VT, unsigned Opcode_i8, unsigned Opcode_i16, unsigned Opcode_i32, std::optional&lt; unsigned &gt; Opcode_i64, unsigned Opcode_f32, std::optional&lt; unsigned &gt; Opcode_f64)</td>
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



<p>Definition at line 828 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### EnableRsqrtOpt {#a94429cfb79e342c93eb6091d2eced7c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableRsqrtOpt("nvptx-rsqrt-approx-opt", cl::init(true), cl::Hidden, cl::desc("Enable reciprocal sqrt optimization"))</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### CP\_ASYNC\_BULK\_TENSOR\_OPCODE {#a77df5d4f07bea183cef503b97100cbde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CP_ASYNC_BULK_TENSOR_OPCODE(dir, dim, mode, is_s32, suffix)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  (is_s32                                                                      \
       ? NVPTX::CP_ASYNC_BULK_TENSOR_##dir##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##dim##_SHARED32_##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonoptaddrmode-cpp/#abdd61257a7f5e75ed961036299f26498">mode</a>##suffix   \
       : NVPTX::CP_ASYNC_BULK_TENSOR_##dir##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##dim##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonoptaddrmode-cpp/#abdd61257a7f5e75ed961036299f26498">mode</a>##suffix)
</div>
</dd>
</dl>

<p>Definition at line 2829 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### CP\_ASYNC\_BULK\_TENSOR\_OPCODE\_S2G\_IMPL {#a8ec299c3fc4b8d019ad7a992d2fb4b77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CP_ASYNC_BULK_TENSOR_OPCODE_S2G_IMPL(op, dim, mode, is_ch, is_s32)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  (is_ch ? (<a href="#a77df5d4f07bea183cef503b97100cbde">CP_ASYNC_BULK_TENSOR_OPCODE</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>, dim, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonoptaddrmode-cpp/#abdd61257a7f5e75ed961036299f26498">mode</a>, is_s32, _CH))           \
         : (<a href="#a77df5d4f07bea183cef503b97100cbde">CP_ASYNC_BULK_TENSOR_OPCODE</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>, dim, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonoptaddrmode-cpp/#abdd61257a7f5e75ed961036299f26498">mode</a>, is_s32, )))
</div>
</dd>
</dl>

<p>Definition at line 2834 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"nvptx-isel"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### GET\_CP\_ASYNC\_BULK\_TENSOR\_OPCODE\_G2S {#aab96b98af09825bebe6de2cd8398756f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_CP_ASYNC_BULK_TENSOR_OPCODE_G2S(dim, mode, is_mc, is_ch, is_s32)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  [&amp;]() -&gt; auto {                                                              \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (is_mc &amp;&amp; is_ch)                                                        \
      return <a href="#a77df5d4f07bea183cef503b97100cbde">CP_ASYNC_BULK_TENSOR_OPCODE</a>(G2S, dim, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonoptaddrmode-cpp/#abdd61257a7f5e75ed961036299f26498">mode</a>, is_s32, _MC_CH);      \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (is_ch)                                                                 \
      return <a href="#a77df5d4f07bea183cef503b97100cbde">CP_ASYNC_BULK_TENSOR_OPCODE</a>(G2S, dim, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonoptaddrmode-cpp/#abdd61257a7f5e75ed961036299f26498">mode</a>, is_s32, _CH);         \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (is_mc)                                                                 \
      return <a href="#a77df5d4f07bea183cef503b97100cbde">CP_ASYNC_BULK_TENSOR_OPCODE</a>(G2S, dim, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonoptaddrmode-cpp/#abdd61257a7f5e75ed961036299f26498">mode</a>, is_s32, _MC);         \
    return <a href="#a77df5d4f07bea183cef503b97100cbde">CP_ASYNC_BULK_TENSOR_OPCODE</a>(G2S, dim, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonoptaddrmode-cpp/#abdd61257a7f5e75ed961036299f26498">mode</a>, is_s32, );              \
  }()
</div>
</dd>
</dl>

<p>Definition at line 2845 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#ab1ee7b07b8f0584afa2b83310603b7e2">GetCpAsyncBulkTensorG2SOpcode</a>.</p>

</div>
</div>

### GET\_CP\_ASYNC\_BULK\_TENSOR\_OPCODE\_PREFETCH {#a9b7c5d4c57c69f906b62ca96441bf2ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_CP_ASYNC_BULK_TENSOR_OPCODE_PREFETCH(dim, mode, is_ch)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  (is_ch ? NVPTX::CP_ASYNC_BULK_TENSOR_PREFETCH_##dim##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonoptaddrmode-cpp/#abdd61257a7f5e75ed961036299f26498">mode</a>##_CH            \
         : NVPTX::CP_ASYNC_BULK_TENSOR_PREFETCH_##dim##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonoptaddrmode-cpp/#abdd61257a7f5e75ed961036299f26498">mode</a>)
</div>
</dd>
</dl>

<p>Definition at line 2856 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#aa1db17237d853c77135d34258235cda7">GetCpAsyncBulkTensorPrefetchOpcode</a>.</p>

</div>
</div>

### GET\_CP\_ASYNC\_BULK\_TENSOR\_OPCODE\_S2G {#ade167e42b5f74fa526b5a712d8a6d7b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_CP_ASYNC_BULK_TENSOR_OPCODE_S2G(dim, mode, is_reduce, is_ch, is_s32)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  (is_reduce                                                                   \
       ? (<a href="#a8ec299c3fc4b8d019ad7a992d2fb4b77">CP_ASYNC_BULK_TENSOR_OPCODE_S2G_IMPL</a>(RED, dim, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonoptaddrmode-cpp/#abdd61257a7f5e75ed961036299f26498">mode</a>, is_ch, is_s32)) \
       : (<a href="#a8ec299c3fc4b8d019ad7a992d2fb4b77">CP_ASYNC_BULK_TENSOR_OPCODE_S2G_IMPL</a>(S2G, dim, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonoptaddrmode-cpp/#abdd61257a7f5e75ed961036299f26498">mode</a>, is_ch,          \
                                               is_s32)))
</div>
</dd>
</dl>

<p>Definition at line 2839 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#ac688df8cf1f1e144eb4fc140f4e9992f">GetCpAsyncBulkTensorS2GOpcode</a>.</p>

</div>
</div>

### getOpcodeForVectorStParam {#a01114896848a62f9dc80bb6058743141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define getOpcodeForVectorStParam(n, ty, isimm)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  (n == 2) ? <a href="#a92ffdac526e53a7e6f848b7bd25c216f">getOpcodeForVectorStParamV2</a>(ty, isimm)                            \
           : <a href="#a382988ec321024fedbacfb3279355b6a">getOpcodeForVectorStParamV4</a>(ty, isimm)
</div>
</dd>
</dl>

<p>Definition at line 2061 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#a5f3c1ae4858b86cca14c693cb98af79b">pickOpcodeForVectorStParam</a>.</p>

</div>
</div>

### getOpcodeForVectorStParamV2 {#a92ffdac526e53a7e6f848b7bd25c216f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define getOpcodeForVectorStParamV2(ty, isimm)&nbsp;&nbsp;&nbsp;  (isimm[0]) ? <a href="#a26044ead664497cfd3c0c5d15fb79376">getOpcV2H1</a>(ty, i, isimm[1]) : <a href="#a26044ead664497cfd3c0c5d15fb79376">getOpcV2H1</a>(ty, r, isimm[1])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2039 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#a5f3c1ae4858b86cca14c693cb98af79b">pickOpcodeForVectorStParam</a>.</p>

</div>
</div>

### getOpcodeForVectorStParamV4 {#a382988ec321024fedbacfb3279355b6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define getOpcodeForVectorStParamV4(ty, isimm)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  (isimm[0]) ? <a href="#a309bf3ec9bbf6c2d8acc00833449791d">getOpcV4H1</a>(ty, i, isimm[1], isimm[2], isimm[3])                 \
             : <a href="#a309bf3ec9bbf6c2d8acc00833449791d">getOpcV4H1</a>(ty, r, isimm[1], isimm[2], isimm[3])
</div>
</dd>
</dl>

<p>Definition at line 2057 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getOpcV2H {#a3f38231ccf7bbd165e394043553b8e19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define getOpcV2H(ty, opKind0, opKind1)&nbsp;&nbsp;&nbsp;  NVPTX::StoreParamV2##ty##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##opKind0##opKind1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2033 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getOpcV2H1 {#a26044ead664497cfd3c0c5d15fb79376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define getOpcV2H1(ty, opKind0, isImm1)&nbsp;&nbsp;&nbsp;  (isImm1) ? <a href="#a3f38231ccf7bbd165e394043553b8e19">getOpcV2H</a>(ty, opKind0, i) : <a href="#a3f38231ccf7bbd165e394043553b8e19">getOpcV2H</a>(ty, opKind0, r)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2036 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getOpcV4H {#a63a7517728d74ee42f0e0c124a8b9af4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define getOpcV4H(ty, opKind0, opKind1, opKind2, opKind3)&nbsp;&nbsp;&nbsp;  NVPTX::StoreParamV4##ty##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##opKind0##opKind1##opKind2##opKind3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2042 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getOpcV4H1 {#a309bf3ec9bbf6c2d8acc00833449791d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define getOpcV4H1(ty, opKind0, isImm1, isImm2, isImm3)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  (isImm1) ? <a href="#aee4b51eec918ef753f47c88e8b06f10e">getOpcV4H2</a>(ty, opKind0, i, isImm2, isImm3)                        \
           : <a href="#aee4b51eec918ef753f47c88e8b06f10e">getOpcV4H2</a>(ty, opKind0, r, isImm2, isImm3)
</div>
</dd>
</dl>

<p>Definition at line 2053 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getOpcV4H2 {#aee4b51eec918ef753f47c88e8b06f10e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define getOpcV4H2(ty, opKind0, opKind1, isImm2, isImm3)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  (isImm2) ? <a href="#a06ba1d2f43d7ea53f6fe9106292d162b">getOpcV4H3</a>(ty, opKind0, opKind1, i, isImm3)                       \
           : <a href="#a06ba1d2f43d7ea53f6fe9106292d162b">getOpcV4H3</a>(ty, opKind0, opKind1, r, isImm3)
</div>
</dd>
</dl>

<p>Definition at line 2049 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getOpcV4H3 {#a06ba1d2f43d7ea53f6fe9106292d162b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define getOpcV4H3(ty, opKind0, opKind1, opKind2, isImm3)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  (isImm3) ? <a href="#a63a7517728d74ee42f0e0c124a8b9af4">getOpcV4H</a>(ty, opKind0, opKind1, opKind2, i)                       \
           : <a href="#a63a7517728d74ee42f0e0c124a8b9af4">getOpcV4H</a>(ty, opKind0, opKind1, opKind2, r)
</div>
</dd>
</dl>

<p>Definition at line 2045 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### PASS\_NAME {#acf9235cddac26ff3f81e8c56849bcaac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PASS_NAME&nbsp;&nbsp;&nbsp;"NVPTX DAG-&gt;DAG <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Selection"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
