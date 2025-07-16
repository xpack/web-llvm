---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/basicblocksectionsprofilereaderwrapperpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BasicBlockSectionsProfileReaderWrapperPass` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::BasicBlockSectionsProfileReaderWrapperPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionsprofilereader-h">llvm/CodeGen/BasicBlockSectionsProfileReader.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablepass">ImmutablePass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/immutablepass">ImmutablePass</a> class - This class is used to provide information that does not need to be run. <a href="/web-llvm/docs/api/classes/llvm/immutablepass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af672c06aa34ac7d31e4d703c95afedb5">BasicBlockSectionsProfileReaderWrapperPass</a> (const MemoryBuffer *Buf)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab196b483867e867596d4b0c724887d26">BasicBlockSectionsProfileReaderWrapperPass</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acafe6f28be0cea2fcaf8a9e31bbb20b9">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#acafe6f28be0cea2fcaf8a9e31bbb20b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b51d1b21ce4cc6959eaca63d7e7bd85">isFunctionHot</a> (StringRef FuncName) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; bool, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/bbclusterinfo">BBClusterInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accb75267cae6a683edef7785b1b15ddb">getClusterInfoForFunction</a> (StringRef FuncName) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f04f0c0725eee6c8ac655b62f80d664">getClonePathsForFunction</a> (StringRef FuncName) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a065b76d17a91964a67b2e45dbc1db7a0">doInitialization</a> (Module &amp;M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>doInitialization - Virtual method overridden by subclasses to do any necessary initialization before any pass is run. <a href="#a065b76d17a91964a67b2e45dbc1db7a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblocksectionsprofilereader">BasicBlockSectionsProfileReader</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cadd4ea1a09de954440670eb57af44a">getBBSPR</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblocksectionsprofilereader">BasicBlockSectionsProfileReader</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a457bff4a0939f4e9206bdc814a231b07">BBSPR</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35964d3943642c7d485dc17e1173e864">ID</a> = 0</td>
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


<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionsprofilereader-h">BasicBlockSectionsProfileReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BasicBlockSectionsProfileReaderWrapperPass() {#af672c06aa34ac7d31e4d703c95afedb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BasicBlockSectionsProfileReaderWrapperPass::BasicBlockSectionsProfileReaderWrapperPass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> * Buf)</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionsprofilereader-h">BasicBlockSectionsProfileReader.h</a>.</p>


<p>References <a href="#a457bff4a0939f4e9206bdc814a231b07">BBSPR</a>, <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a35964d3943642c7d485dc17e1173e864">ID</a>, <a href="/web-llvm/docs/api/classes/llvm/immutablepass/#a4d664099280bb09275254d64c329d25d">llvm::ImmutablePass::ImmutablePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3f167c8f10a8452424e81b9da0a7693b">llvm::initializeBasicBlockSectionsProfileReaderWrapperPassPass</a>.</p>

</div>
</div>

### BasicBlockSectionsProfileReaderWrapperPass() {#ab196b483867e867596d4b0c724887d26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BasicBlockSectionsProfileReaderWrapperPass::BasicBlockSectionsProfileReaderWrapperPass ()</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionsprofilereader-h">BasicBlockSectionsProfileReader.h</a>.</p>


<p>References <a href="#a457bff4a0939f4e9206bdc814a231b07">BBSPR</a>, <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a35964d3943642c7d485dc17e1173e864">ID</a>, <a href="/web-llvm/docs/api/classes/llvm/immutablepass/#a4d664099280bb09275254d64c329d25d">llvm::ImmutablePass::ImmutablePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3f167c8f10a8452424e81b9da0a7693b">llvm::initializeBasicBlockSectionsProfileReaderWrapperPassPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### doInitialization() {#a065b76d17a91964a67b2e45dbc1db7a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BasicBlockSectionsProfileReaderWrapperPass::doInitialization (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>doInitialization - Virtual method overridden by subclasses to do any necessary initialization before any pass is run.</p>

<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionsprofilereader-h">BasicBlockSectionsProfileReader.h</a>, definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksectionsprofilereader-cpp">BasicBlockSectionsProfileReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a457bff4a0939f4e9206bdc814a231b07">BBSPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a6aa32b6763df05d8187ad5551533b567">llvm::sys::path::remove_leading_dotslash</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### getBBSPR() {#a4cadd4ea1a09de954440670eb57af44a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlockSectionsProfileReader &amp; BasicBlockSectionsProfileReaderWrapperPass::getBBSPR ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionsprofilereader-h">BasicBlockSectionsProfileReader.h</a>, definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksectionsprofilereader-cpp">BasicBlockSectionsProfileReader.cpp</a>.</p>


<p>Reference <a href="#a457bff4a0939f4e9206bdc814a231b07">BBSPR</a>.</p>

</div>
</div>

### getClonePathsForFunction() {#a4f04f0c0725eee6c8ac655b62f80d664}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; SmallVector&lt; unsigned &gt; &gt; BasicBlockSectionsProfileReaderWrapperPass::getClonePathsForFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionsprofilereader-h">BasicBlockSectionsProfileReader.h</a>, definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksectionsprofilereader-cpp">BasicBlockSectionsProfileReader.cpp</a>.</p>


<p>Reference <a href="#a457bff4a0939f4e9206bdc814a231b07">BBSPR</a>.</p>

</div>
</div>

### getClusterInfoForFunction() {#accb75267cae6a683edef7785b1b15ddb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; bool, SmallVector&lt; BBClusterInfo &gt; &gt; BasicBlockSectionsProfileReaderWrapperPass::getClusterInfoForFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionsprofilereader-h">BasicBlockSectionsProfileReader.h</a>, definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksectionsprofilereader-cpp">BasicBlockSectionsProfileReader.cpp</a>.</p>


<p>Reference <a href="#a457bff4a0939f4e9206bdc814a231b07">BBSPR</a>.</p>

</div>
</div>

### getPassName() {#acafe6f28be0cea2fcaf8a9e31bbb20b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::BasicBlockSectionsProfileReaderWrapperPass::getPassName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionsprofilereader-h">BasicBlockSectionsProfileReader.h</a>.</p>

</div>
</div>

### isFunctionHot() {#a9b51d1b21ce4cc6959eaca63d7e7bd85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BasicBlockSectionsProfileReaderWrapperPass::isFunctionHot (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionsprofilereader-h">BasicBlockSectionsProfileReader.h</a>, definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksectionsprofilereader-cpp">BasicBlockSectionsProfileReader.cpp</a>.</p>


<p>Reference <a href="#a457bff4a0939f4e9206bdc814a231b07">BBSPR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BBSPR {#a457bff4a0939f4e9206bdc814a231b07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlockSectionsProfileReader llvm::BasicBlockSectionsProfileReaderWrapperPass::BBSPR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionsprofilereader-h">BasicBlockSectionsProfileReader.h</a>.</p>


<p>Referenced by <a href="#ab196b483867e867596d4b0c724887d26">BasicBlockSectionsProfileReaderWrapperPass</a>, <a href="#af672c06aa34ac7d31e4d703c95afedb5">BasicBlockSectionsProfileReaderWrapperPass</a>, <a href="#a065b76d17a91964a67b2e45dbc1db7a0">doInitialization</a>, <a href="#a4cadd4ea1a09de954440670eb57af44a">getBBSPR</a>, <a href="#a4f04f0c0725eee6c8ac655b62f80d664">getClonePathsForFunction</a>, <a href="#accb75267cae6a683edef7785b1b15ddb">getClusterInfoForFunction</a> and <a href="#a9b51d1b21ce4cc6959eaca63d7e7bd85">isFunctionHot</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a35964d3943642c7d485dc17e1173e864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char BasicBlockSectionsProfileReaderWrapperPass::ID = 0</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionsprofilereader-h">BasicBlockSectionsProfileReader.h</a>.</p>


<p>Referenced by <a href="#ab196b483867e867596d4b0c724887d26">BasicBlockSectionsProfileReaderWrapperPass</a> and <a href="#af672c06aa34ac7d31e4d703c95afedb5">BasicBlockSectionsProfileReaderWrapperPass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionsprofilereader-h">BasicBlockSectionsProfileReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksectionsprofilereader-cpp">BasicBlockSectionsProfileReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
