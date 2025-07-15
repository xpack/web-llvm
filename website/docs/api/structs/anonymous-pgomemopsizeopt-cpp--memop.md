---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-pgomemopsizeopt-cpp-/memop
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MemOp` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{PGOMemOPSizeOpt.cpp}::MemOp { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74d689ad39bc17ef20951ea740b324af">MemOp</a> (MemIntrinsic *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a901aa08c739540bcbf5c1c38b68ff473">MemOp</a> (CallInst *CI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memintrinsic">MemIntrinsic</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b4f5f39156576e806083f17ad8f807a">asMI</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa105e0a30c68c011d96632e8eb719c46">asCI</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-pgomemopsizeopt-cpp-/memop">MemOp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31dbd7b46e97e9f3b170569e89059b82">clone</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4677641f25f05369e308d58d14f2fbb6">getLength</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a889b79117ef13301b2b29a1791f4e540">setLength</a> (Value *Length)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2f49bc98075eef87eafaee154b7eac5">getFuncName</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c186e93bec38698d2d376c6eefaf5bb">isMemmove</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c8bd1558d1b481693131d443c5669e2">isMemcmp</a> (TargetLibraryInfo &amp;TLI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8a4bb85b0732df6c45f43d726c63011">isBcmp</a> (TargetLibraryInfo &amp;TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abccd022ea8583eb828326120c036643f">getName</a> (TargetLibraryInfo &amp;TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c296b31d6adebb56f4343afe15c91fe">I</a></td>
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


<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgomemopsizeopt-cpp">PGOMemOPSizeOpt.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MemOp() {#a74d689ad39bc17ef20951ea740b324af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PGOMemOPSizeOpt.cpp}::MemOp::MemOp (<a href="/web-llvm/docs/api/classes/llvm/memintrinsic">MemIntrinsic</a> * MI)</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgomemopsizeopt-cpp">PGOMemOPSizeOpt.cpp</a>.</p>


<p>References <a href="#a3c296b31d6adebb56f4343afe15c91fe">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a31dbd7b46e97e9f3b170569e89059b82">clone</a>.</p>

</div>
</div>

### MemOp() {#a901aa08c739540bcbf5c1c38b68ff473}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PGOMemOPSizeOpt.cpp}::MemOp::MemOp (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgomemopsizeopt-cpp">PGOMemOPSizeOpt.cpp</a>.</p>


<p>Reference <a href="#a3c296b31d6adebb56f4343afe15c91fe">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### asCI() {#aa105e0a30c68c011d96632e8eb719c46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * anonymous{PGOMemOPSizeOpt.cpp}::MemOp::asCI ()</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgomemopsizeopt-cpp">PGOMemOPSizeOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a3c296b31d6adebb56f4343afe15c91fe">I</a>.</p>


<p>Referenced by <a href="#a31dbd7b46e97e9f3b170569e89059b82">clone</a>, <a href="#ad2f49bc98075eef87eafaee154b7eac5">getFuncName</a>, <a href="#a4677641f25f05369e308d58d14f2fbb6">getLength</a>, <a href="#abccd022ea8583eb828326120c036643f">getName</a>, <a href="#ab8a4bb85b0732df6c45f43d726c63011">isBcmp</a>, <a href="#a8c8bd1558d1b481693131d443c5669e2">isMemcmp</a> and <a href="#a889b79117ef13301b2b29a1791f4e540">setLength</a>.</p>

</div>
</div>

### asMI() {#a8b4f5f39156576e806083f17ad8f807a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemIntrinsic * anonymous{PGOMemOPSizeOpt.cpp}::MemOp::asMI ()</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgomemopsizeopt-cpp">PGOMemOPSizeOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#a3c296b31d6adebb56f4343afe15c91fe">I</a>.</p>


<p>Referenced by <a href="#a31dbd7b46e97e9f3b170569e89059b82">clone</a>, <a href="#ad2f49bc98075eef87eafaee154b7eac5">getFuncName</a>, <a href="#a4677641f25f05369e308d58d14f2fbb6">getLength</a>, <a href="#abccd022ea8583eb828326120c036643f">getName</a>, <a href="#ab8a4bb85b0732df6c45f43d726c63011">isBcmp</a>, <a href="#a8c8bd1558d1b481693131d443c5669e2">isMemcmp</a>, <a href="#a4c186e93bec38698d2d376c6eefaf5bb">isMemmove</a> and <a href="#a889b79117ef13301b2b29a1791f4e540">setLength</a>.</p>

</div>
</div>

### clone() {#a31dbd7b46e97e9f3b170569e89059b82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemOp anonymous{PGOMemOPSizeOpt.cpp}::MemOp::clone ()</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgomemopsizeopt-cpp">PGOMemOPSizeOpt.cpp</a>.</p>


<p>References <a href="#aa105e0a30c68c011d96632e8eb719c46">asCI</a>, <a href="#a8b4f5f39156576e806083f17ad8f807a">asMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a31dbd7b46e97e9f3b170569e89059b82">clone</a>, <a href="#a74d689ad39bc17ef20951ea740b324af">MemOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a31dbd7b46e97e9f3b170569e89059b82">clone</a>.</p>

</div>
</div>

### getFuncName() {#ad2f49bc98075eef87eafaee154b7eac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{PGOMemOPSizeOpt.cpp}::MemOp::getFuncName ()</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgomemopsizeopt-cpp">PGOMemOPSizeOpt.cpp</a>.</p>


<p>References <a href="#aa105e0a30c68c011d96632e8eb719c46">asCI</a>, <a href="#a8b4f5f39156576e806083f17ad8f807a">asMI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getLength() {#a4677641f25f05369e308d58d14f2fbb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{PGOMemOPSizeOpt.cpp}::MemOp::getLength ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgomemopsizeopt-cpp">PGOMemOPSizeOpt.cpp</a>.</p>


<p>References <a href="#aa105e0a30c68c011d96632e8eb719c46">asCI</a>, <a href="#a8b4f5f39156576e806083f17ad8f807a">asMI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getName() {#abccd022ea8583eb828326120c036643f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * anonymous{PGOMemOPSizeOpt.cpp}::MemOp::getName (<a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI)</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgomemopsizeopt-cpp">PGOMemOPSizeOpt.cpp</a>.</p>


<p>References <a href="#aa105e0a30c68c011d96632e8eb719c46">asCI</a>, <a href="#a8b4f5f39156576e806083f17ad8f807a">asMI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a97cfbbed8869e3582142012a071a9052">llvm::TargetLibraryInfo::getLibFunc</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-pgomemopsizeopt-cpp-/#ab0f0ab659e4ba581082457ae457fce52">anonymous{PGOMemOPSizeOpt.cpp}::getMIName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isBcmp() {#ab8a4bb85b0732df6c45f43d726c63011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PGOMemOPSizeOpt.cpp}::MemOp::isBcmp (<a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgomemopsizeopt-cpp">PGOMemOPSizeOpt.cpp</a>.</p>


<p>References <a href="#aa105e0a30c68c011d96632e8eb719c46">asCI</a>, <a href="#a8b4f5f39156576e806083f17ad8f807a">asMI</a> and <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a97cfbbed8869e3582142012a071a9052">llvm::TargetLibraryInfo::getLibFunc</a>.</p>

</div>
</div>

### isMemcmp() {#a8c8bd1558d1b481693131d443c5669e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PGOMemOPSizeOpt.cpp}::MemOp::isMemcmp (<a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgomemopsizeopt-cpp">PGOMemOPSizeOpt.cpp</a>.</p>


<p>References <a href="#aa105e0a30c68c011d96632e8eb719c46">asCI</a>, <a href="#a8b4f5f39156576e806083f17ad8f807a">asMI</a> and <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a97cfbbed8869e3582142012a071a9052">llvm::TargetLibraryInfo::getLibFunc</a>.</p>

</div>
</div>

### isMemmove() {#a4c186e93bec38698d2d376c6eefaf5bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PGOMemOPSizeOpt.cpp}::MemOp::isMemmove ()</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgomemopsizeopt-cpp">PGOMemOPSizeOpt.cpp</a>.</p>


<p>References <a href="#a8b4f5f39156576e806083f17ad8f807a">asMI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### setLength() {#a889b79117ef13301b2b29a1791f4e540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PGOMemOPSizeOpt.cpp}::MemOp::setLength (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Length)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgomemopsizeopt-cpp">PGOMemOPSizeOpt.cpp</a>.</p>


<p>References <a href="#aa105e0a30c68c011d96632e8eb719c46">asCI</a>, <a href="#a8b4f5f39156576e806083f17ad8f807a">asMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### I {#a3c296b31d6adebb56f4343afe15c91fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{PGOMemOPSizeOpt.cpp}::MemOp::I</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgomemopsizeopt-cpp">PGOMemOPSizeOpt.cpp</a>.</p>


<p>Referenced by <a href="#aa105e0a30c68c011d96632e8eb719c46">asCI</a>, <a href="#a8b4f5f39156576e806083f17ad8f807a">asMI</a>, <a href="#a901aa08c739540bcbf5c1c38b68ff473">MemOp</a> and <a href="#a74d689ad39bc17ef20951ea740b324af">MemOp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgomemopsizeopt-cpp">PGOMemOPSizeOpt.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
