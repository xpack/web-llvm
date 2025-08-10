---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/stablefunctionmaprecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `StableFunctionMapRecord` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::StableFunctionMapRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmaprecord-h">llvm/CGData/StableFunctionMapRecord.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9cc0cf25141430f249fbbd805fe89b0">StableFunctionMapRecord</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb88857f20273423e0ef57d1005d8c21">StableFunctionMapRecord</a> (std::unique_ptr&lt; StableFunctionMap &gt; FunctionMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0e73c819aeb5a427bd161d0465f073e">serialize</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serialize the stable function map to a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>. <a href="#ac0e73c819aeb5a427bd161d0465f073e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46fcb6ab7d4a17276796efb4fd9ef091">deserialize</a> (const unsigned char *&amp;Ptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deserialize the stable function map from a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>. <a href="#a46fcb6ab7d4a17276796efb4fd9ef091">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afab769346efd3e1ee1efe2bfe44d7149">serializeYAML</a> (yaml::Output &amp;YOS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serialize the stable function map to a YAML stream. <a href="#afab769346efd3e1ee1efe2bfe44d7149">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add85723c9058d7160e140ca778136076">deserializeYAML</a> (yaml::Input &amp;YIS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deserialize the stable function map from a YAML stream. <a href="#add85723c9058d7160e140ca778136076">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cd1b3682ae88c0d68ea0a77a8cec60f">finalize</a> (bool SkipTrim=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize the stable function map by trimming content. <a href="#a1cd1b3682ae88c0d68ea0a77a8cec60f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0621093b5be0060d05b4dd5336611229">merge</a> (const StableFunctionMapRecord &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge the stable function map into this one. <a href="#a0621093b5be0060d05b4dd5336611229">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09340e3ef9295311df9e4ce96617ca99">empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a841eba68cb60664b7b048e09be0f521a">print</a> (raw_ostream &amp;OS=llvm::errs()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the stable function map in a YAML format. <a href="#a841eba68cb60664b7b048e09be0f521a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap">StableFunctionMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eadb49468a17cf63d04cfe7a47dc396">FunctionMap</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6d6f1cad87cc3ed7f87784dd9ddff0f">serialize</a> (raw_ostream &amp;OS, const StableFunctionMap *FunctionMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A static helper function to serialize the stable function map without owning the stable function map. <a href="#aa6d6f1cad87cc3ed7f87784dd9ddff0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmaprecord-h">StableFunctionMapRecord.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### StableFunctionMapRecord() {#af9cc0cf25141430f249fbbd805fe89b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StableFunctionMapRecord::StableFunctionMapRecord ()</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmaprecord-h">StableFunctionMapRecord.h</a>.</p>


<p>Reference <a href="#a6eadb49468a17cf63d04cfe7a47dc396">FunctionMap</a>.</p>


<p>Referenced by <a href="#a0621093b5be0060d05b4dd5336611229">merge</a>.</p>

</div>
</div>

### StableFunctionMapRecord() {#abb88857f20273423e0ef57d1005d8c21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StableFunctionMapRecord::StableFunctionMapRecord (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap">StableFunctionMap</a> &gt; FunctionMap)</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmaprecord-h">StableFunctionMapRecord.h</a>.</p>


<p>References <a href="#a6eadb49468a17cf63d04cfe7a47dc396">FunctionMap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### deserialize() {#a46fcb6ab7d4a17276796efb4fd9ef091}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StableFunctionMapRecord::deserialize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char *&amp; Ptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deserialize the stable function map from a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>.</p>

<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmaprecord-h">StableFunctionMapRecord.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmaprecord-cpp">StableFunctionMapRecord.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afff5074588f0423a669618a7134e13ec">llvm::alignAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6eadb49468a17cf63d04cfe7a47dc396">FunctionMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae6c58c37f5229487e86ce915afe1ba12">llvm::support::endian::readNext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegendatareader/#ad41848e26234890d2d908a09f6709022">llvm::CodeGenDataReader::mergeFromObjectFile</a>.</p>

</div>
</div>

### deserializeYAML() {#add85723c9058d7160e140ca778136076}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StableFunctionMapRecord::deserializeYAML (<a href="/web-llvm/docs/api/classes/llvm/yaml/input">yaml::Input</a> &amp; YIS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deserialize the stable function map from a YAML stream.</p>

<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmaprecord-h">StableFunctionMapRecord.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmaprecord-cpp">StableFunctionMapRecord.cpp</a>.</p>


<p>References <a href="#a6eadb49468a17cf63d04cfe7a47dc396">FunctionMap</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/input/#a19ce7da8d438cf158c9b36d433ad386d">llvm::yaml::Input::nextDocument</a>.</p>

</div>
</div>

### empty() {#a09340e3ef9295311df9e4ce96617ca99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StableFunctionMapRecord::empty ()</td>
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
<dd><p>true if the stable function map is empty.</p></dd>
</dl>


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmaprecord-h">StableFunctionMapRecord.h</a>.</p>


<p>Reference <a href="#a6eadb49468a17cf63d04cfe7a47dc396">FunctionMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a05b4c070c172287759f5f2f437a3edcb">llvm::cgdata::mergeCodeGenData</a>.</p>

</div>
</div>

### finalize() {#a1cd1b3682ae88c0d68ea0a77a8cec60f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::StableFunctionMapRecord::finalize (bool SkipTrim=false)</td>
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

<p>Finalize the stable function map by trimming content.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmaprecord-h">StableFunctionMapRecord.h</a>.</p>


<p>Reference <a href="#a6eadb49468a17cf63d04cfe7a47dc396">FunctionMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a05b4c070c172287759f5f2f437a3edcb">llvm::cgdata::mergeCodeGenData</a>.</p>

</div>
</div>

### merge() {#a0621093b5be0060d05b4dd5336611229}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::StableFunctionMapRecord::merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmaprecord">StableFunctionMapRecord</a> &amp; Other)</td>
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

<p>Merge the stable function map into this one.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmaprecord-h">StableFunctionMapRecord.h</a>.</p>


<p>References <a href="#a6eadb49468a17cf63d04cfe7a47dc396">FunctionMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#af9cc0cf25141430f249fbbd805fe89b0">StableFunctionMapRecord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegendatareader/#ad41848e26234890d2d908a09f6709022">llvm::CodeGenDataReader::mergeFromObjectFile</a>.</p>

</div>
</div>

### print() {#a841eba68cb60664b7b048e09be0f521a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::StableFunctionMapRecord::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS=<a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>())</td>
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

<p>Print the stable function map in a YAML format.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmaprecord-h">StableFunctionMapRecord.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="#afab769346efd3e1ee1efe2bfe44d7149">serializeYAML</a>.</p>

</div>
</div>

### serialize() {#ac0e73c819aeb5a427bd161d0465f073e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StableFunctionMapRecord::serialize (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Serialize the stable function map to a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>.</p>

<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmaprecord-h">StableFunctionMapRecord.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmaprecord-cpp">StableFunctionMapRecord.cpp</a>.</p>


<p>References <a href="#a6eadb49468a17cf63d04cfe7a47dc396">FunctionMap</a> and <a href="#aa6d6f1cad87cc3ed7f87784dd9ddff0f">serialize</a>.</p>

</div>
</div>

### serializeYAML() {#afab769346efd3e1ee1efe2bfe44d7149}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StableFunctionMapRecord::serializeYAML (<a href="/web-llvm/docs/api/classes/llvm/yaml/output">yaml::Output</a> &amp; YOS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Serialize the stable function map to a YAML stream.</p>

<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmaprecord-h">StableFunctionMapRecord.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmaprecord-cpp">StableFunctionMapRecord.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="#a6eadb49468a17cf63d04cfe7a47dc396">FunctionMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmaprecord-cpp/#a509ce85b468f4da99d1111c7498e2557">getStableFunctionEntries</a> and <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmaprecord-cpp/#a282266673aa65393e018d96acf69a211">getStableIndexOperandHashes</a>.</p>


<p>Referenced by <a href="#a841eba68cb60664b7b048e09be0f521a">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### FunctionMap {#a6eadb49468a17cf63d04cfe7a47dc396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;StableFunctionMap&gt; llvm::StableFunctionMapRecord::FunctionMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmaprecord-h">StableFunctionMapRecord.h</a>.</p>


<p>Referenced by <a href="#a46fcb6ab7d4a17276796efb4fd9ef091">deserialize</a>, <a href="#add85723c9058d7160e140ca778136076">deserializeYAML</a>, <a href="#a09340e3ef9295311df9e4ce96617ca99">empty</a>, <a href="#a1cd1b3682ae88c0d68ea0a77a8cec60f">finalize</a>, <a href="#a0621093b5be0060d05b4dd5336611229">merge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a05b4c070c172287759f5f2f437a3edcb">llvm::cgdata::mergeCodeGenData</a>, <a href="#ac0e73c819aeb5a427bd161d0465f073e">serialize</a>, <a href="#aa6d6f1cad87cc3ed7f87784dd9ddff0f">serialize</a>, <a href="#afab769346efd3e1ee1efe2bfe44d7149">serializeYAML</a>, <a href="#af9cc0cf25141430f249fbbd805fe89b0">StableFunctionMapRecord</a> and <a href="#abb88857f20273423e0ef57d1005d8c21">StableFunctionMapRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### serialize() {#aa6d6f1cad87cc3ed7f87784dd9ddff0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StableFunctionMapRecord::serialize (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap">StableFunctionMap</a> * FunctionMap)</td>
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

<p>A static helper function to serialize the stable function map without owning the stable function map.</p>

<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmaprecord-h">StableFunctionMapRecord.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmaprecord-cpp">StableFunctionMapRecord.cpp</a>.</p>


<p>References <a href="#a6eadb49468a17cf63d04cfe7a47dc396">FunctionMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmaprecord-cpp/#a509ce85b468f4da99d1111c7498e2557">getStableFunctionEntries</a>, <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmaprecord-cpp/#a282266673aa65393e018d96acf69a211">getStableIndexOperandHashes</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99cdcecbadc13087f087c61809bb44f1">llvm::offsetToAlignment</a>, <a href="/web-llvm/docs/api/structs/llvm/support/endian/writer/#aea6f1003a6933f07d06dbce84a8f26cb">llvm::support::endian::Writer::OS</a> and <a href="/web-llvm/docs/api/structs/llvm/support/endian/writer/#a16a69d4248bb11c84536099421ea833b">llvm::support::endian::Writer::write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalmergefunc/#a5f897499fea3f1a9fbb5c0fb2a363a20">llvm::GlobalMergeFunc::emitFunctionMap</a> and <a href="#ac0e73c819aeb5a427bd161d0465f073e">serialize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmaprecord-h">StableFunctionMapRecord.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmaprecord-cpp">StableFunctionMapRecord.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
