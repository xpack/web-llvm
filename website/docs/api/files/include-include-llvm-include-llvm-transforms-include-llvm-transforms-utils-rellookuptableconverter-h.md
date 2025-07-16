---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/rellookuptableconverter-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `RelLookupTableConverter.h` File Reference

<p>This file implements relative lookup table converter that converts lookup tables to relative lookup tables to make them PIC-friendly. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/rellookuptableconverterpass">RelLookupTableConverterPass</a></td>
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

<p>This file implements relative lookup table converter that converts lookup tables to relative lookup tables to make them PIC-friendly.</p>


<p>Switch lookup table example: @switch.table.foo = private unnamed_addr constant [3 x i8*] [ i8* getelementptr inbounds ([5 x i8], [5 x i8]* .str, i64 0, i64 0), i8* getelementptr inbounds ([4 x i8], [4 x i8]* .str.1, i64 0, i64 0), i8* getelementptr inbounds ([4 x i8], [4 x i8]* .str.2, i64 0, i64 0) ], align 8</p>


<p>switch.lookup: %1 = sext i32 cond to i64 switch.gep = getelementptr inbounds [3 x i8*], [3 x i8*]* @switch.table.foo, i64 0, i64 %1 switch.load = load i8*, i8** switch.gep, align 8 ret i8* switch.load</p>


<p>Switch lookup table will become a relative lookup table that consists of relative offsets.</p>


<p>@reltable.foo = private unnamed_addr constant [3 x i32] [ i32 trunc (i64 sub (i64 ptrtoint ([5 x i8]* .str to i64), i64 ptrtoint ([3 x i32]* @reltable.foo to i64)) to i32), i32 trunc (i64 sub (i64 ptrtoint ([4 x i8]* .str.1 to i64), i64 ptrtoint ([3 x i32]* @reltable.foo to i64)) to i32), i32 trunc (i64 sub (i64 ptrtoint ([4 x i8]* .str.2 to i64), i64 ptrtoint ([3 x i32]* @reltable.foo to i64)) to i32) ], align 4</p>


<p>IR after converting to a relative lookup table: switch.lookup: %1 = sext i32 cond to i64 reltable.shift = shl i64 %1, 2 reltable.intrinsic = call i8* @llvm.load.relative.i64( i8* bitcast ([3 x i32]* @reltable.foo to i8*), i64 reltable.shift) ret i8* reltable.intrinsic</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
