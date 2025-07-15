---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/yaml/document
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Document` Class Reference

<p>A YAML <a href="/web-llvm/docs/api/classes/llvm/yaml/stream">Stream</a> is a sequence of Documents. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::yaml::Document { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">llvm/Support/YAMLParser.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6db9d28bd448a131448276ee03de1e6d">Node</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1b2098fb9098819d9009d63dda2f7b5">document_iterator</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaf30a62ca1f2600cca6016951eee25b">Document</a> (Stream &amp;ParentStream)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a195e6cd6c71f2fabbd3d99a61627abee">parseBlockNode</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Root for parsing a node. Returns a single node. <a href="#a195e6cd6c71f2fabbd3d99a61627abee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cb9cf1d6e2fa720e8c93f46648200e9">skip</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finish parsing the current document and return true if there are more. <a href="#a3cb9cf1d6e2fa720e8c93f46648200e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a673e9ef8fd2171ea34096f60eed3c74d">getRoot</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse and return the root level node. <a href="#a673e9ef8fd2171ea34096f60eed3c74d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c62d6163d023ea28cb792a4ff48deed">getTagMap</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/token">Token</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a992c23410cd340cea16681070ac11a6d">peekNext</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/token">Token</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d034ec554a58752a4b40024526f6592">getNext</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7de9b3b3e061f5617c626a0117c52100">setError</a> (const Twine &amp;Message, Token &amp;Location) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27a644cc54b0faf52954d38f1f1a9e64">failed</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae62694f2d29cad6979bb835caf741fec">parseDirectives</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse BLAH directives and return true if any were encountered. <a href="#ae62694f2d29cad6979bb835caf741fec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3f285b9211807d7c9e4a76f21c88005">parseYAMLDirective</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse YAML. <a href="#ac3f285b9211807d7c9e4a76f21c88005">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8340cfde864fd5ee79744d79df55dfac">parseTAGDirective</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse TAG. <a href="#a8340cfde864fd5ee79744d79df55dfac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a112c2ea71385a7f24838b91fad7c6871">expectToken</a> (int TK)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Consume the next token and error if it is not <em>TK</em>. <a href="#a112c2ea71385a7f24838b91fad7c6871">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/stream">Stream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02d358ae12dd8c42d9570c873bbf3d84">stream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/yaml/stream">Stream</a> to read tokens from. <a href="#a02d358ae12dd8c42d9570c873bbf3d84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a411013273bc08d0c28e83fd81e734ed6">NodeAllocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to allocate nodes to. <a href="#a411013273bc08d0c28e83fd81e734ed6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40d264fc8a65a20a9e26d5f2212fff6d">Root</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The root node. <a href="#a40d264fc8a65a20a9e26d5f2212fff6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26ea34993b2ea763b35ee1244f0e0f43">TagMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps tag prefixes to their expansion. <a href="#a26ea34993b2ea763b35ee1244f0e0f43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A YAML <a href="/web-llvm/docs/api/classes/llvm/yaml/stream">Stream</a> is a sequence of Documents.</p>


<p>A document contains a root node.</p>


<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<div class="doxySectionDef">

## Friends

### document\_iterator {#aa1b2098fb9098819d9009d63dda2f7b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/yaml/document-iterator">document_iterator</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 558 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>References <a href="#aa1b2098fb9098819d9009d63dda2f7b5">document_iterator</a> and <a href="#a6db9d28bd448a131448276ee03de1e6d">Node</a>.</p>


<p>Referenced by <a href="#aa1b2098fb9098819d9009d63dda2f7b5">document_iterator</a>.</p>

</div>
</div>

### Node {#a6db9d28bd448a131448276ee03de1e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>Reference <a href="#a6db9d28bd448a131448276ee03de1e6d">Node</a>.</p>


<p>Referenced by <a href="#aa1b2098fb9098819d9009d63dda2f7b5">document_iterator</a>, <a href="#a673e9ef8fd2171ea34096f60eed3c74d">getRoot</a>, <a href="#a6db9d28bd448a131448276ee03de1e6d">Node</a> and <a href="#a195e6cd6c71f2fabbd3d99a61627abee">parseBlockNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Document() {#aeaf30a62ca1f2600cca6016951eee25b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Document::Document (<a href="/web-llvm/docs/api/classes/llvm/yaml/stream">Stream</a> &amp; ParentStream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2468 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a21388bc616a0c79332f06f17ad2a63da">llvm::yaml::Token::TK_DocumentStart</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRoot() {#a673e9ef8fd2171ea34096f60eed3c74d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * llvm::yaml::Document::getRoot ()</td>
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

<p>Parse and return the root level node.</p>

<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>References <a href="#a6db9d28bd448a131448276ee03de1e6d">Node</a> and <a href="#a195e6cd6c71f2fabbd3d99a61627abee">parseBlockNode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#ac4d29f90f81ea8264f49bb0736faf1d0">llvm::remarks::YAMLRemarkParser::parseRemark</a> and <a href="#a3cb9cf1d6e2fa720e8c93f46648200e9">skip</a>.</p>

</div>
</div>

### getTagMap() {#a3c62d6163d023ea28cb792a4ff48deed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::map&lt; StringRef, StringRef &gt; &amp; llvm::yaml::Document::getTagMap ()</td>
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



<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>

</div>
</div>

### parseBlockNode() {#a195e6cd6c71f2fabbd3d99a61627abee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * Document::parseBlockNode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Root for parsing a node. Returns a single node.</p>

<p>Declaration at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2512 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#ac66731b70af2ad5aded1ce13a20acb29">llvm::StringRef::copy</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae2705fd641fb3d1eefa2691b5117cf22">llvm::StringRef::drop_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a396e0f47847aa197379fa2883e602a24">llvm::yaml::Token::Kind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/mappingnode/#a167fc067293dc1c4d886c86bbbc7fddaa81350c3e1c558b7f05a3453d611b810d">llvm::yaml::MappingNode::MT_Block</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/mappingnode/#a167fc067293dc1c4d886c86bbbc7fddaaa2cf6bec50d891d032caf32a31b8253e">llvm::yaml::MappingNode::MT_Flow</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/mappingnode/#a167fc067293dc1c4d886c86bbbc7fddaaaff37744ee49f45739490449eed6195b">llvm::yaml::MappingNode::MT_Inline</a>, <a href="#a6db9d28bd448a131448276ee03de1e6d">Node</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#ab2bc3dca5761a105ee575a8dc5ef36a0">llvm::yaml::Token::Range</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/sequencenode/#a94189404dca9667e4377d4f0bef90f28a3438e318f0332e9def374d53f6c8d6d2">llvm::yaml::SequenceNode::ST_Block</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/sequencenode/#a94189404dca9667e4377d4f0bef90f28aad13c8c125e5877b5853ff46abd49313">llvm::yaml::SequenceNode::ST_Flow</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/sequencenode/#a94189404dca9667e4377d4f0bef90f28a0494b083066edd3c886a2895157f9de1">llvm::yaml::SequenceNode::ST_Indentless</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531ae06ceae74093cd37f3091e1e154f39a9">llvm::yaml::Token::TK_Alias</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a8340baa944a2841ca03501f13630074b">llvm::yaml::Token::TK_Anchor</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a740ebe1fc34dc71512527c688b6adf76">llvm::yaml::Token::TK_BlockEntry</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a06e9aa56b4f6ec622a31dc0e72b0e3be">llvm::yaml::Token::TK_BlockMappingStart</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a71734af33e74dd7b68c4980ed1f766d8">llvm::yaml::Token::TK_BlockScalar</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a077c62971dd7272d6c4ccac9307d27ba">llvm::yaml::Token::TK_BlockSequenceStart</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a966a8a0467d033c2aab7df3b93f7abb6">llvm::yaml::Token::TK_DocumentEnd</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a21388bc616a0c79332f06f17ad2a63da">llvm::yaml::Token::TK_DocumentStart</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a5d1fec5f8be79dd4c5956a2503aa2843">llvm::yaml::Token::TK_Error</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a1814af059afd1fc841c6bcd0e8c92995">llvm::yaml::Token::TK_FlowEntry</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531ac9c8081f0d5e401295fe53e081c1e7df">llvm::yaml::Token::TK_FlowMappingEnd</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531addfdb5bdb33bcce24a5d5b7ecc5538f2">llvm::yaml::Token::TK_FlowMappingStart</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531ac4125146ea96c10a281bf1e07dd2d661">llvm::yaml::Token::TK_FlowSequenceEnd</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531abed63dce168b5d595a7f1d3d3626dd0c">llvm::yaml::Token::TK_FlowSequenceStart</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a537b5ded27736279783b16d2f4b670ef">llvm::yaml::Token::TK_Key</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a91391f278be4723a401519886e49ca6e">llvm::yaml::Token::TK_Scalar</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a063fd4366f9e152640f754222924b499">llvm::yaml::Token::TK_StreamEnd</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a2c0c59b4b92d3d0269d2062f8e6853e7">llvm::yaml::Token::TK_Tag</a>.</p>


<p>Referenced by <a href="#a673e9ef8fd2171ea34096f60eed3c74d">getRoot</a>.</p>

</div>
</div>

### skip() {#a3cb9cf1d6e2fa720e8c93f46648200e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Document::skip ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finish parsing the current document and return true if there are more.</p>


<p>Return false otherwise.</p>


<p>Declaration at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2480 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>References <a href="#a673e9ef8fd2171ea34096f60eed3c74d">getRoot</a>, <a href="#a3cb9cf1d6e2fa720e8c93f46648200e9">skip</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a966a8a0467d033c2aab7df3b93f7abb6">llvm::yaml::Token::TK_DocumentEnd</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a063fd4366f9e152640f754222924b499">llvm::yaml::Token::TK_StreamEnd</a>.</p>


<p>Referenced by <a href="#a3cb9cf1d6e2fa720e8c93f46648200e9">skip</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/stream/#af2acd5606c7ff8246f7b934f0b26e44d">llvm::yaml::Stream::skip</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### expectToken() {#a112c2ea71385a7f24838b91fad7c6871}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Document::expectToken (int TK)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Consume the next token and error if it is not <em>TK</em>.</p>

<p>Declaration at line 589 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2655 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### failed() {#a27a644cc54b0faf52954d38f1f1a9e64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Document::failed ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2508 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### getNext() {#a5d034ec554a58752a4b40024526f6592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token Document::getNext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 575 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2500 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### parseDirectives() {#ae62694f2d29cad6979bb835caf741fec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Document::parseDirectives ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse BLAH directives and return true if any were encountered.</p>

<p>Declaration at line 580 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2624 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### parseTAGDirective() {#a8340cfde864fd5ee79744d79df55dfac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Document::parseTAGDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse TAG.</p>

<p>Declaration at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2644 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### parseYAMLDirective() {#ac3f285b9211807d7c9e4a76f21c88005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Document::parseYAMLDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse YAML.</p>

<p>Declaration at line 583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2640 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### peekNext() {#a992c23410cd340cea16681070ac11a6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token &amp; Document::peekNext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 574 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2496 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### setError() {#a7de9b3b3e061f5617c626a0117c52100}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Document::setError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Message, <a href="/web-llvm/docs/api/structs/llvm/yaml/token">Token</a> &amp; Location)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 576 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2504 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NodeAllocator {#a411013273bc08d0c28e83fd81e734ed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::yaml::Document::NodeAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to allocate nodes to.</p>


<p>All are destroyed without calling their destructor when the document is destroyed.</p>


<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>

</div>
</div>

### Root {#a40d264fc8a65a20a9e26d5f2212fff6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node* llvm::yaml::Document::Root</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The root node.</p>


<p>Used to support skipping a partially parsed document.</p>


<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>

</div>
</div>

### stream {#a02d358ae12dd8c42d9570c873bbf3d84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Stream&amp; llvm::yaml::Document::stream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/yaml/stream">Stream</a> to read tokens from.</p>

<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>

</div>
</div>

### TagMap {#a26ea34993b2ea763b35ee1244f0e0f43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;StringRef, StringRef&gt; llvm::yaml::Document::TagMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps tag prefixes to their expansion.</p>

<p>Definition at line 572 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
