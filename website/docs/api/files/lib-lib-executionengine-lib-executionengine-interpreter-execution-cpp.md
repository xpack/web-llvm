---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Execution.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/intrinsiclowering-h">llvm/CodeGen/IntrinsicLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/getelementptrtypeiterator-h">llvm/IR/GetElementPtrTypeIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;algorithm&gt;
#include &lt;cmath&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3e13c10a54f07060151d496cffde457">STATISTIC</a> (NumDynamicInsts, "Number of dynamic instructions executed")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a> (Value *V, GenericValue Val, ExecutionContext &amp;SF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6afbe60697d1b461028d733f1380e22d">executeFNegInst</a> (GenericValue &amp;Dest, GenericValue Src, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46d49ce365aa2b814bb9b25f332757df">executeFAddInst</a> (GenericValue &amp;Dest, GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ba822e8185395389ff297d86335506b">executeFSubInst</a> (GenericValue &amp;Dest, GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8cce347f31a3057d0d8a61a4ade64e4">executeFMulInst</a> (GenericValue &amp;Dest, GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dcd6bdc8271cf5a7a963933e7a18c66">executeFDivInst</a> (GenericValue &amp;Dest, GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2b2089ccf34571233f731db1c299b85">executeFRemInst</a> (GenericValue &amp;Dest, GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7670586abfe3aed532c70997b0d4424">executeICMP_EQ</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a908bbe72c94bd551dcbd394a8817c2d7">executeICMP_NE</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9477a1cada9e071e78a65a75f09247b">executeICMP_ULT</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b809b83b0c40ad9dcb8bbd8ea4591a7">executeICMP_SLT</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a072f11ea1ef8304f96662d1f385f5ad3">executeICMP_UGT</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d592b5002f3855f9fa9f486a55087b2">executeICMP_SGT</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a826efd0d1d8bbe269183e89ea5514e2f">executeICMP_ULE</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f5002419dfa68ad8a3be90f9e591a1d">executeICMP_SLE</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c84af3c90fae95a8ea40029ddceb3b0">executeICMP_UGE</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34085170841ce0d5eb1687c8cefd9234">executeICMP_SGE</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53a0f3f250d2ad3ab79b96b2d7b12527">executeFCMP_OEQ</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad84c8e547a3add8cc581d6fbec1ea5cb">executeFCMP_ONE</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a687130dc367d99c69d3c7c611169d6b6">executeFCMP_OLE</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0473b23318c3e81617e969e5d34b6c65">executeFCMP_OGE</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88f7c3a00a5fc3920f305094bf381798">executeFCMP_OLT</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35b4530505dca524726752e6a20883e1">executeFCMP_OGT</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc7da546e2638a58b40f8236f43e91c0">executeFCMP_UEQ</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42019dfdf44962124bfc3ed1e7dda826">executeFCMP_UNE</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ca29b39b2e1fbf95a750c13d2035f61">executeFCMP_ULE</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03c3b9faab810a8a847dee1c1024db92">executeFCMP_UGE</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f7dd1881517874a4850e4d1cb970a66">executeFCMP_ULT</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed4e397ad7ab2921318cf474e0b8320e">executeFCMP_UGT</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a1b97d63e55b8f92d4d2e5468fb7cf6">executeFCMP_ORD</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ecb49f4c2b5b1041e0ad44dc213f5b0">executeFCMP_UNO</a> (GenericValue Src1, GenericValue Src2, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dbb09eb50c3c8609ff46bf6add8c2ee">executeFCMP_BOOL</a> (GenericValue Src1, GenericValue Src2, Type *Ty, const bool val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f71481be990c1361b473eea6c18df11">executeSelectInst</a> (GenericValue Src1, GenericValue Src2, GenericValue Src3, Type *Ty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9de4ecd5d07314b56d5a0d1fad6f6fc">getShiftAmount</a> (uint64_t orgShiftAmount, llvm::APInt valueToShift)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a748be8883cec545a336485a26d8fc097">PrintVolatile</a>("interpreter-print-volatile", cl::Hidden, cl::desc("make the interpreter print every volatile load and store"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"interpreter"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3949efc1d5bca1a86dcf300cf11536ee">IMPLEMENT_BINARY_OPERATOR</a>(OP, TY)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4e06ed051f3a169ce69957401c35978">IMPLEMENT_INTEGER_ICMP</a>(OP, TY)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fbafd8ad5bbf8c85080bd1083b94318">IMPLEMENT_VECTOR_INTEGER_ICMP</a>(OP, TY)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a930b0c47dc8ca23c7c467b8818f9a6c6">IMPLEMENT_POINTER_ICMP</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac86dae43d05947074538335c136d8286">IMPLEMENT_FCMP</a>(OP, TY)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb6c924a81110e476857a563b911073b">IMPLEMENT_VECTOR_FCMP_T</a>(OP, TY)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ed001f6ad2ba58b6d619c555334c829">IMPLEMENT_VECTOR_FCMP</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a441661dba18aaac72417737b68cce3ee">IMPLEMENT_SCALAR_NANS</a>(TY, X, Y)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cdbcca6a13731e5efb6848f9ca0da6e">MASK_VECTOR_NANS_T</a>(X, Y, TZ, FLAG)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7870210eb9766fdb8b9e8c2d3bbe7424">MASK_VECTOR_NANS</a>(TY, X, Y, FLAG)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c13a70fc317a045485f7a12c8855609">IMPLEMENT_UNORDERED</a>(TY, X, Y)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9a34d26aaadbcb4dde31f56c68e9dc7">IMPLEMENT_VECTOR_UNORDERED</a>(TY, X, Y, FUNC)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35d25f42428e57ca9b363fe5c8ea2b74">INTEGER_VECTOR_OPERATION</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a772ad021946611dccd72512addffaa8e">INTEGER_VECTOR_FUNCTION</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae82dc0214067114dea1566497bd42c5e">FLOAT_VECTOR_FUNCTION</a>(OP, TY)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ecc89a903a39fa91e98829c7a768fb9">FLOAT_VECTOR_OP</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab17082b5668396b9c47660397a72c0e6">IMPLEMENT_VAARG</a>(TY)&nbsp;&nbsp;&nbsp;   case Type::TY##TyID: Dest.TY##Val = Src.TY##Val; break</td>
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

### executeFAddInst() {#a46d49ce365aa2b814bb9b25f332757df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void executeFAddInst (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &amp; Dest, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">Float</a>, <a href="#a3949efc1d5bca1a86dcf300cf11536ee">IMPLEMENT_BINARY_OPERATOR</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ad931a9b6a516452142c12592afe8968d">llvm::Interpreter::visitBinaryOperator</a>.</p>

</div>
</div>

### executeFCMP\_BOOL() {#a9dbb09eb50c3c8609ff46bf6add8c2ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeFCMP_BOOL (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool val)</td>
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



<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#aa46325f5b23e83bb49e497cfce2f1b89">llvm::GenericValue::AggregateVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a06c639b057f4b02e4ea274c3e059c95f">llvm::Interpreter::visitFCmpInst</a>.</p>

</div>
</div>

### executeFCMP\_OEQ() {#a53a0f3f250d2ad3ab79b96b2d7b12527}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeFCMP_OEQ (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">Float</a>, <a href="#ac86dae43d05947074538335c136d8286">IMPLEMENT_FCMP</a>, <a href="#a7ed001f6ad2ba58b6d619c555334c829">IMPLEMENT_VECTOR_FCMP</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#adc7da546e2638a58b40f8236f43e91c0">executeFCMP_UEQ</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a06c639b057f4b02e4ea274c3e059c95f">llvm::Interpreter::visitFCmpInst</a>.</p>

</div>
</div>

### executeFCMP\_OGE() {#a0473b23318c3e81617e969e5d34b6c65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeFCMP_OGE (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">Float</a>, <a href="#ac86dae43d05947074538335c136d8286">IMPLEMENT_FCMP</a>, <a href="#a7ed001f6ad2ba58b6d619c555334c829">IMPLEMENT_VECTOR_FCMP</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a03c3b9faab810a8a847dee1c1024db92">executeFCMP_UGE</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a06c639b057f4b02e4ea274c3e059c95f">llvm::Interpreter::visitFCmpInst</a>.</p>

</div>
</div>

### executeFCMP\_OGT() {#a35b4530505dca524726752e6a20883e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeFCMP_OGT (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">Float</a>, <a href="#ac86dae43d05947074538335c136d8286">IMPLEMENT_FCMP</a>, <a href="#a7ed001f6ad2ba58b6d619c555334c829">IMPLEMENT_VECTOR_FCMP</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#aed4e397ad7ab2921318cf474e0b8320e">executeFCMP_UGT</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a06c639b057f4b02e4ea274c3e059c95f">llvm::Interpreter::visitFCmpInst</a>.</p>

</div>
</div>

### executeFCMP\_OLE() {#a687130dc367d99c69d3c7c611169d6b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeFCMP_OLE (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">Float</a>, <a href="#ac86dae43d05947074538335c136d8286">IMPLEMENT_FCMP</a>, <a href="#a7ed001f6ad2ba58b6d619c555334c829">IMPLEMENT_VECTOR_FCMP</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a1ca29b39b2e1fbf95a750c13d2035f61">executeFCMP_ULE</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a06c639b057f4b02e4ea274c3e059c95f">llvm::Interpreter::visitFCmpInst</a>.</p>

</div>
</div>

### executeFCMP\_OLT() {#a88f7c3a00a5fc3920f305094bf381798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeFCMP_OLT (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">Float</a>, <a href="#ac86dae43d05947074538335c136d8286">IMPLEMENT_FCMP</a>, <a href="#a7ed001f6ad2ba58b6d619c555334c829">IMPLEMENT_VECTOR_FCMP</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a8f7dd1881517874a4850e4d1cb970a66">executeFCMP_ULT</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a06c639b057f4b02e4ea274c3e059c95f">llvm::Interpreter::visitFCmpInst</a>.</p>

</div>
</div>

### executeFCMP\_ONE() {#ad84c8e547a3add8cc581d6fbec1ea5cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeFCMP_ONE (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#aa46325f5b23e83bb49e497cfce2f1b89">llvm::GenericValue::AggregateVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">Float</a>, <a href="#ac86dae43d05947074538335c136d8286">IMPLEMENT_FCMP</a>, <a href="#a441661dba18aaac72417737b68cce3ee">IMPLEMENT_SCALAR_NANS</a>, <a href="#a7ed001f6ad2ba58b6d619c555334c829">IMPLEMENT_VECTOR_FCMP</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#a7870210eb9766fdb8b9e8c2d3bbe7424">MASK_VECTOR_NANS</a>.</p>


<p>Referenced by <a href="#a42019dfdf44962124bfc3ed1e7dda826">executeFCMP_UNE</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a06c639b057f4b02e4ea274c3e059c95f">llvm::Interpreter::visitFCmpInst</a>.</p>

</div>
</div>

### executeFCMP\_ORD() {#a9a1b97d63e55b8f92d4d2e5468fb7cf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeFCMP_ORD (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#aa46325f5b23e83bb49e497cfce2f1b89">llvm::GenericValue::AggregateVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a9810b36b4c4c17901d491f5aac030623">llvm::GenericValue::DoubleVal</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a5160197592bd1fc5c8cc81cd803e0629">llvm::GenericValue::FloatVal</a> and <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a06c639b057f4b02e4ea274c3e059c95f">llvm::Interpreter::visitFCmpInst</a>.</p>

</div>
</div>

### executeFCMP\_UEQ() {#adc7da546e2638a58b40f8236f43e91c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeFCMP_UEQ (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="#a53a0f3f250d2ad3ab79b96b2d7b12527">executeFCMP_OEQ</a>, <a href="#a9c13a70fc317a045485f7a12c8855609">IMPLEMENT_UNORDERED</a>, <a href="#aa9a34d26aaadbcb4dde31f56c68e9dc7">IMPLEMENT_VECTOR_UNORDERED</a> and <a href="#a7870210eb9766fdb8b9e8c2d3bbe7424">MASK_VECTOR_NANS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a06c639b057f4b02e4ea274c3e059c95f">llvm::Interpreter::visitFCmpInst</a>.</p>

</div>
</div>

### executeFCMP\_UGE() {#a03c3b9faab810a8a847dee1c1024db92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeFCMP_UGE (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="#a0473b23318c3e81617e969e5d34b6c65">executeFCMP_OGE</a>, <a href="#a9c13a70fc317a045485f7a12c8855609">IMPLEMENT_UNORDERED</a>, <a href="#aa9a34d26aaadbcb4dde31f56c68e9dc7">IMPLEMENT_VECTOR_UNORDERED</a> and <a href="#a7870210eb9766fdb8b9e8c2d3bbe7424">MASK_VECTOR_NANS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a06c639b057f4b02e4ea274c3e059c95f">llvm::Interpreter::visitFCmpInst</a>.</p>

</div>
</div>

### executeFCMP\_UGT() {#aed4e397ad7ab2921318cf474e0b8320e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeFCMP_UGT (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="#a35b4530505dca524726752e6a20883e1">executeFCMP_OGT</a>, <a href="#a9c13a70fc317a045485f7a12c8855609">IMPLEMENT_UNORDERED</a>, <a href="#aa9a34d26aaadbcb4dde31f56c68e9dc7">IMPLEMENT_VECTOR_UNORDERED</a> and <a href="#a7870210eb9766fdb8b9e8c2d3bbe7424">MASK_VECTOR_NANS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a06c639b057f4b02e4ea274c3e059c95f">llvm::Interpreter::visitFCmpInst</a>.</p>

</div>
</div>

### executeFCMP\_ULE() {#a1ca29b39b2e1fbf95a750c13d2035f61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeFCMP_ULE (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="#a687130dc367d99c69d3c7c611169d6b6">executeFCMP_OLE</a>, <a href="#a9c13a70fc317a045485f7a12c8855609">IMPLEMENT_UNORDERED</a>, <a href="#aa9a34d26aaadbcb4dde31f56c68e9dc7">IMPLEMENT_VECTOR_UNORDERED</a> and <a href="#a7870210eb9766fdb8b9e8c2d3bbe7424">MASK_VECTOR_NANS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a06c639b057f4b02e4ea274c3e059c95f">llvm::Interpreter::visitFCmpInst</a>.</p>

</div>
</div>

### executeFCMP\_ULT() {#a8f7dd1881517874a4850e4d1cb970a66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeFCMP_ULT (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="#a88f7c3a00a5fc3920f305094bf381798">executeFCMP_OLT</a>, <a href="#a9c13a70fc317a045485f7a12c8855609">IMPLEMENT_UNORDERED</a>, <a href="#aa9a34d26aaadbcb4dde31f56c68e9dc7">IMPLEMENT_VECTOR_UNORDERED</a> and <a href="#a7870210eb9766fdb8b9e8c2d3bbe7424">MASK_VECTOR_NANS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a06c639b057f4b02e4ea274c3e059c95f">llvm::Interpreter::visitFCmpInst</a>.</p>

</div>
</div>

### executeFCMP\_UNE() {#a42019dfdf44962124bfc3ed1e7dda826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeFCMP_UNE (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="#ad84c8e547a3add8cc581d6fbec1ea5cb">executeFCMP_ONE</a>, <a href="#a9c13a70fc317a045485f7a12c8855609">IMPLEMENT_UNORDERED</a>, <a href="#aa9a34d26aaadbcb4dde31f56c68e9dc7">IMPLEMENT_VECTOR_UNORDERED</a> and <a href="#a7870210eb9766fdb8b9e8c2d3bbe7424">MASK_VECTOR_NANS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a06c639b057f4b02e4ea274c3e059c95f">llvm::Interpreter::visitFCmpInst</a>.</p>

</div>
</div>

### executeFCMP\_UNO() {#a4ecb49f4c2b5b1041e0ad44dc213f5b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeFCMP_UNO (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#aa46325f5b23e83bb49e497cfce2f1b89">llvm::GenericValue::AggregateVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a9810b36b4c4c17901d491f5aac030623">llvm::GenericValue::DoubleVal</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a5160197592bd1fc5c8cc81cd803e0629">llvm::GenericValue::FloatVal</a> and <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a06c639b057f4b02e4ea274c3e059c95f">llvm::Interpreter::visitFCmpInst</a>.</p>

</div>
</div>

### executeFDivInst() {#a2dcd6bdc8271cf5a7a963933e7a18c66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void executeFDivInst (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &amp; Dest, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">Float</a>, <a href="#a3949efc1d5bca1a86dcf300cf11536ee">IMPLEMENT_BINARY_OPERATOR</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ad931a9b6a516452142c12592afe8968d">llvm::Interpreter::visitBinaryOperator</a>.</p>

</div>
</div>

### executeFMulInst() {#af8cce347f31a3057d0d8a61a4ade64e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void executeFMulInst (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &amp; Dest, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">Float</a>, <a href="#a3949efc1d5bca1a86dcf300cf11536ee">IMPLEMENT_BINARY_OPERATOR</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ad931a9b6a516452142c12592afe8968d">llvm::Interpreter::visitBinaryOperator</a>.</p>

</div>
</div>

### executeFNegInst() {#a6afbe60697d1b461028d733f1380e22d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void executeFNegInst (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &amp; Dest, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a9810b36b4c4c17901d491f5aac030623">llvm::GenericValue::DoubleVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a5160197592bd1fc5c8cc81cd803e0629">llvm::GenericValue::FloatVal</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a8b2b94ef14cca14e32542e221b3303f5">llvm::Interpreter::visitUnaryOperator</a>.</p>

</div>
</div>

### executeFRemInst() {#ab2b2089ccf34571233f731db1c299b85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void executeFRemInst (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &amp; Dest, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a9810b36b4c4c17901d491f5aac030623">llvm::GenericValue::DoubleVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a5160197592bd1fc5c8cc81cd803e0629">llvm::GenericValue::FloatVal</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ad931a9b6a516452142c12592afe8968d">llvm::Interpreter::visitBinaryOperator</a>.</p>

</div>
</div>

### executeFSubInst() {#a1ba822e8185395389ff297d86335506b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void executeFSubInst (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &amp; Dest, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">Float</a>, <a href="#a3949efc1d5bca1a86dcf300cf11536ee">IMPLEMENT_BINARY_OPERATOR</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ad931a9b6a516452142c12592afe8968d">llvm::Interpreter::visitBinaryOperator</a>.</p>

</div>
</div>

### executeICMP\_EQ() {#ae7670586abfe3aed532c70997b0d4424}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeICMP_EQ (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac4e06ed051f3a169ce69957401c35978">IMPLEMENT_INTEGER_ICMP</a>, <a href="#a930b0c47dc8ca23c7c467b8818f9a6c6">IMPLEMENT_POINTER_ICMP</a>, <a href="#a1fbafd8ad5bbf8c85080bd1083b94318">IMPLEMENT_VECTOR_INTEGER_ICMP</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a382f8209946dc96b1cb2a30589c06f1c">llvm::Interpreter::visitICmpInst</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a562abb53521e5d5930bb086374da2628">llvm::Interpreter::visitSwitchInst</a>.</p>

</div>
</div>

### executeICMP\_NE() {#a908bbe72c94bd551dcbd394a8817c2d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeICMP_NE (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac4e06ed051f3a169ce69957401c35978">IMPLEMENT_INTEGER_ICMP</a>, <a href="#a930b0c47dc8ca23c7c467b8818f9a6c6">IMPLEMENT_POINTER_ICMP</a>, <a href="#a1fbafd8ad5bbf8c85080bd1083b94318">IMPLEMENT_VECTOR_INTEGER_ICMP</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a382f8209946dc96b1cb2a30589c06f1c">llvm::Interpreter::visitICmpInst</a>.</p>

</div>
</div>

### executeICMP\_SGE() {#a34085170841ce0d5eb1687c8cefd9234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeICMP_SGE (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac4e06ed051f3a169ce69957401c35978">IMPLEMENT_INTEGER_ICMP</a>, <a href="#a930b0c47dc8ca23c7c467b8818f9a6c6">IMPLEMENT_POINTER_ICMP</a>, <a href="#a1fbafd8ad5bbf8c85080bd1083b94318">IMPLEMENT_VECTOR_INTEGER_ICMP</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a382f8209946dc96b1cb2a30589c06f1c">llvm::Interpreter::visitICmpInst</a>.</p>

</div>
</div>

### executeICMP\_SGT() {#a2d592b5002f3855f9fa9f486a55087b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeICMP_SGT (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac4e06ed051f3a169ce69957401c35978">IMPLEMENT_INTEGER_ICMP</a>, <a href="#a930b0c47dc8ca23c7c467b8818f9a6c6">IMPLEMENT_POINTER_ICMP</a>, <a href="#a1fbafd8ad5bbf8c85080bd1083b94318">IMPLEMENT_VECTOR_INTEGER_ICMP</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a382f8209946dc96b1cb2a30589c06f1c">llvm::Interpreter::visitICmpInst</a>.</p>

</div>
</div>

### executeICMP\_SLE() {#a2f5002419dfa68ad8a3be90f9e591a1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeICMP_SLE (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac4e06ed051f3a169ce69957401c35978">IMPLEMENT_INTEGER_ICMP</a>, <a href="#a930b0c47dc8ca23c7c467b8818f9a6c6">IMPLEMENT_POINTER_ICMP</a>, <a href="#a1fbafd8ad5bbf8c85080bd1083b94318">IMPLEMENT_VECTOR_INTEGER_ICMP</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a382f8209946dc96b1cb2a30589c06f1c">llvm::Interpreter::visitICmpInst</a>.</p>

</div>
</div>

### executeICMP\_SLT() {#a0b809b83b0c40ad9dcb8bbd8ea4591a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeICMP_SLT (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac4e06ed051f3a169ce69957401c35978">IMPLEMENT_INTEGER_ICMP</a>, <a href="#a930b0c47dc8ca23c7c467b8818f9a6c6">IMPLEMENT_POINTER_ICMP</a>, <a href="#a1fbafd8ad5bbf8c85080bd1083b94318">IMPLEMENT_VECTOR_INTEGER_ICMP</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a382f8209946dc96b1cb2a30589c06f1c">llvm::Interpreter::visitICmpInst</a>.</p>

</div>
</div>

### executeICMP\_UGE() {#a0c84af3c90fae95a8ea40029ddceb3b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeICMP_UGE (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac4e06ed051f3a169ce69957401c35978">IMPLEMENT_INTEGER_ICMP</a>, <a href="#a930b0c47dc8ca23c7c467b8818f9a6c6">IMPLEMENT_POINTER_ICMP</a>, <a href="#a1fbafd8ad5bbf8c85080bd1083b94318">IMPLEMENT_VECTOR_INTEGER_ICMP</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a382f8209946dc96b1cb2a30589c06f1c">llvm::Interpreter::visitICmpInst</a>.</p>

</div>
</div>

### executeICMP\_UGT() {#a072f11ea1ef8304f96662d1f385f5ad3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeICMP_UGT (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac4e06ed051f3a169ce69957401c35978">IMPLEMENT_INTEGER_ICMP</a>, <a href="#a930b0c47dc8ca23c7c467b8818f9a6c6">IMPLEMENT_POINTER_ICMP</a>, <a href="#a1fbafd8ad5bbf8c85080bd1083b94318">IMPLEMENT_VECTOR_INTEGER_ICMP</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a382f8209946dc96b1cb2a30589c06f1c">llvm::Interpreter::visitICmpInst</a>.</p>

</div>
</div>

### executeICMP\_ULE() {#a826efd0d1d8bbe269183e89ea5514e2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeICMP_ULE (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac4e06ed051f3a169ce69957401c35978">IMPLEMENT_INTEGER_ICMP</a>, <a href="#a930b0c47dc8ca23c7c467b8818f9a6c6">IMPLEMENT_POINTER_ICMP</a>, <a href="#a1fbafd8ad5bbf8c85080bd1083b94318">IMPLEMENT_VECTOR_INTEGER_ICMP</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a382f8209946dc96b1cb2a30589c06f1c">llvm::Interpreter::visitICmpInst</a>.</p>

</div>
</div>

### executeICMP\_ULT() {#af9477a1cada9e071e78a65a75f09247b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeICMP_ULT (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac4e06ed051f3a169ce69957401c35978">IMPLEMENT_INTEGER_ICMP</a>, <a href="#a930b0c47dc8ca23c7c467b8818f9a6c6">IMPLEMENT_POINTER_ICMP</a>, <a href="#a1fbafd8ad5bbf8c85080bd1083b94318">IMPLEMENT_VECTOR_INTEGER_ICMP</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a382f8209946dc96b1cb2a30589c06f1c">llvm::Interpreter::visitICmpInst</a>.</p>

</div>
</div>

### executeSelectInst() {#a4f71481be990c1361b473eea6c18df11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue executeSelectInst (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src2, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Src3, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#aa46325f5b23e83bb49e497cfce2f1b89">llvm::GenericValue::AggregateVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a1df708fd8aa2d183afcafa641e96ccc1">llvm::Interpreter::visitSelectInst</a>.</p>

</div>
</div>

### getShiftAmount() {#ab9de4ecd5d07314b56d5a0d1fad6f6fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getShiftAmount (uint64_t orgShiftAmount, <a href="/web-llvm/docs/api/classes/llvm/apint">llvm::APInt</a> valueToShift)</td>
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



<p>Definition at line 1139 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afb65eef479f0473d0fe1666b80155237">llvm::NextPowerOf2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ac56427a25d7626e4b748e8fbf1fdf9bb">llvm::Interpreter::visitAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a39600b19581391dccc382a54d6b79be2">llvm::Interpreter::visitLShr</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#adaccb8a2292bd0d7fecec1c16d177cd3">llvm::Interpreter::visitShl</a>.</p>

</div>
</div>

### SetValue() {#aa43f5ded794bbaa78a7d7b3b72caed8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SetValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Val, <a href="/web-llvm/docs/api/structs/llvm/executioncontext">ExecutionContext</a> &amp; SF)</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a7e36a63781989accf846f2e78f510d33">llvm::Interpreter::callFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a6472f2a2e040373d958419bde7523539">createMemSetLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a1ce4069e58167789a23552d4cab66114">llvm::Interpreter::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ac56427a25d7626e4b748e8fbf1fdf9bb">llvm::Interpreter::visitAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ad931a9b6a516452142c12592afe8968d">llvm::Interpreter::visitBinaryOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#abd8ab3044cbed9d96925639c54ac89cb">llvm::Interpreter::visitBitCastInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a582723c984e76cf38ba855426a60a235">llvm::Interpreter::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a555a1a7ce9538b817e65c911ed7da13a">llvm::Interpreter::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a06c639b057f4b02e4ea274c3e059c95f">llvm::Interpreter::visitFCmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a9d6f9c796d975ed192c0b004feb0d181">llvm::Interpreter::visitFPExtInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ae8faf6742ce6199babb1b5072ae40da4">llvm::Interpreter::visitFPToSIInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a70ebc74064b9abcb424d33b3e8a1e95c">llvm::Interpreter::visitFPToUIInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ad6c27060516049d30db09aab83ce8e2a">llvm::Interpreter::visitFPTruncInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a7e0b0ae6ad80cac2ce881d61147d25ec">llvm::Interpreter::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a382f8209946dc96b1cb2a30589c06f1c">llvm::Interpreter::visitICmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a86b39d8533c9fd7c518a6ebc3456e6d1">llvm::Interpreter::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a47c795f3e83fbfbd37c1b890c850dbe7">llvm::Interpreter::visitInsertValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a2e92cc7536cb0d667a0225a25810af08">llvm::Interpreter::visitIntToPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a7d9427c6aacb65d962854ea8bfe5c23b">llvm::Interpreter::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a39600b19581391dccc382a54d6b79be2">llvm::Interpreter::visitLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a09f6cc56fdb2d7b2ea817665147c7d8d">llvm::Interpreter::visitPtrToIntInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a1df708fd8aa2d183afcafa641e96ccc1">llvm::Interpreter::visitSelectInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ac55fd7a63e2f2beeb7ed4ecc05305c5a">llvm::Interpreter::visitSExtInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#adaccb8a2292bd0d7fecec1c16d177cd3">llvm::Interpreter::visitShl</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a1023db1599beb0118dd1ffe91d85f172">llvm::Interpreter::visitShuffleVectorInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a05cde965fd9be8eab699f1fbfa661b9b">llvm::Interpreter::visitSIToFPInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a6187006e0146e42ba68ea7b0a36f8612">llvm::Interpreter::visitTruncInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a398c50e793136ad369479408206bb4a8">llvm::Interpreter::visitUIToFPInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a8b2b94ef14cca14e32542e221b3303f5">llvm::Interpreter::visitUnaryOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a54b80362711a465bb0430383cbf50837">llvm::Interpreter::visitVAArgInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a5ac2392669a11cf5fc17003be773c7d7">llvm::Interpreter::visitVACopyInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ab12c231bbdababc7fddf09a0c2825ae9">llvm::Interpreter::visitVAStartInst</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ae2cb4303f15332b4ecb8ae8cd9e2f2d0">llvm::Interpreter::visitZExtInst</a>.</p>

</div>
</div>

### STATISTIC() {#ac3e13c10a54f07060151d496cffde457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumDynamicInsts, "Number of dynamic <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> executed")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### PrintVolatile {#a748be8883cec545a336485a26d8fc097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PrintVolatile("interpreter-print-volatile", cl::Hidden, cl::desc("make the interpreter print every volatile load and store"))</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a7d9427c6aacb65d962854ea8bfe5c23b">llvm::Interpreter::visitLoadInst</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a552ef98be3146773854e33c8548d202b">llvm::Interpreter::visitStoreInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"interpreter"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### FLOAT\_VECTOR\_FUNCTION {#ae82dc0214067114dea1566497bd42c5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FLOAT_VECTOR_FUNCTION(OP, TY)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">      <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> (unsigned i = 0; i &lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">R.AggregateVal.size</a>(); ++i)          \
        R.AggregateVal[i].TY =                                      \
        Src1.AggregateVal[i].TY <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a> Src2.AggregateVal[i].TY;
</div>
</dd>
</dl>

<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### FLOAT\_VECTOR\_OP {#a1ecc89a903a39fa91e98829c7a768fb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FLOAT_VECTOR_OP(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  {                                         \
  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (cast&lt;<a href="/web-llvm/docs/api/classes/vectortype">VectorType</a>&gt;(Ty)-&gt;getElementType()-&gt;isFloatTy())            \
    <a href="#ae82dc0214067114dea1566497bd42c5e">FLOAT_VECTOR_FUNCTION</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, FloatVal)                               \
  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a0544c3fe466e421738dae463968b70ba">else</a> {                                                              \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (cast&lt;<a href="/web-llvm/docs/api/classes/vectortype">VectorType</a>&gt;(Ty)-&gt;getElementType()-&gt;isDoubleTy())         \
      <a href="#ae82dc0214067114dea1566497bd42c5e">FLOAT_VECTOR_FUNCTION</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, DoubleVal)                            \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a0544c3fe466e421738dae463968b70ba">else</a> {                                                            \
      dbgs() &lt;&lt; "Unhandled type <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a> instruction: " &lt;&lt; *Ty &lt;&lt; "\n"; \
      <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>(0);                                            \
    }                                                                 \
  }                                                                   \
}
</div>
</dd>
</dl>

<p>Definition at line 734 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ad931a9b6a516452142c12592afe8968d">llvm::Interpreter::visitBinaryOperator</a>.</p>

</div>
</div>

### IMPLEMENT\_BINARY\_OPERATOR {#a3949efc1d5bca1a86dcf300cf11536ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define IMPLEMENT_BINARY_OPERATOR(OP, TY)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">   case Type::TY##TyID: \
     Dest.TY##Val = Src1.TY##Val <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a> Src2.TY##Val; \
     break
</div>
</dd>
</dl>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>Referenced by <a href="#a46d49ce365aa2b814bb9b25f332757df">executeFAddInst</a>, <a href="#a2dcd6bdc8271cf5a7a963933e7a18c66">executeFDivInst</a>, <a href="#af8cce347f31a3057d0d8a61a4ade64e4">executeFMulInst</a> and <a href="#a1ba822e8185395389ff297d86335506b">executeFSubInst</a>.</p>

</div>
</div>

### IMPLEMENT\_FCMP {#ac86dae43d05947074538335c136d8286}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define IMPLEMENT_FCMP(OP, TY)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">   case Type::TY##TyID: \
     Dest.IntVal = <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>(1,Src1.TY##Val <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a> Src2.TY##Val); \
     break
</div>
</dd>
</dl>

<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>Referenced by <a href="#a53a0f3f250d2ad3ab79b96b2d7b12527">executeFCMP_OEQ</a>, <a href="#a0473b23318c3e81617e969e5d34b6c65">executeFCMP_OGE</a>, <a href="#a35b4530505dca524726752e6a20883e1">executeFCMP_OGT</a>, <a href="#a687130dc367d99c69d3c7c611169d6b6">executeFCMP_OLE</a>, <a href="#a88f7c3a00a5fc3920f305094bf381798">executeFCMP_OLT</a> and <a href="#ad84c8e547a3add8cc581d6fbec1ea5cb">executeFCMP_ONE</a>.</p>

</div>
</div>

### IMPLEMENT\_INTEGER\_ICMP {#ac4e06ed051f3a169ce69957401c35978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define IMPLEMENT_INTEGER_ICMP(OP, TY)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">   case Type::IntegerTyID:  \
      Dest.IntVal = <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>(1,<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">Src1.IntVal.OP</a>(Src2.IntVal)); \
      break;
</div>
</dd>
</dl>

<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>Referenced by <a href="#ae7670586abfe3aed532c70997b0d4424">executeICMP_EQ</a>, <a href="#a908bbe72c94bd551dcbd394a8817c2d7">executeICMP_NE</a>, <a href="#a34085170841ce0d5eb1687c8cefd9234">executeICMP_SGE</a>, <a href="#a2d592b5002f3855f9fa9f486a55087b2">executeICMP_SGT</a>, <a href="#a2f5002419dfa68ad8a3be90f9e591a1d">executeICMP_SLE</a>, <a href="#a0b809b83b0c40ad9dcb8bbd8ea4591a7">executeICMP_SLT</a>, <a href="#a0c84af3c90fae95a8ea40029ddceb3b0">executeICMP_UGE</a>, <a href="#a072f11ea1ef8304f96662d1f385f5ad3">executeICMP_UGT</a>, <a href="#a826efd0d1d8bbe269183e89ea5514e2f">executeICMP_ULE</a> and <a href="#af9477a1cada9e071e78a65a75f09247b">executeICMP_ULT</a>.</p>

</div>
</div>

### IMPLEMENT\_POINTER\_ICMP {#a930b0c47dc8ca23c7c467b8818f9a6c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define IMPLEMENT_POINTER_ICMP(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">   case Type::PointerTyID: \
      Dest.IntVal = <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>(1,(void*)(intptr_t)Src1.PointerVal <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a> \
                            (void*)(intptr_t)Src2.PointerVal); \
      break;
</div>
</dd>
</dl>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>Referenced by <a href="#ae7670586abfe3aed532c70997b0d4424">executeICMP_EQ</a>, <a href="#a908bbe72c94bd551dcbd394a8817c2d7">executeICMP_NE</a>, <a href="#a34085170841ce0d5eb1687c8cefd9234">executeICMP_SGE</a>, <a href="#a2d592b5002f3855f9fa9f486a55087b2">executeICMP_SGT</a>, <a href="#a2f5002419dfa68ad8a3be90f9e591a1d">executeICMP_SLE</a>, <a href="#a0b809b83b0c40ad9dcb8bbd8ea4591a7">executeICMP_SLT</a>, <a href="#a0c84af3c90fae95a8ea40029ddceb3b0">executeICMP_UGE</a>, <a href="#a072f11ea1ef8304f96662d1f385f5ad3">executeICMP_UGT</a>, <a href="#a826efd0d1d8bbe269183e89ea5514e2f">executeICMP_ULE</a> and <a href="#af9477a1cada9e071e78a65a75f09247b">executeICMP_ULT</a>.</p>

</div>
</div>

### IMPLEMENT\_SCALAR\_NANS {#a441661dba18aaac72417737b68cce3ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define IMPLEMENT_SCALAR_NANS(TY, X, Y)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (TY-&gt;isFloatTy()) {                                                    \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (X.FloatVal != X.FloatVal || Y.FloatVal != Y.FloatVal) {             \
      Dest.IntVal = <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>(1,false);                                         \
      return Dest;                                                          \
    }                                                                       \
  } <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a0544c3fe466e421738dae463968b70ba">else</a> {                                                                  \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (X.DoubleVal != X.DoubleVal || Y.DoubleVal != Y.DoubleVal) {         \
      Dest.IntVal = <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>(1,false);                                         \
      return Dest;                                                          \
    }                                                                       \
  }
</div>
</dd>
</dl>

<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>Referenced by <a href="#ad84c8e547a3add8cc581d6fbec1ea5cb">executeFCMP_ONE</a>.</p>

</div>
</div>

### IMPLEMENT\_UNORDERED {#a9c13a70fc317a045485f7a12c8855609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define IMPLEMENT_UNORDERED(TY, X, Y)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (TY-&gt;isFloatTy()) {                                                 \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (X.FloatVal != X.FloatVal || Y.FloatVal != Y.FloatVal) {          \
      Dest.IntVal = <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>(1,<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>);                                       \
      return Dest;                                                       \
    }                                                                    \
  } <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a0544c3fe466e421738dae463968b70ba">else</a> <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (X.DoubleVal != X.DoubleVal || Y.DoubleVal != Y.DoubleVal) { \
    Dest.IntVal = <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>(1,<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>);                                         \
    return Dest;                                                         \
  }
</div>
</dd>
</dl>

<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>Referenced by <a href="#adc7da546e2638a58b40f8236f43e91c0">executeFCMP_UEQ</a>, <a href="#a03c3b9faab810a8a847dee1c1024db92">executeFCMP_UGE</a>, <a href="#aed4e397ad7ab2921318cf474e0b8320e">executeFCMP_UGT</a>, <a href="#a1ca29b39b2e1fbf95a750c13d2035f61">executeFCMP_ULE</a>, <a href="#a8f7dd1881517874a4850e4d1cb970a66">executeFCMP_ULT</a> and <a href="#a42019dfdf44962124bfc3ed1e7dda826">executeFCMP_UNE</a>.</p>

</div>
</div>

### IMPLEMENT\_VAARG {#ab17082b5668396b9c47660397a72c0e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define IMPLEMENT_VAARG(TY)&nbsp;&nbsp;&nbsp;   case Type::TY##TyID: Dest.TY##Val = Src.TY##Val; break</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1726 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a54b80362711a465bb0430383cbf50837">llvm::Interpreter::visitVAArgInst</a>.</p>

</div>
</div>

### IMPLEMENT\_VECTOR\_FCMP {#a7ed001f6ad2ba58b6d619c555334c829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define IMPLEMENT_VECTOR_FCMP(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case Type::FixedVectorTyID:                                                  \
  case Type::ScalableVectorTyID:                                               \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (cast&lt;<a href="/web-llvm/docs/api/classes/vectortype">VectorType</a>&gt;(Ty)-&gt;getElementType()-&gt;isFloatTy()) {                 \
      <a href="#acb6c924a81110e476857a563b911073b">IMPLEMENT_VECTOR_FCMP_T</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">Float</a>);                                      \
    } <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a0544c3fe466e421738dae463968b70ba">else</a> {                                                                   \
      <a href="#acb6c924a81110e476857a563b911073b">IMPLEMENT_VECTOR_FCMP_T</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, Double);                                     \
    }
</div>
</dd>
</dl>

<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>Referenced by <a href="#a53a0f3f250d2ad3ab79b96b2d7b12527">executeFCMP_OEQ</a>, <a href="#a0473b23318c3e81617e969e5d34b6c65">executeFCMP_OGE</a>, <a href="#a35b4530505dca524726752e6a20883e1">executeFCMP_OGT</a>, <a href="#a687130dc367d99c69d3c7c611169d6b6">executeFCMP_OLE</a>, <a href="#a88f7c3a00a5fc3920f305094bf381798">executeFCMP_OLT</a> and <a href="#ad84c8e547a3add8cc581d6fbec1ea5cb">executeFCMP_ONE</a>.</p>

</div>
</div>

### IMPLEMENT\_VECTOR\_FCMP\_T {#acb6c924a81110e476857a563b911073b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define IMPLEMENT_VECTOR_FCMP_T(OP, TY)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">Src1.AggregateVal.size</a>() == <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">Src2.AggregateVal.size</a>());     \
  Dest.AggregateVal.resize( <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">Src1.AggregateVal.size</a>() );             \
  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a>( uint32_t _i=0;_i&lt;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">Src1.AggregateVal.size</a>();_i++)              \
    Dest.AggregateVal[_i].IntVal = <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>(1,                         \
    Src1.AggregateVal[_i].TY##Val <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a> Src2.AggregateVal[_i].TY##Val);\
  break;
</div>
</dd>
</dl>

<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### IMPLEMENT\_VECTOR\_INTEGER\_ICMP {#a1fbafd8ad5bbf8c85080bd1083b94318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define IMPLEMENT_VECTOR_INTEGER_ICMP(OP, TY)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case Type::FixedVectorTyID:                                                  \
  case Type::ScalableVectorTyID: {                                             \
    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">Src1.AggregateVal.size</a>() == <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">Src2.AggregateVal.size</a>());              \
    Dest.AggregateVal.resize(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">Src1.AggregateVal.size</a>());                        \
    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> (uint32_t _i = 0; _i &lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">Src1.AggregateVal.size</a>(); _i++)                 \
      Dest.AggregateVal[_i].IntVal = <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>(                                    \
          1, Src1.AggregateVal[_i].<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">IntVal.OP</a>(Src2.AggregateVal[_i].IntVal));   \
  } break;
</div>
</dd>
</dl>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>Referenced by <a href="#ae7670586abfe3aed532c70997b0d4424">executeICMP_EQ</a>, <a href="#a908bbe72c94bd551dcbd394a8817c2d7">executeICMP_NE</a>, <a href="#a34085170841ce0d5eb1687c8cefd9234">executeICMP_SGE</a>, <a href="#a2d592b5002f3855f9fa9f486a55087b2">executeICMP_SGT</a>, <a href="#a2f5002419dfa68ad8a3be90f9e591a1d">executeICMP_SLE</a>, <a href="#a0b809b83b0c40ad9dcb8bbd8ea4591a7">executeICMP_SLT</a>, <a href="#a0c84af3c90fae95a8ea40029ddceb3b0">executeICMP_UGE</a>, <a href="#a072f11ea1ef8304f96662d1f385f5ad3">executeICMP_UGT</a>, <a href="#a826efd0d1d8bbe269183e89ea5514e2f">executeICMP_ULE</a> and <a href="#af9477a1cada9e071e78a65a75f09247b">executeICMP_ULT</a>.</p>

</div>
</div>

### IMPLEMENT\_VECTOR\_UNORDERED {#aa9a34d26aaadbcb4dde31f56c68e9dc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define IMPLEMENT_VECTOR_UNORDERED(TY, X, Y, FUNC)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (TY-&gt;isVectorTy()) {                                                      \
    <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> DestMask = Dest;                                              \
    Dest = FUNC(Src1, Src2, Ty);                                               \
    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> (size_t _i = 0; _i &lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">Src1.AggregateVal.size</a>(); _i++)                   \
      <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (DestMask.AggregateVal[_i].IntVal == <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)                            \
        Dest.AggregateVal[_i].IntVal = <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>(1, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>);                         \
    return Dest;                                                               \
  }
</div>
</dd>
</dl>

<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>Referenced by <a href="#adc7da546e2638a58b40f8236f43e91c0">executeFCMP_UEQ</a>, <a href="#a03c3b9faab810a8a847dee1c1024db92">executeFCMP_UGE</a>, <a href="#aed4e397ad7ab2921318cf474e0b8320e">executeFCMP_UGT</a>, <a href="#a1ca29b39b2e1fbf95a750c13d2035f61">executeFCMP_ULE</a>, <a href="#a8f7dd1881517874a4850e4d1cb970a66">executeFCMP_ULT</a> and <a href="#a42019dfdf44962124bfc3ed1e7dda826">executeFCMP_UNE</a>.</p>

</div>
</div>

### INTEGER\_VECTOR\_FUNCTION {#a772ad021946611dccd72512addffaa8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INTEGER_VECTOR_FUNCTION(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> (unsigned i = 0; i &lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">R.AggregateVal.size</a>(); ++i)           \
      R.AggregateVal[i].IntVal =                                   \
      Src1.AggregateVal[i].<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">IntVal.OP</a>(Src2.AggregateVal[i].IntVal);
</div>
</dd>
</dl>

<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ad931a9b6a516452142c12592afe8968d">llvm::Interpreter::visitBinaryOperator</a>.</p>

</div>
</div>

### INTEGER\_VECTOR\_OPERATION {#a35d25f42428e57ca9b363fe5c8ea2b74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INTEGER_VECTOR_OPERATION(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> (unsigned i = 0; i &lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">R.AggregateVal.size</a>(); ++i)           \
      R.AggregateVal[i].IntVal =                                   \
      Src1.AggregateVal[i].IntVal <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a> Src2.AggregateVal[i].IntVal;
</div>
</dd>
</dl>

<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ad931a9b6a516452142c12592afe8968d">llvm::Interpreter::visitBinaryOperator</a>.</p>

</div>
</div>

### MASK\_VECTOR\_NANS {#a7870210eb9766fdb8b9e8c2d3bbe7424}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MASK_VECTOR_NANS(TY, X, Y, FLAG)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (TY-&gt;isVectorTy()) {                                                   \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (cast&lt;<a href="/web-llvm/docs/api/classes/vectortype">VectorType</a>&gt;(TY)-&gt;getElementType()-&gt;isFloatTy()) {              \
      <a href="#a3cdbcca6a13731e5efb6848f9ca0da6e">MASK_VECTOR_NANS_T</a>(<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">Float</a>, FLAG)                                 \
    } <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a0544c3fe466e421738dae463968b70ba">else</a> {                                                                \
      <a href="#a3cdbcca6a13731e5efb6848f9ca0da6e">MASK_VECTOR_NANS_T</a>(<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>, Double, FLAG)                                \
    }                                                                       \
  }                                                                         \
</div>
</dd>
</dl>

<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>Referenced by <a href="#ad84c8e547a3add8cc581d6fbec1ea5cb">executeFCMP_ONE</a>, <a href="#adc7da546e2638a58b40f8236f43e91c0">executeFCMP_UEQ</a>, <a href="#a03c3b9faab810a8a847dee1c1024db92">executeFCMP_UGE</a>, <a href="#aed4e397ad7ab2921318cf474e0b8320e">executeFCMP_UGT</a>, <a href="#a1ca29b39b2e1fbf95a750c13d2035f61">executeFCMP_ULE</a>, <a href="#a8f7dd1881517874a4850e4d1cb970a66">executeFCMP_ULT</a> and <a href="#a42019dfdf44962124bfc3ed1e7dda826">executeFCMP_UNE</a>.</p>

</div>
</div>

### MASK\_VECTOR\_NANS\_T {#a3cdbcca6a13731e5efb6848f9ca0da6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MASK_VECTOR_NANS_T(X, Y, TZ, FLAG)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">X.AggregateVal.size</a>() == <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">Y.AggregateVal.size</a>());                   \
  Dest.AggregateVal.resize( <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">X.AggregateVal.size</a>() );                        \
  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a>( uint32_t _i=0;_i&lt;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">X.AggregateVal.size</a>();_i++) {                       \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (X.AggregateVal[_i].TZ##Val != X.AggregateVal[_i].TZ##Val ||         \
        Y.AggregateVal[_i].TZ##Val != Y.AggregateVal[_i].TZ##Val)           \
      Dest.AggregateVal[_i].IntVal = <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>(1,FLAG);                         \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a0544c3fe466e421738dae463968b70ba">else</a>  {                                                                 \
      Dest.AggregateVal[_i].IntVal = <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>(1,!FLAG);                        \
    }                                                                       \
  }
</div>
</dd>
</dl>

<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
