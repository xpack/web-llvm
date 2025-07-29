---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/outlinedhashtreerecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `OutlinedHashTreeRecord` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::OutlinedHashTreeRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">llvm/CGData/OutlinedHashTreeRecord.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9860e6d3634ffb50b571251b43052b46">OutlinedHashTreeRecord</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34c5e9a476f387121faac69d2045cb12">OutlinedHashTreeRecord</a> (std::unique_ptr&lt; OutlinedHashTree &gt; HashTree)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74ae6e240a1760c68a807fd885606fe6">serialize</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serialize the outlined hash tree to a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>. <a href="#a74ae6e240a1760c68a807fd885606fe6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c9fcdfa14dafa4bf635b6bdd88e0c77">deserialize</a> (const unsigned char *&amp;Ptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deserialize the outlined hash tree from a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>. <a href="#a2c9fcdfa14dafa4bf635b6bdd88e0c77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a016492643cfefde4ce1fab18d0c8cfd8">serializeYAML</a> (yaml::Output &amp;YOS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serialize the outlined hash tree to a YAML stream. <a href="#a016492643cfefde4ce1fab18d0c8cfd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2224262c0507515a54edc38eb71d693c">deserializeYAML</a> (yaml::Input &amp;YIS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deserialize the outlined hash tree from a YAML stream. <a href="#a2224262c0507515a54edc38eb71d693c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4486d597859e5cabe3b4a691a4bb5ee">merge</a> (const OutlinedHashTreeRecord &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge the other outlined hash tree into this one. <a href="#ab4486d597859e5cabe3b4a691a4bb5ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e5e2f09e5c13dfc26257ff0d02f3f86">empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8538f41cea55ce9f22b2c72bfb7b1874">print</a> (raw_ostream &amp;OS=llvm::errs()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the outlined hash tree in a YAML format. <a href="#a8538f41cea55ce9f22b2c72bfb7b1874">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31079d22c3b163ed90eba3679919bb6b">convertToStableData</a> (IdHashNodeStableMapTy &amp;IdNodeStableMap) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert the outlined hash tree to stable data. <a href="#a31079d22c3b163ed90eba3679919bb6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a976662dddace2ecb39011465c19720">convertFromStableData</a> (const IdHashNodeStableMapTy &amp;IdNodeStableMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert the stable data back to the outlined hash tree. <a href="#a6a976662dddace2ecb39011465c19720">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a959a2066fb03b6af9f7ddd79bc1f5004">HashTree</a></td>
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


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OutlinedHashTreeRecord() {#a9860e6d3634ffb50b571251b43052b46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OutlinedHashTreeRecord::OutlinedHashTreeRecord ()</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a>.</p>


<p>Reference <a href="#a959a2066fb03b6af9f7ddd79bc1f5004">HashTree</a>.</p>


<p>Referenced by <a href="#ab4486d597859e5cabe3b4a691a4bb5ee">merge</a>.</p>

</div>
</div>

### OutlinedHashTreeRecord() {#a34c5e9a476f387121faac69d2045cb12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OutlinedHashTreeRecord::OutlinedHashTreeRecord (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a> &gt; HashTree)</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a>.</p>


<p>References <a href="#a959a2066fb03b6af9f7ddd79bc1f5004">HashTree</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### deserialize() {#a2c9fcdfa14dafa4bf635b6bdd88e0c77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutlinedHashTreeRecord::deserialize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char *&amp; Ptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deserialize the outlined hash tree from a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>.</p>

<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/outlinedhashtreerecord-cpp">OutlinedHashTreeRecord.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/hashnodestable/#a1a8ed2c92340bd47d8da01a8d483f5ae">llvm::HashNodeStable::Hash</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae6c58c37f5229487e86ce915afe1ba12">llvm::support::endian::readNext</a>, <a href="/web-llvm/docs/api/structs/llvm/hashnodestable/#a9044678a73d0f8eb1869896267366952">llvm::HashNodeStable::SuccessorIds</a> and <a href="/web-llvm/docs/api/structs/llvm/hashnodestable/#a4768333b0fd61daef285d1104a911ec9">llvm::HashNodeStable::Terminals</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegendatareader/#ad41848e26234890d2d908a09f6709022">llvm::CodeGenDataReader::mergeFromObjectFile</a>.</p>

</div>
</div>

### deserializeYAML() {#a2224262c0507515a54edc38eb71d693c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutlinedHashTreeRecord::deserializeYAML (<a href="/web-llvm/docs/api/classes/llvm/yaml/input">yaml::Input</a> &amp; YIS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deserialize the outlined hash tree from a YAML stream.</p>

<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/outlinedhashtreerecord-cpp">OutlinedHashTreeRecord.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/yaml/input/#a19ce7da8d438cf158c9b36d433ad386d">llvm::yaml::Input::nextDocument</a>.</p>

</div>
</div>

### empty() {#a3e5e2f09e5c13dfc26257ff0d02f3f86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OutlinedHashTreeRecord::empty ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the outlined hash tree is empty.</p></dd>
</dl>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a>.</p>


<p>Reference <a href="#a959a2066fb03b6af9f7ddd79bc1f5004">HashTree</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a05b4c070c172287759f5f2f437a3edcb">llvm::cgdata::mergeCodeGenData</a>.</p>

</div>
</div>

### merge() {#ab4486d597859e5cabe3b4a691a4bb5ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::OutlinedHashTreeRecord::merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/outlinedhashtreerecord">OutlinedHashTreeRecord</a> &amp; Other)</td>
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

<p>Merge the other outlined hash tree into this one.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a>.</p>


<p>References <a href="#a959a2066fb03b6af9f7ddd79bc1f5004">HashTree</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a9860e6d3634ffb50b571251b43052b46">OutlinedHashTreeRecord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegendatareader/#ad41848e26234890d2d908a09f6709022">llvm::CodeGenDataReader::mergeFromObjectFile</a>.</p>

</div>
</div>

### print() {#a8538f41cea55ce9f22b2c72bfb7b1874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::OutlinedHashTreeRecord::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS=<a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>())</td>
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

<p>Print the outlined hash tree in a YAML format.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="#a016492643cfefde4ce1fab18d0c8cfd8">serializeYAML</a>.</p>

</div>
</div>

### serialize() {#a74ae6e240a1760c68a807fd885606fe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutlinedHashTreeRecord::serialize (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Serialize the outlined hash tree to a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>.</p>

<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/outlinedhashtreerecord-cpp">OutlinedHashTreeRecord.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="/web-llvm/docs/api/structs/llvm/support/endian/writer/#a16a69d4248bb11c84536099421ea833b">llvm::support::endian::Writer::write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a7fe992f3a0f55c247f1f27cb09755ab5">anonymous{MachineOutliner.cpp}::MachineOutliner::emitOutlinedHashTree</a>.</p>

</div>
</div>

### serializeYAML() {#a016492643cfefde4ce1fab18d0c8cfd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutlinedHashTreeRecord::serializeYAML (<a href="/web-llvm/docs/api/classes/llvm/yaml/output">yaml::Output</a> &amp; YOS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Serialize the outlined hash tree to a YAML stream.</p>

<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/outlinedhashtreerecord-cpp">OutlinedHashTreeRecord.cpp</a>.</p>


<p>Referenced by <a href="#a8538f41cea55ce9f22b2c72bfb7b1874">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### convertFromStableData() {#a6a976662dddace2ecb39011465c19720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutlinedHashTreeRecord::convertFromStableData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ae16b5b471638b82084c70efc140cbd48">IdHashNodeStableMapTy</a> &amp; IdNodeStableMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert the stable data back to the outlined hash tree.</p>

<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a>, definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/outlinedhashtreerecord-cpp">OutlinedHashTreeRecord.cpp</a>.</p>

</div>
</div>

### convertToStableData() {#a31079d22c3b163ed90eba3679919bb6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutlinedHashTreeRecord::convertToStableData (<a href="/web-llvm/docs/api/namespaces/llvm/#ae16b5b471638b82084c70efc140cbd48">IdHashNodeStableMapTy</a> &amp; IdNodeStableMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert the outlined hash tree to stable data.</p>

<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/outlinedhashtreerecord-cpp">OutlinedHashTreeRecord.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### HashTree {#a959a2066fb03b6af9f7ddd79bc1f5004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;OutlinedHashTree&gt; llvm::OutlinedHashTreeRecord::HashTree</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a>.</p>


<p>Referenced by <a href="#a3e5e2f09e5c13dfc26257ff0d02f3f86">empty</a>, <a href="#ab4486d597859e5cabe3b4a691a4bb5ee">merge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a05b4c070c172287759f5f2f437a3edcb">llvm::cgdata::mergeCodeGenData</a>, <a href="#a9860e6d3634ffb50b571251b43052b46">OutlinedHashTreeRecord</a> and <a href="#a34c5e9a476f387121faac69d2045cb12">OutlinedHashTreeRecord</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/cgdata/outlinedhashtreerecord-cpp">OutlinedHashTreeRecord.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
