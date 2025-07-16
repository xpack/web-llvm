---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/yaml/keyvaluenode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `KeyValueNode` Class Reference

<p>A key and value pair. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::yaml::KeyValueNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">llvm/Support/YAMLParser.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract base class for all Nodes. <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac036f35fb6c22fe8ead94d5218f57245">KeyValueNode</a> (std::unique_ptr&lt; Document &gt; &amp;D)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab423b6588650879f12890d97837328ba">getKey</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse and return the key. <a href="#ab423b6588650879f12890d97837328ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1294ccf387b5a8f26c64b492fcc38d22">getValue</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse and return the value. <a href="#a1294ccf387b5a8f26c64b492fcc38d22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85d3317a82c6b6b15b6cb2466cd06b6d">skip</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a663ea21b70680e7b0f02ab559bc0a3d0">anchor</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pin the vtables to this file. <a href="#a663ea21b70680e7b0f02ab559bc0a3d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65a38a1c8a9ac0574620b4b48498fc94">Key</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac31d0ac3032d0596f33b9317158d9b9c">Value</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d6da181da9601218ececfbdd4361d49">classof</a> (const Node *N)</td>
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

<p>A key and value pair.</p>


<p>While not technically a <a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a> under the YAML representation graph, it is easier to treat them this way.</p>


<p>TODO: Consider making this not a child of <a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a>.</p>


<p>Example: Section: .text</p>


<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### KeyValueNode() {#ac036f35fb6c22fe8ead94d5218f57245}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::KeyValueNode::KeyValueNode (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/yaml/document">Document</a> &gt; &amp; D)</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#a9be14a4482135b4cf1f12684445bd05cad37227a542a57ed0045bdb56212e3ce0">llvm::yaml::Node::NK_KeyValue</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#ac0d44d7d7fc14a6a2596d0d2e36e0ba3">llvm::yaml::Node::Node</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getKey() {#ab423b6588650879f12890d97837328ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * KeyValueNode::getKey ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse and return the key.</p>


<p>This may be called multiple times.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The key, or nullptr if <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#a4a3a9ae577da9991a159a2c5fb10b419">failed()</a> == true.</p></dd>
</dl>


<p>Declaration at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2257 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#a4c9c2bb039202b749ec9aceafadb7eee">llvm::yaml::Node::Doc</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#ad3b1eb94e3f5985d5c964b830459710b">llvm::yaml::Node::getAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#af6421e485ae3e23017b17b19eabad4f2">llvm::yaml::Node::getNext</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a396e0f47847aa197379fa2883e602a24">llvm::yaml::Token::Kind</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#ac0d44d7d7fc14a6a2596d0d2e36e0ba3">llvm::yaml::Node::Node</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#aebd3b856bc2b481175bdd1e55a0e2d9e">llvm::yaml::Node::parseBlockNode</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#af768a9bd2b66618730d44a81343f70f9">llvm::yaml::Node::peekNext</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a7f83863c476433568203d2a37dfaefc1">llvm::yaml::Token::TK_BlockEnd</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a5d1fec5f8be79dd4c5956a2503aa2843">llvm::yaml::Token::TK_Error</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a537b5ded27736279783b16d2f4b670ef">llvm::yaml::Token::TK_Key</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a220bc8a613a1eceb652b17a9f1f4fe80">llvm::yaml::Token::TK_Value</a>.</p>


<p>Referenced by <a href="#a1294ccf387b5a8f26c64b492fcc38d22">getValue</a> and <a href="#a85d3317a82c6b6b15b6cb2466cd06b6d">skip</a>.</p>

</div>
</div>

### getValue() {#a1294ccf387b5a8f26c64b492fcc38d22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * KeyValueNode::getValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse and return the value.</p>


<p>This may be called multiple times.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The value, or nullptr if <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#a4a3a9ae577da9991a159a2c5fb10b419">failed()</a> == true.</p></dd>
</dl>


<p>Declaration at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2282 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#a4c9c2bb039202b749ec9aceafadb7eee">llvm::yaml::Node::Doc</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#a4a3a9ae577da9991a159a2c5fb10b419">llvm::yaml::Node::failed</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#ad3b1eb94e3f5985d5c964b830459710b">llvm::yaml::Node::getAllocator</a>, <a href="#ab423b6588650879f12890d97837328ba">getKey</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#af6421e485ae3e23017b17b19eabad4f2">llvm::yaml::Node::getNext</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a396e0f47847aa197379fa2883e602a24">llvm::yaml::Token::Kind</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#ac0d44d7d7fc14a6a2596d0d2e36e0ba3">llvm::yaml::Node::Node</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#aebd3b856bc2b481175bdd1e55a0e2d9e">llvm::yaml::Node::parseBlockNode</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#af768a9bd2b66618730d44a81343f70f9">llvm::yaml::Node::peekNext</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#aed7304613d5892b3f9526e63908e0b9a">llvm::yaml::Node::setError</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#ac41eb1b46bcf91022167e1dcf895b51f">llvm::yaml::Node::skip</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a7f83863c476433568203d2a37dfaefc1">llvm::yaml::Token::TK_BlockEnd</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a5d1fec5f8be79dd4c5956a2503aa2843">llvm::yaml::Token::TK_Error</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a1814af059afd1fc841c6bcd0e8c92995">llvm::yaml::Token::TK_FlowEntry</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531ac9c8081f0d5e401295fe53e081c1e7df">llvm::yaml::Token::TK_FlowMappingEnd</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a537b5ded27736279783b16d2f4b670ef">llvm::yaml::Token::TK_Key</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a220bc8a613a1eceb652b17a9f1f4fe80">llvm::yaml::Token::TK_Value</a>.</p>


<p>Referenced by <a href="#a85d3317a82c6b6b15b6cb2466cd06b6d">skip</a>.</p>

</div>
</div>

### skip() {#a85d3317a82c6b6b15b6cb2466cd06b6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::KeyValueNode::skip ()</td>
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



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>References <a href="#ab423b6588650879f12890d97837328ba">getKey</a>, <a href="#a1294ccf387b5a8f26c64b492fcc38d22">getValue</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#ac0d44d7d7fc14a6a2596d0d2e36e0ba3">llvm::yaml::Node::Node</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a663ea21b70680e7b0f02ab559bc0a3d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void KeyValueNode::anchor ()</td>
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

<p>Pin the vtables to this file.</p>

<p>Declaration at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Key {#a65a38a1c8a9ac0574620b4b48498fc94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node* llvm::yaml::KeyValueNode::Key = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>

</div>
</div>

### Value {#ac31d0ac3032d0596f33b9317158d9b9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node* llvm::yaml::KeyValueNode::Value = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a9d6da181da9601218ececfbdd4361d49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::KeyValueNode::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a> * N)</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#a9be14a4482135b4cf1f12684445bd05cad37227a542a57ed0045bdb56212e3ce0">llvm::yaml::Node::NK_KeyValue</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#ac0d44d7d7fc14a6a2596d0d2e36e0ba3">llvm::yaml::Node::Node</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
