---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/optimizationlevel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `OptimizationLevel` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::OptimizationLevel { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">llvm/Passes/OptimizationLevel.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fde7b3b9f2a8c78d09bed66bc70179e">OptimizationLevel</a> ()=default</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9bc6dfb6c120b6b452815984cb976b3">OptimizationLevel</a> (unsigned SpeedLevel, unsigned SizeLevel)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15d421eddeb112ae94ec5cd9a7c80564">operator==</a> (const OptimizationLevel &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f1296b820d60dccd2a6bae2ac4fd5e4">operator!=</a> (const OptimizationLevel &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8b4922e348da3964aace032c1da4108">isOptimizingForSpeed</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e2715d84143938c4eea797507559408">isOptimizingForSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a979da278e42c9db7dc7cf79de09109cc">getSpeedupLevel</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e8011309a2b8805bced360da3e77186">getSizeLevel</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5123daf1907d46647c6c911f132737b">SpeedLevel</a> = 2</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52bcaee89d8155da88a7eba8c6d5384a">SizeLevel</a> = 0</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ca9e4f5478a77fa91fc56e1f1f6ba24">O0</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable as many optimizations as possible. <a href="#a6ca9e4f5478a77fa91fc56e1f1f6ba24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfab17afad8d19eb90de02e684900ccd">O1</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize quickly without destroying debuggability. <a href="#acfab17afad8d19eb90de02e684900ccd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c0836ff9219a0b737a11979991c3389">O2</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize for fast execution as much as possible without triggering significant incremental compile time or code size growth. <a href="#a9c0836ff9219a0b737a11979991c3389">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a097296a5feaefc188dafa71b19204714">O3</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize for fast execution as much as possible. <a href="#a097296a5feaefc188dafa71b19204714">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73679792a87ec44543a1cc09a5d8c3cc">Os</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to <span class="doxyComputerOutput">O2</span> but tries to optimize for small code size instead of fast execution without triggering significant incremental execution time slowdowns. <a href="#a73679792a87ec44543a1cc09a5d8c3cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e916712888d6a2d3952834c126460e7">Oz</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A very specialized mode that will optimize for code size at any and all costs. <a href="#a1e916712888d6a2d3952834c126460e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">OptimizationLevel.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OptimizationLevel() {#a2fde7b3b9f2a8c78d09bed66bc70179e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OptimizationLevel::OptimizationLevel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">OptimizationLevel.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### OptimizationLevel() {#ac9bc6dfb6c120b6b452815984cb976b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OptimizationLevel::OptimizationLevel (unsigned SpeedLevel, unsigned SizeLevel)</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">OptimizationLevel.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a8f1296b820d60dccd2a6bae2ac4fd5e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OptimizationLevel::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> &amp; Other)</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">OptimizationLevel.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator==() {#a15d421eddeb112ae94ec5cd9a7c80564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OptimizationLevel::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> &amp; Other)</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">OptimizationLevel.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getSizeLevel() {#a6e8011309a2b8805bced360da3e77186}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::OptimizationLevel::getSizeLevel ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">OptimizationLevel.h</a>.</p>

</div>
</div>

### getSpeedupLevel() {#a979da278e42c9db7dc7cf79de09109cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::OptimizationLevel::getSpeedupLevel ()</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">OptimizationLevel.h</a>.</p>

</div>
</div>

### isOptimizingForSize() {#a1e2715d84143938c4eea797507559408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OptimizationLevel::isOptimizingForSize ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">OptimizationLevel.h</a>.</p>

</div>
</div>

### isOptimizingForSpeed() {#ac8b4922e348da3964aace032c1da4108}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OptimizationLevel::isOptimizingForSpeed ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">OptimizationLevel.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### SizeLevel {#a52bcaee89d8155da88a7eba8c6d5384a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::OptimizationLevel::SizeLevel = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">OptimizationLevel.h</a>.</p>

</div>
</div>

### SpeedLevel {#ad5123daf1907d46647c6c911f132737b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::OptimizationLevel::SpeedLevel = 2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">OptimizationLevel.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### O0 {#a6ca9e4f5478a77fa91fc56e1f1f6ba24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const OptimizationLevel OptimizationLevel::O0</td>
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

<p>Disable as many optimizations as possible.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
     0,
     0}
</div>
</dd>
</dl>


<p>This doesn't completely disable the optimizer in all cases, for example always_inline functions can be required to be inlined for correctness.</p>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">OptimizationLevel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ad4548cd9e4b6358214f2e34e5e56112e">llvm::PassBuilder::buildFatLTODefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9501d22da3319c387a0a617fc4ffcc31">llvm::PassBuilder::buildFunctionSimplificationPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a08240a2eba496a292cec022c5093f621">llvm::PassBuilder::buildInlinerPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab319565ffed9e4cb2aff1aa78847ec2d">llvm::PassBuilder::buildLTODefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab53586b47722fa95d93ae8b06f734742">llvm::PassBuilder::buildModuleInlinerPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ad6f258d31ffa2d2e4dfaf990ba596d0d">llvm::PassBuilder::buildModuleSimplificationPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a94e03b8856e739853a1419da126f1758">llvm::PassBuilder::buildO0DefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a546f4259efb4e1629d1d14b8757c52c4">llvm::PassBuilder::buildPerModuleDefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab7d260f2f928c81a2d225f2d1aafad0e">llvm::PassBuilder::buildThinLTODefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a2832cb00a6c94208b4a06696eeeabf99">llvm::PassBuilder::buildThinLTOPreLinkDefaultPipeline</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae1b1fc686e5285c37b8f51cab4d213f0">optimizeModule</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#af05832a87891b7d9d07bce3c339bc934">anonymous{PassBuilder.cpp}::parseFunctionSimplificationPipelineOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#a9e4f6112c778d883860155c39c4d3594">parseOptLevel</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#ab727dbb342900913787fc58840a3c002">llvm::AMDGPUTargetMachine::registerPassBuilderCallbacks</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### O1 {#acfab17afad8d19eb90de02e684900ccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const OptimizationLevel OptimizationLevel::O1</td>
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

<p>Optimize quickly without destroying debuggability.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
     1,
     0}
</div>
</dd>
</dl>


<p>This level is tuned to produce a result from the optimizer as quickly as possible and to avoid destroying debuggability. This tends to result in a very good development mode where the compiled code will be immediately executed as part of testing. As a consequence, where possible, we would like to produce efficient-to-execute code, but not if it significantly slows down compilation or would prevent even basic debugging of the resulting binary.</p>


<p>As an example, complex loop transformations such as versioning, vectorization, or fusion don't make sense here due to the degree to which the executed code differs from the source code, and the compile time cost.</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">OptimizationLevel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab319565ffed9e4cb2aff1aa78847ec2d">llvm::PassBuilder::buildLTODefaultPipeline</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae1b1fc686e5285c37b8f51cab4d213f0">optimizeModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#a9e4f6112c778d883860155c39c4d3594">parseOptLevel</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#ab727dbb342900913787fc58840a3c002">llvm::AMDGPUTargetMachine::registerPassBuilderCallbacks</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### O2 {#a9c0836ff9219a0b737a11979991c3389}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const OptimizationLevel OptimizationLevel::O2</td>
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

<p>Optimize for fast execution as much as possible without triggering significant incremental compile time or code size growth.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
     2,
     0}
</div>
</dd>
</dl>


<p>The key idea is that optimizations at this level should "pay for
themselves". So if an optimization increases compile time by 5% or increases code size by 5% for a particular benchmark, that benchmark should also be one which sees a 5% runtime improvement. If the compile time or code size penalties happen on average across a diverse range of LLVM users' benchmarks, then the improvements should as well.</p>


<p>And no matter what, the compile time needs to not grow superlinearly with the size of input to LLVM so that users can control the runtime of the optimizer in this mode.</p>


<p>This is expected to be a good default optimization level for the vast majority of users.</p>


<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">OptimizationLevel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a08240a2eba496a292cec022c5093f621">llvm::PassBuilder::buildInlinerPipeline</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae1b1fc686e5285c37b8f51cab4d213f0">optimizeModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#a9e4f6112c778d883860155c39c4d3594">parseOptLevel</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### O3 {#a097296a5feaefc188dafa71b19204714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const OptimizationLevel OptimizationLevel::O3</td>
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

<p>Optimize for fast execution as much as possible.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
     3,
     0}
</div>
</dd>
</dl>


<p>This mode is significantly more aggressive in trading off compile time and code size to get execution time improvements. The core idea is that this mode should include any optimization that helps execution time on balance across a diverse collection of benchmarks, even if it increases code size or compile time for some benchmarks without corresponding improvements to execution time.</p>


<p>Despite being willing to trade more compile time off to get improved execution time, this mode still tries to avoid superlinear growth in order to make even significantly slower compile times at least scale reasonably. This does not preclude very substantial constant factor costs though.</p>


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">OptimizationLevel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9501d22da3319c387a0a617fc4ffcc31">llvm::PassBuilder::buildFunctionSimplificationPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a08240a2eba496a292cec022c5093f621">llvm::PassBuilder::buildInlinerPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#adf20f88f2a71fd5cd08708b9da72979a">llvm::PassBuilder::buildModuleOptimizationPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ad6f258d31ffa2d2e4dfaf990ba596d0d">llvm::PassBuilder::buildModuleSimplificationPipeline</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae1b1fc686e5285c37b8f51cab4d213f0">optimizeModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#a9e4f6112c778d883860155c39c4d3594">parseOptLevel</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### Os {#a73679792a87ec44543a1cc09a5d8c3cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const OptimizationLevel OptimizationLevel::Os</td>
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

<p>Similar to <span class="doxyComputerOutput">O2</span> but tries to optimize for small code size instead of fast execution without triggering significant incremental execution time slowdowns.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
     2,
     1}
</div>
</dd>
</dl>


<p>The logic here is exactly the same as <span class="doxyComputerOutput">O2</span>, but with code size and execution time metrics swapped.</p>


<p>A consequence of the different core goal is that this should in general produce substantially smaller executables that still run in a reasonable amount of time.</p>


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">OptimizationLevel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab319565ffed9e4cb2aff1aa78847ec2d">llvm::PassBuilder::buildLTODefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ad6f258d31ffa2d2e4dfaf990ba596d0d">llvm::PassBuilder::buildModuleSimplificationPipeline</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#a9e4f6112c778d883860155c39c4d3594">parseOptLevel</a>.</p>

</div>
</div>

### Oz {#a1e916712888d6a2d3952834c126460e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const OptimizationLevel OptimizationLevel::Oz</td>
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

<p>A very specialized mode that will optimize for code size at any and all costs.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
     2,
     2}
</div>
</dd>
</dl>


<p>This is useful primarily when there are absolute size limitations and any effort taken to reduce the size is worth it regardless of the execution time impact. You should expect this level to produce rather slow, but very small, code.</p>


<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">OptimizationLevel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9501d22da3319c387a0a617fc4ffcc31">llvm::PassBuilder::buildFunctionSimplificationPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab319565ffed9e4cb2aff1aa78847ec2d">llvm::PassBuilder::buildLTODefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#adf20f88f2a71fd5cd08708b9da72979a">llvm::PassBuilder::buildModuleOptimizationPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ad6f258d31ffa2d2e4dfaf990ba596d0d">llvm::PassBuilder::buildModuleSimplificationPipeline</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#a9e4f6112c778d883860155c39c4d3594">parseOptLevel</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">OptimizationLevel.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
