---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/yaml/node
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Node` Class Reference

<p>Abstract base class for all Nodes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::yaml::Node { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">llvm/Support/YAMLParser.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/aliasnode">AliasNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an alias to a <a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a> with an anchor. <a href="/web-llvm/docs/api/classes/llvm/yaml/aliasnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/blockscalarnode">BlockScalarNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A block scalar node is an opaque datum that can be presented as a series of zero or more Unicode scalar values. <a href="/web-llvm/docs/api/classes/llvm/yaml/blockscalarnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode">KeyValueNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A key and value pair. <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/mappingnode">MappingNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a YAML map created from either a block map for a flow map. <a href="/web-llvm/docs/api/classes/llvm/yaml/mappingnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/nullnode">NullNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A null value. <a href="/web-llvm/docs/api/classes/llvm/yaml/nullnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/scalarnode">ScalarNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A scalar node is an opaque datum that can be presented as a series of zero or more Unicode scalar values. <a href="/web-llvm/docs/api/classes/llvm/yaml/scalarnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/sequencenode">SequenceNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a YAML sequence created from either a block sequence for a flow sequence. <a href="/web-llvm/docs/api/classes/llvm/yaml/sequencenode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeKind { <a href="#a9be14a4482135b4cf1f12684445bd05c">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0d44d7d7fc14a6a2596d0d2e36e0ba3">Node</a> (unsigned int Type, std::unique_ptr&lt; Document &gt; &amp;, StringRef Anchor, StringRef Tag)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63bcbecade31beb5c5d33ae091c19639">Node</a> (const Node &amp;)=delete</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a284e88aaee347f4f126fb98f13a5db82">~Node</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2295c9306f1935385d7787f7fb5d3f4">operator=</a> (const Node &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d8893a3a74ad6e94dd41976e48c23c9">operator new</a> (size_t Size, BumpPtrAllocator &amp;Alloc, size_t Alignment=16) noexcept</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab0ab67dc6b1e7ec9941858ee1d95765">operator delete</a> (void *Ptr, BumpPtrAllocator &amp;Alloc, size_t Size) noexcept</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae427d34d729a52ca0316f3e41c2ffcbd">operator delete</a> (void *) noexcept=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6473a49d886e9b4e4b59700ac818eae9">getAnchor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the value of the anchor attached to this node. <a href="#a6473a49d886e9b4e4b59700ac818eae9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12fb2868b07901f8fc3bf4d1a97be781">getRawTag</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the tag as it was written in the document. <a href="#a12fb2868b07901f8fc3bf4d1a97be781">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a388e35e6191f5f51957c3024ef635190">getVerbatimTag</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the verbatium tag for a given <a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a>. <a href="#a388e35e6191f5f51957c3024ef635190">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad91e8eeb22d3f235f9d2b378447a7658">getSourceRange</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f5ca6a77c319906e8e16eda4c3642b9">setSourceRange</a> (SMRange SR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/token">Token</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af768a9bd2b66618730d44a81343f70f9">peekNext</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6421e485ae3e23017b17b19eabad4f2">getNext</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebd3b856bc2b481175bdd1e55a0e2d9e">parseBlockNode</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3b1eb94e3f5985d5c964b830459710b">getAllocator</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed7304613d5892b3f9526e63908e0b9a">setError</a> (const Twine &amp;Message, Token &amp;Location) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a3a9ae577da9991a159a2c5fb10b419">failed</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac41eb1b46bcf91022167e1dcf895b51f">skip</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27a30e0fec030306571236f8af39c9d4">getType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa246fb4c384590219623e676f1a60b5c">anchor</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pin the vtables to this file. <a href="#aa246fb4c384590219623e676f1a60b5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/yaml/document">Document</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c9c2bb039202b749ec9aceafadb7eee">Doc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e1c6be4d6e0af6ef6ce23f3cad3966b">SourceRange</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a795ee6874f865280a0c365a56a3b78a2">TypeID</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a739e0034a32574483b7b640c8cd2f6d1">Anchor</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4c89c5b44eb4708a8e3e070301524b6">Tag</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The tag as typed in the document. <a href="#ae4c89c5b44eb4708a8e3e070301524b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Abstract base class for all Nodes.</p>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### NodeKind {#a9be14a4482135b4cf1f12684445bd05c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::yaml::Node::NodeKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NK_Null<a id="a9be14a4482135b4cf1f12684445bd05cab7a7d760170eea69305fb7e626d3adf3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NK_Scalar<a id="a9be14a4482135b4cf1f12684445bd05cac3fd6387249af374b02021456103de1b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NK_BlockScalar<a id="a9be14a4482135b4cf1f12684445bd05cabf54f60a912c3f357aa9951b437c6e2b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NK_KeyValue<a id="a9be14a4482135b4cf1f12684445bd05cad37227a542a57ed0045bdb56212e3ce0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NK_Mapping<a id="a9be14a4482135b4cf1f12684445bd05ca8b6283b023691c6550523a955021c2b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NK_Sequence<a id="a9be14a4482135b4cf1f12684445bd05cad08123f59c216f3b171bf9410ded85a0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NK_Alias<a id="a9be14a4482135b4cf1f12684445bd05cadf30c7e88328c1121b987de2544a67c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Node() {#ac0d44d7d7fc14a6a2596d0d2e36e0ba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::Node::Node (unsigned int Type, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/yaml/document">Document</a> &gt; &amp;, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Anchor, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/yaml/aliasnode/#a2db3791110bd5d60604ddaa52b581d57">llvm::yaml::AliasNode::AliasNode</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/mappingnode/#a8e32c864ecfb8f276744c70d9a052297">llvm::yaml::MappingNode::basic_collection_iterator&lt; MappingNode, KeyValueNode &gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/sequencenode/#a84b700a9b41cc52c28785f2fcb1221ab">llvm::yaml::SequenceNode::basic_collection_iterator&lt; SequenceNode, Node &gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/blockscalarnode/#a85f1cad503bb4c8ac78b28b75832d5b8">llvm::yaml::BlockScalarNode::BlockScalarNode</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/aliasnode/#a5b055094faab8675a84ded1d0d849210">llvm::yaml::AliasNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/blockscalarnode/#a0fe29b12ada09490790221d7f10e3cb9">llvm::yaml::BlockScalarNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#a9d6da181da9601218ececfbdd4361d49">llvm::yaml::KeyValueNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/mappingnode/#a6a785765ed95dacd5f3a407b6c929de6">llvm::yaml::MappingNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/nullnode/#ae80aaff6db8dccc59337adc2a7047bb3">llvm::yaml::NullNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/scalarnode/#a6d236b13f37ba588208cb56039c1ed36">llvm::yaml::ScalarNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/sequencenode/#a204c5bcb113d98ac54c0b5e721149911">llvm::yaml::SequenceNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#ab423b6588650879f12890d97837328ba">llvm::yaml::KeyValueNode::getKey</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#a1294ccf387b5a8f26c64b492fcc38d22">llvm::yaml::KeyValueNode::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#ac036f35fb6c22fe8ead94d5218f57245">llvm::yaml::KeyValueNode::KeyValueNode</a>, <a href="#a63bcbecade31beb5c5d33ae091c19639">Node</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/nullnode/#ae1ccb86b37bd5f8135607e08d2ea7435">llvm::yaml::NullNode::NullNode</a>, <a href="#ae2295c9306f1935385d7787f7fb5d3f4">operator=</a>, <a href="#aebd3b856bc2b481175bdd1e55a0e2d9e">parseBlockNode</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/scalarnode/#a8cd838d3dcf1efd1367cbed9a0f8a69b">llvm::yaml::ScalarNode::ScalarNode</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#a85d3317a82c6b6b15b6cb2466cd06b6d">llvm::yaml::KeyValueNode::skip</a>.</p>

</div>
</div>

### Node() {#a63bcbecade31beb5c5d33ae091c19639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::Node::Node (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>Reference <a href="#ac0d44d7d7fc14a6a2596d0d2e36e0ba3">Node</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~Node() {#a284e88aaee347f4f126fb98f13a5db82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::Node::~Node ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator delete() {#aab0ab67dc6b1e7ec9941858ee1d95765}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::Node::operator delete (void * Ptr, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Alloc, size_t Size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1aea571dc00aef155a16d4e7e1861e1682">llvm::Alloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### operator delete() {#ae427d34d729a52ca0316f3e41c2ffcbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::Node::operator delete (void *)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel noexcept">noexcept</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>

</div>
</div>

### operator new() {#a2d8893a3a74ad6e94dd41976e48c23c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::yaml::Node::operator new (size_t Size, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Alloc, size_t Alignment=16)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1aea571dc00aef155a16d4e7e1861e1682">llvm::Alloc</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### operator=() {#ae2295c9306f1935385d7787f7fb5d3f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::Node::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>Reference <a href="#ac0d44d7d7fc14a6a2596d0d2e36e0ba3">Node</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### failed() {#a4a3a9ae577da9991a159a2c5fb10b419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Node::failed ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2027 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>Reference <a href="#a4c9c2bb039202b749ec9aceafadb7eee">Doc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#a1294ccf387b5a8f26c64b492fcc38d22">llvm::yaml::KeyValueNode::getValue</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/sequencenode/#a5848780917af6e4008594d684aaaa9db">llvm::yaml::SequenceNode::increment</a>.</p>

</div>
</div>

### getAllocator() {#ad3b1eb94e3f5985d5c964b830459710b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator &amp; Node::getAllocator ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2019 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>Reference <a href="#a4c9c2bb039202b749ec9aceafadb7eee">Doc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#ab423b6588650879f12890d97837328ba">llvm::yaml::KeyValueNode::getKey</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#a1294ccf387b5a8f26c64b492fcc38d22">llvm::yaml::KeyValueNode::getValue</a>.</p>

</div>
</div>

### getAnchor() {#a6473a49d886e9b4e4b59700ac818eae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::yaml::Node::getAnchor ()</td>
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

<p>Get the value of the anchor attached to this node.</p>


<p>If it does not have one, <a href="#a6473a49d886e9b4e4b59700ac818eae9">getAnchor()</a>.<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size()</a> will be 0.</p>


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>

</div>
</div>

### getNext() {#af6421e485ae3e23017b17b19eabad4f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token Node::getNext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2011 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>Reference <a href="#a4c9c2bb039202b749ec9aceafadb7eee">Doc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#ab423b6588650879f12890d97837328ba">llvm::yaml::KeyValueNode::getKey</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#a1294ccf387b5a8f26c64b492fcc38d22">llvm::yaml::KeyValueNode::getValue</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/sequencenode/#a5848780917af6e4008594d684aaaa9db">llvm::yaml::SequenceNode::increment</a>.</p>

</div>
</div>

### getRawTag() {#a12fb2868b07901f8fc3bf4d1a97be781}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::yaml::Node::getRawTag ()</td>
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

<p>Get the tag as it was written in the document.</p>


<p>This does not perform tag resolution.</p>


<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>Referenced by <a href="#a388e35e6191f5f51957c3024ef635190">getVerbatimTag</a>.</p>

</div>
</div>

### getSourceRange() {#ad91e8eeb22d3f235f9d2b378447a7658}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMRange llvm::yaml::Node::getSourceRange ()</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>Reference <a href="#a6e1c6be4d6e0af6ef6ce23f3cad3966b">SourceRange</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-ad322848578d151a36fcda7ed451f767/#a7d87092d92555db97b2196e799b6d70e">llvm::yaml::ScalarTraits&lt; FrameIndex &gt;::input</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-010e664abf779a0d0397e20693cd6016/#a3d1f93c262b46e3f302d15f27422723b">llvm::yaml::ScalarTraits&lt; StringValue &gt;::input</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-b35dd31197c29325629c63022d08b455/#a50bd5b08d577c6711e24a5858f39f03d">llvm::yaml::ScalarTraits&lt; UnsignedValue &gt;::input</a>.</p>

</div>
</div>

### getType() {#a27a30e0fec030306571236f8af39c9d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::yaml::Node::getType ()</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>Referenced by <a href="#a388e35e6191f5f51957c3024ef635190">getVerbatimTag</a>.</p>

</div>
</div>

### getVerbatimTag() {#a388e35e6191f5f51957c3024ef635190}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string Node::getVerbatimTag ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the verbatium tag for a given <a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a>.</p>


<p>This performs tag resoluton and substitution.</p>


<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 1962 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>References <a href="#a4c9c2bb039202b749ec9aceafadb7eee">Doc</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7a7c222449f3208a532168c90bfb654d">llvm::StringRef::find_last_of</a>, <a href="#a12fb2868b07901f8fc3bf4d1a97be781">getRawTag</a>, <a href="#a27a30e0fec030306571236f8af39c9d4">getType</a>, <a href="#a9be14a4482135b4cf1f12684445bd05cabf54f60a912c3f357aa9951b437c6e2b">NK_BlockScalar</a>, <a href="#a9be14a4482135b4cf1f12684445bd05ca8b6283b023691c6550523a955021c2b3">NK_Mapping</a>, <a href="#a9be14a4482135b4cf1f12684445bd05cab7a7d760170eea69305fb7e626d3adf3">NK_Null</a>, <a href="#a9be14a4482135b4cf1f12684445bd05cac3fd6387249af374b02021456103de1b">NK_Scalar</a>, <a href="#a9be14a4482135b4cf1f12684445bd05cad08123f59c216f3b171bf9410ded85a0">NK_Sequence</a>, <a href="#aed7304613d5892b3f9526e63908e0b9a">setError</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531a2c0c59b4b92d3d0269d2062f8e6853e7">llvm::yaml::Token::TK_Tag</a>.</p>

</div>
</div>

### parseBlockNode() {#aebd3b856bc2b481175bdd1e55a0e2d9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * Node::parseBlockNode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2015 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>References <a href="#a4c9c2bb039202b749ec9aceafadb7eee">Doc</a> and <a href="#ac0d44d7d7fc14a6a2596d0d2e36e0ba3">Node</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#ab423b6588650879f12890d97837328ba">llvm::yaml::KeyValueNode::getKey</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#a1294ccf387b5a8f26c64b492fcc38d22">llvm::yaml::KeyValueNode::getValue</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/sequencenode/#a5848780917af6e4008594d684aaaa9db">llvm::yaml::SequenceNode::increment</a>.</p>

</div>
</div>

### peekNext() {#af768a9bd2b66618730d44a81343f70f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token &amp; Node::peekNext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2007 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>Reference <a href="#a4c9c2bb039202b749ec9aceafadb7eee">Doc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#ab423b6588650879f12890d97837328ba">llvm::yaml::KeyValueNode::getKey</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#a1294ccf387b5a8f26c64b492fcc38d22">llvm::yaml::KeyValueNode::getValue</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/sequencenode/#a5848780917af6e4008594d684aaaa9db">llvm::yaml::SequenceNode::increment</a>.</p>

</div>
</div>

### setError() {#aed7304613d5892b3f9526e63908e0b9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Node::setError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Message, <a href="/web-llvm/docs/api/structs/llvm/yaml/token">Token</a> &amp; Location)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 2023 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>Reference <a href="#a4c9c2bb039202b749ec9aceafadb7eee">Doc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#a1294ccf387b5a8f26c64b492fcc38d22">llvm::yaml::KeyValueNode::getValue</a>, <a href="#a388e35e6191f5f51957c3024ef635190">getVerbatimTag</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/sequencenode/#a5848780917af6e4008594d684aaaa9db">llvm::yaml::SequenceNode::increment</a>.</p>

</div>
</div>

### setSourceRange() {#a6f5ca6a77c319906e8e16eda4c3642b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::Node::setSourceRange (<a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> SR)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>Reference <a href="#a6e1c6be4d6e0af6ef6ce23f3cad3966b">SourceRange</a>.</p>

</div>
</div>

### skip() {#ac41eb1b46bcf91022167e1dcf895b51f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::yaml::Node::skip ()</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#a1294ccf387b5a8f26c64b492fcc38d22">llvm::yaml::KeyValueNode::getValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#aa246fb4c384590219623e676f1a60b5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Node::anchor ()</td>
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

<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Doc {#a4c9c2bb039202b749ec9aceafadb7eee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Document&gt;&amp; llvm::yaml::Node::Doc</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>Referenced by <a href="#a4a3a9ae577da9991a159a2c5fb10b419">failed</a>, <a href="#ad3b1eb94e3f5985d5c964b830459710b">getAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#ab423b6588650879f12890d97837328ba">llvm::yaml::KeyValueNode::getKey</a>, <a href="#af6421e485ae3e23017b17b19eabad4f2">getNext</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#a1294ccf387b5a8f26c64b492fcc38d22">llvm::yaml::KeyValueNode::getValue</a>, <a href="#a388e35e6191f5f51957c3024ef635190">getVerbatimTag</a>, <a href="#aebd3b856bc2b481175bdd1e55a0e2d9e">parseBlockNode</a>, <a href="#af768a9bd2b66618730d44a81343f70f9">peekNext</a> and <a href="#aed7304613d5892b3f9526e63908e0b9a">setError</a>.</p>

</div>
</div>

### SourceRange {#a6e1c6be4d6e0af6ef6ce23f3cad3966b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMRange llvm::yaml::Node::SourceRange</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/yaml/blockscalarnode/#a85f1cad503bb4c8ac78b28b75832d5b8">llvm::yaml::BlockScalarNode::BlockScalarNode</a>, <a href="#ad91e8eeb22d3f235f9d2b378447a7658">getSourceRange</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/scalarnode/#a8cd838d3dcf1efd1367cbed9a0f8a69b">llvm::yaml::ScalarNode::ScalarNode</a> and <a href="#a6f5ca6a77c319906e8e16eda4c3642b9">setSourceRange</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Anchor {#a739e0034a32574483b7b640c8cd2f6d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::yaml::Node::Anchor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>

</div>
</div>

### Tag {#ae4c89c5b44eb4708a8e3e070301524b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::yaml::Node::Tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The tag as typed in the document.</p>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>

</div>
</div>

### TypeID {#a795ee6874f865280a0c365a56a3b78a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::yaml::Node::TypeID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>

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
