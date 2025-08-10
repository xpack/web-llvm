---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sectionkind
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SectionKind` Class

<p><a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> - This is a simple POD value that classifies the properties of a section. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SectionKind { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">llvm/MC/SectionKind.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Kind { <a href="#aa4afef01ba08eef605f5830330275a08">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6894a272b36a6e1eb42ef1c910dc5697">isMetadata</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67bb4ba77c5f9b2b8f47411ecbe1483a">isExclude</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a911975a33944b0773374a1e0eedf05a4">isText</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa19a6b1a0ba8bfd279117ef753792ba8">isExecuteOnly</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa418587893455f17ad8d4823b2242aa6">isReadOnly</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa449bc2673abc47ef9fe2a63bb55a274">isMergeableCString</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c547013d8a97063560b6c440aca687e">isMergeable1ByteCString</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12df776e476880942f780b54ff111319">isMergeable2ByteCString</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1716f8c782c39832401385a923c0d2a">isMergeable4ByteCString</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45f7cfa2079d73c55e232a34b2142e9a">isMergeableConst</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ea87f467e35c2d466c6a3fa019f1c66">isMergeableConst4</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55eab50d1a0f0c657f95e2125a244cee">isMergeableConst8</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad69fc93f0ec874dadb2296a57e9172ad">isMergeableConst16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d0f888b500014371c472b485a4ab3ee">isMergeableConst32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb631efd7c1a6c05461c549a6587120d">isWriteable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a855fc291efd8a8e431efba6ad7b5a156">isThreadLocal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a829252d906c3ff0aa7c2a7f011be08fc">isThreadBSS</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa328c680b268bc4ad5d932eeb05a368c">isThreadData</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14071b73bc38df9556c17bb05769223a">isThreadBSSLocal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa23169de2de4db5923f56558402c3b5">isGlobalWriteableData</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a102506ae69b258bfb413f538e29d78be">isBSS</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a530d168e733ea6e9f298d3f22dcee93d">isBSSLocal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8acd2c7eb8807ad6d82313d5e41b8fa1">isBSSExtern</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05dc1a27488527d1bcad7e0247f87776">isCommon</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0e6c4d69bde2f14afa179eaf2232d81">isData</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a94754e6aae7a9ef484245ac2862421">isReadOnlyWithRel</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum llvm::SectionKind::Kind</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93314e5863933cc4776f595eedc7f428">K</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13a2c76a48665ee3f4782fba7ddd72e1">getMetadata</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f52624d609dcde926bc28542a2905eb">getExclude</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36d55da4fb88dbef3b548a7e25c99dd7">getText</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf3d3001aed0f9ca52d21cf29d4f682a">getExecuteOnly</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4b0b8bc19062c7b0195fc7239c4dbea">getReadOnly</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aead4fda3e5d368447b9d19e1dccaf5d6">getMergeable1ByteCString</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ad9b570dc830b33dfa9cacdb86390b8">getMergeable2ByteCString</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab731cc61066d98cdd5da0e7f7407c8d8">getMergeable4ByteCString</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2617c9278391cedbbf9588aa7496b6da">getMergeableConst4</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a696d509cf70352c7846d8e7102dd0e81">getMergeableConst8</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7f2ce1ef7809115d038a2029fdffc2b">getMergeableConst16</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc5b59fd0fd4ca8acb949ebb61d79702">getMergeableConst32</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ca4fd7df1d9dc2cf7c4a1046d5b6957">getThreadBSS</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a047ddbdfed14ef00dfd7d11718be4cc1">getThreadData</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3711ddc5bc4960d036233522d9dc4bf6">getThreadBSSLocal</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97d95412f17878de8c47a9d13fd91871">getBSS</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22a2988fe4f2eaddfadb1918f75617e3">getBSSLocal</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10a7b1ca007e441de1a296980e351ee8">getBSSExtern</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cb1c8acc9369fd56127f27312420c3e">getCommon</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a587678b6051996e25d2bd6ebce323c9c">getData</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d239dea51a80324a3ce44985ed41dd4">getReadOnlyWithRel</a> ()</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b65c28d41fecc5dc88ff30aede5d957">get</a> (Kind K)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> - This is a simple POD value that classifies the properties of a section.</p>


<p>A section is classified into the deepest possible classification, and then the target maps them onto their sections based on what capabilities they have.</p>


<p>The comments below describe these as if they were an inheritance hierarchy in order to explain the predicates below.</p>


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Kind {#aa4afef01ba08eef605f5830330275a08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::SectionKind::Kind </td>
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
<td class="doxyEnumItemName">Metadata<a id="aa4afef01ba08eef605f5830330275a08ab1cbd788e4a65f4dfa2da217a5d00130"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> - Debug info sections or other metadata</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Exclude<a id="aa4afef01ba08eef605f5830330275a08a6707b2338cd40c17cd9522f6f9de53b8"></a></td>
<td class="doxyEnumItemDescription">Exclude - This section will be excluded from the final executable or shared library</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Text<a id="aa4afef01ba08eef605f5830330275a08a86606e628d06a26002ca94ad7ddff3e8"></a></td>
<td class="doxyEnumItemDescription">Text - Text section, used for functions and other executable code</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExecuteOnly<a id="aa4afef01ba08eef605f5830330275a08a4aec6e3abb35e95e22a457b159048def"></a></td>
<td class="doxyEnumItemDescription">ExecuteOnly, Text section that is not readable</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ReadOnly<a id="aa4afef01ba08eef605f5830330275a08ae1484357cd578d1cc9e54831c999c9e2"></a></td>
<td class="doxyEnumItemDescription">ReadOnly - Data that is never written to at program runtime by the program or the dynamic linker</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mergeable1ByteCString<a id="aa4afef01ba08eef605f5830330275a08a9e641d8a8f7167d5cf77737596542803"></a></td>
<td class="doxyEnumItemDescription">MergableCString - <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> null-terminated string which allows merging</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mergeable2ByteCString<a id="aa4afef01ba08eef605f5830330275a08ac0942b3ef76394b0cea8369b0e7b811c"></a></td>
<td class="doxyEnumItemDescription">Mergeable2ByteCString - 2 byte mergable, null terminated, string</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mergeable4ByteCString<a id="aa4afef01ba08eef605f5830330275a08a5dc4fd24912cec0498c629c21d568605"></a></td>
<td class="doxyEnumItemDescription">Mergeable4ByteCString - 4 byte mergable, null terminated, string</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MergeableConst4<a id="aa4afef01ba08eef605f5830330275a08ab102e91f8b28a2615109b98fc0c302fa"></a></td>
<td class="doxyEnumItemDescription">MergeableConst - These are sections for merging fixed-length constants together</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MergeableConst8<a id="aa4afef01ba08eef605f5830330275a08ae5e659a0c4df48870590c04a9a9a5f6b"></a></td>
<td class="doxyEnumItemDescription">MergeableConst8 - This is a section used by 8-byte constants, for example, doubles</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MergeableConst16<a id="aa4afef01ba08eef605f5830330275a08ac99563f03e4c2c232ee79feb1d925297"></a></td>
<td class="doxyEnumItemDescription">MergeableConst16 - This is a section used by 16-byte constants, for example, vectors</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MergeableConst32<a id="aa4afef01ba08eef605f5830330275a08a63e5c1223df420490f2afd1d32d66bc9"></a></td>
<td class="doxyEnumItemDescription">MergeableConst32 - This is a section used by 32-byte constants, for example, vectors</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ThreadBSS<a id="aa4afef01ba08eef605f5830330275a08a1da2736e763c546f0c373e52a03c22ff"></a></td>
<td class="doxyEnumItemDescription">Writeable - This is the base of all segments that need to be written to during program runtime</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ThreadData<a id="aa4afef01ba08eef605f5830330275a08aec6b230b7d4ea197de65157241c66f6b"></a></td>
<td class="doxyEnumItemDescription">ThreadData - Initialized TLS data objects</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ThreadBSSLocal<a id="aa4afef01ba08eef605f5830330275a08a203d0612ee4f6fa5b1d270f20de97ba0"></a></td>
<td class="doxyEnumItemDescription">ThreadBSSLocal - Zero-initialized TLS data objects with local linkage</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BSS<a id="aa4afef01ba08eef605f5830330275a08a2006fb47ff868a0144ad295adb379cc6"></a></td>
<td class="doxyEnumItemDescription">GlobalWriteableData - Writeable data that is global (not thread local)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BSSLocal<a id="aa4afef01ba08eef605f5830330275a08af892f42bac47d9a583a781f12e1ddee7"></a></td>
<td class="doxyEnumItemDescription">BSSLocal - This is BSS (zero initialized and writable) data which has local linkage</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BSSExtern<a id="aa4afef01ba08eef605f5830330275a08afc109b8ae00d245a61f3b4b6b5eccd13"></a></td>
<td class="doxyEnumItemDescription">BSSExtern - This is BSS data with normal external linkage</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Common<a id="aa4afef01ba08eef605f5830330275a08a7f06a268d027749c2280feb9f16c2341"></a></td>
<td class="doxyEnumItemDescription">Common - Data with common linkage</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Data<a id="aa4afef01ba08eef605f5830330275a08a3eec60d1a3f02f9eeb9b8137e32a742b"></a></td>
<td class="doxyEnumItemDescription">This is writeable data that has a non-zero initializer</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ReadOnlyWithRel<a id="aa4afef01ba08eef605f5830330275a08a7578a99b401f88cf77c373228566489b"></a></td>
<td class="doxyEnumItemDescription">ReadOnlyWithRel - These are global variables that are never written to by the program, but that have relocations, so they must be stuck in a writeable section so that the dynamic linker can write to them</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isBSS() {#a102506ae69b258bfb413f538e29d78be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isBSS ()</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a> and <a href="#aaa23169de2de4db5923f56558402c3b5">isGlobalWriteableData</a>.</p>

</div>
</div>

### isBSSExtern() {#a8acd2c7eb8807ad6d82313d5e41b8fa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isBSSExtern ()</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>

</div>
</div>

### isBSSLocal() {#a530d168e733ea6e9f298d3f22dcee93d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isBSSLocal ()</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#ab62f64f95c7f4a90a4d54f55e1b39967">llvm::TargetLoweringObjectFileXCOFF::getTargetSymbol</a>.</p>

</div>
</div>

### isCommon() {#a05dc1a27488527d1bcad7e0247f87776}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isCommon ()</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a> and <a href="#aaa23169de2de4db5923f56558402c3b5">isGlobalWriteableData</a>.</p>

</div>
</div>

### isData() {#ac0e6c4d69bde2f14afa179eaf2232d81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isData ()</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="#aaa23169de2de4db5923f56558402c3b5">isGlobalWriteableData</a>.</p>

</div>
</div>

### isExclude() {#a67bb4ba77c5f9b2b8f47411ecbe1483a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isExclude ()</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>

</div>
</div>

### isExecuteOnly() {#aa19a6b1a0ba8bfd279117ef753792ba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isExecuteOnly ()</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>

</div>
</div>

### isGlobalWriteableData() {#aaa23169de2de4db5923f56558402c3b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isGlobalWriteableData ()</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>References <a href="#a102506ae69b258bfb413f538e29d78be">isBSS</a>, <a href="#a05dc1a27488527d1bcad7e0247f87776">isCommon</a>, <a href="#ac0e6c4d69bde2f14afa179eaf2232d81">isData</a> and <a href="#a1a94754e6aae7a9ef484245ac2862421">isReadOnlyWithRel</a>.</p>


<p>Referenced by <a href="#aeb631efd7c1a6c05461c549a6587120d">isWriteable</a>.</p>

</div>
</div>

### isMergeable1ByteCString() {#a6c547013d8a97063560b6c440aca687e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isMergeable1ByteCString ()</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>

</div>
</div>

### isMergeable2ByteCString() {#a12df776e476880942f780b54ff111319}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isMergeable2ByteCString ()</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>

</div>
</div>

### isMergeable4ByteCString() {#ab1716f8c782c39832401385a923c0d2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isMergeable4ByteCString ()</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>

</div>
</div>

### isMergeableConst() {#a45f7cfa2079d73c55e232a34b2142e9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isMergeableConst ()</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="#aa418587893455f17ad8d4823b2242aa6">isReadOnly</a>.</p>

</div>
</div>

### isMergeableConst16() {#ad69fc93f0ec874dadb2296a57e9172ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isMergeableConst16 ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>

</div>
</div>

### isMergeableConst32() {#a9d0f888b500014371c472b485a4ab3ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isMergeableConst32 ()</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>

</div>
</div>

### isMergeableConst4() {#a1ea87f467e35c2d466c6a3fa019f1c66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isMergeableConst4 ()</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>

</div>
</div>

### isMergeableConst8() {#a55eab50d1a0f0c657f95e2125a244cee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isMergeableConst8 ()</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>

</div>
</div>

### isMergeableCString() {#aa449bc2673abc47ef9fe2a63bb55a274}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isMergeableCString ()</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="#aa418587893455f17ad8d4823b2242aa6">isReadOnly</a>.</p>

</div>
</div>

### isMetadata() {#a6894a272b36a6e1eb42ef1c910dc5697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isMetadata ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>

</div>
</div>

### isReadOnly() {#aa418587893455f17ad8d4823b2242aa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isReadOnly ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>References <a href="#a45f7cfa2079d73c55e232a34b2142e9a">isMergeableConst</a> and <a href="#aa449bc2673abc47ef9fe2a63bb55a274">isMergeableCString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzsubtarget/#a863dc64d455bad08a3c673e12ddb3ccb">llvm::SystemZSubtarget::isAddressedViaADA</a>.</p>

</div>
</div>

### isReadOnlyWithRel() {#a1a94754e6aae7a9ef484245ac2862421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isReadOnlyWithRel ()</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="#aaa23169de2de4db5923f56558402c3b5">isGlobalWriteableData</a>.</p>

</div>
</div>

### isText() {#a911975a33944b0773374a1e0eedf05a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isText ()</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#ab62f64f95c7f4a90a4d54f55e1b39967">llvm::TargetLoweringObjectFileXCOFF::getTargetSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetobjectfile-cpp/#af73b94d9d74e3ce22b4b6b036054838a">isExecuteOnlyFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff/#aca55cedbb09d4be7f32f2c9abe4b0864">llvm::MCSectionXCOFF::useCodeAlign</a>.</p>

</div>
</div>

### isThreadBSS() {#a829252d906c3ff0aa7c2a7f011be08fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isThreadBSS ()</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>.</p>

</div>
</div>

### isThreadBSSLocal() {#a14071b73bc38df9556c17bb05769223a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isThreadBSSLocal ()</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#ab62f64f95c7f4a90a4d54f55e1b39967">llvm::TargetLoweringObjectFileXCOFF::getTargetSymbol</a>.</p>

</div>
</div>

### isThreadData() {#aa328c680b268bc4ad5d932eeb05a368c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isThreadData ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>.</p>

</div>
</div>

### isThreadLocal() {#a855fc291efd8a8e431efba6ad7b5a156}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isThreadLocal ()</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a> and <a href="#aeb631efd7c1a6c05461c549a6587120d">isWriteable</a>.</p>

</div>
</div>

### isWriteable() {#aeb631efd7c1a6c05461c549a6587120d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SectionKind::isWriteable ()</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>References <a href="#aaa23169de2de4db5923f56558402c3b5">isGlobalWriteableData</a> and <a href="#a855fc291efd8a8e431efba6ad7b5a156">isThreadLocal</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### K {#a93314e5863933cc4776f595eedc7f428}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::SectionKind::Kind llvm::SectionKind::K</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getBSS() {#a97d95412f17878de8c47a9d13fd91871}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getBSS ()</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a728a93afb3dc13272034c0f59100f0ea">getELFKindForNamedSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a684c8f59f91c7a9a03ed144fef80ba6a">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveZerofill</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmasmparser-cpp-/wasmasmparser/#ae0649c94bd0699e12841f9abe89b3548">anonymous{WasmAsmParser.cpp}::WasmAsmParser::parseSectionDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#a1e1a41ed95b25988970966b88d4362d3">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseSectionDirectiveBSS</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilegoff/#a8c58f11a5aa16a65fa81203993787033">llvm::TargetLoweringObjectFileGOFF::SelectSectionForGlobal</a>.</p>

</div>
</div>

### getBSSExtern() {#a10a7b1ca007e441de1a296980e351ee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getBSSExtern ()</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a>.</p>

</div>
</div>

### getBSSLocal() {#a22a2988fe4f2eaddfadb1918f75617e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getBSSLocal ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a>.</p>

</div>
</div>

### getCommon() {#a2cb1c8acc9369fd56127f27312420c3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getCommon ()</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a>.</p>

</div>
</div>

### getData() {#a587678b6051996e25d2bd6ebce323c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getData ()</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a4c3e35391c2381bd4ad1ab5365f8839a">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitGCOVRefs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a7bdbc0657e52a4bffa675c290b32840f">llvm::TargetLoweringObjectFileMachO::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a72781426d7490cd3b30118f02ea912e5">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitPGORefs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a2ddf5387f9cd603891e1933c2f84cf65">llvm::TargetLoweringObjectFileXCOFF::getSectionForExternalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#adee710107b7fec9dcf8076bd0dc44d2d">llvm::TargetLoweringObjectFileXCOFF::getSectionForFunctionDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilegoff/#a75c01c604ceb3f4e3a45c6ee4df1985f">llvm::TargetLoweringObjectFileGOFF::getSectionForLSDA</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a24e99c9fbb9fedd3a9b504d09ddfa21b">llvm::TargetLoweringObjectFileXCOFF::getSectionForTOCEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilewasm/#a5b6997ec5b6f4358e270f2e5d9be4657">llvm::TargetLoweringObjectFileWasm::getStaticCtorSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#ab62f64f95c7f4a90a4d54f55e1b39967">llvm::TargetLoweringObjectFileXCOFF::getTargetSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a7d28a673bee567a5551a2a3f21456bdf">llvm::TargetLoweringObjectFileMachO::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilewasm/#a43cbf327e1543318ec8d7a084634995a">llvm::TargetLoweringObjectFileWasm::InitializeWasm</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a757668838f5767cbf28d9a5b1201a646">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmasmparser-cpp-/wasmasmparser/#ae0649c94bd0699e12841f9abe89b3548">anonymous{WasmAsmParser.cpp}::WasmAsmParser::parseSectionDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#a050b8f83bcfb3b28fc0f8b8578055bbb">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseSectionDirectiveData</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#a19f152ba614afb40f98f4a4373239d75">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseSectionDirectiveDataRel</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#a47f8ba57afc24525a150ec78b22aa7b7">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseSectionDirectiveEhFrame</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#afa6dda813be79bdc7753ef52b9b5ec56">llvm::TargetLoweringObjectFileXCOFF::SelectSectionForGlobal</a>.</p>

</div>
</div>

### getExclude() {#a1f52624d609dcde926bc28542a2905eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getExclude ()</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a>.</p>

</div>
</div>

### getExecuteOnly() {#acf3d3001aed0f9ca52d21cf29d4f682a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getExecuteOnly ()</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armelftargetobjectfile/#a5ced1cd057a22569832c5a05e2ba3d3c">llvm::ARMElfTargetObjectFile::getExplicitSectionGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/armelftargetobjectfile/#a205849b661d3842c84d4c2926ad69e4d">llvm::ARMElfTargetObjectFile::SelectSectionForGlobal</a>.</p>

</div>
</div>

### getMergeable1ByteCString() {#aead4fda3e5d368447b9d19e1dccaf5d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getMergeable1ByteCString ()</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a>.</p>

</div>
</div>

### getMergeable2ByteCString() {#a1ad9b570dc830b33dfa9cacdb86390b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getMergeable2ByteCString ()</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a>.</p>

</div>
</div>

### getMergeable4ByteCString() {#ab731cc61066d98cdd5da0e7f7407c8d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getMergeable4ByteCString ()</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a>.</p>

</div>
</div>

### getMergeableConst16() {#aa7f2ce1ef7809115d038a2029fdffc2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getMergeableConst16 ()</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry/#aa50c9fb6d457212d9ab13ca370d0f24f">llvm::MachineConstantPoolEntry::getSectionKind</a>.</p>

</div>
</div>

### getMergeableConst32() {#afc5b59fd0fd4ca8acb949ebb61d79702}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getMergeableConst32 ()</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry/#aa50c9fb6d457212d9ab13ca370d0f24f">llvm::MachineConstantPoolEntry::getSectionKind</a>.</p>

</div>
</div>

### getMergeableConst4() {#a2617c9278391cedbbf9588aa7496b6da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getMergeableConst4 ()</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry/#aa50c9fb6d457212d9ab13ca370d0f24f">llvm::MachineConstantPoolEntry::getSectionKind</a>.</p>

</div>
</div>

### getMergeableConst8() {#a696d509cf70352c7846d8e7102dd0e81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getMergeableConst8 ()</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry/#aa50c9fb6d457212d9ab13ca370d0f24f">llvm::MachineConstantPoolEntry::getSectionKind</a>.</p>

</div>
</div>

### getMetadata() {#a13a2c76a48665ee3f4782fba7ddd72e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getMetadata ()</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#af0cbac92300c3074e6bb81d58e92a86b">llvm::WebAssemblyAsmPrinter::emitEndOfAsmFile</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#aedbc3a6b1ed39b77650edac4239774cf">llvm::WebAssemblyAsmPrinter::EmitFunctionAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#acda48e0ba94e27f00cbe44c1585fcfe7">emitNonLazyStubs</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a013467bb98e0c35a48763e22de49cc75">llvm::WebAssemblyAsmPrinter::EmitProducerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a06dab5b53d53c65a118f25ea11570352">llvm::WebAssemblyAsmPrinter::EmitTargetFeatures</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#adc76b392eb3df7f2d5456efe795060c3">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::finalizeCGProfile</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a728a93afb3dc13272034c0f59100f0ea">getELFKindForNamedSection</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetobjectfile/#ad5d93004504bd6d5129dbcbb758e5a28">llvm::AMDGPUTargetObjectFile::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a1d07788150d8bd44cbba78db405f1574">llvm::TargetLoweringObjectFileCOFF::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilewasm/#ad7fddd197449964ffb791c5a7e1900ec">llvm::TargetLoweringObjectFileWasm::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a2ddf5387f9cd603891e1933c2f84cf65">llvm::TargetLoweringObjectFileXCOFF::getSectionForExternalReference</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmasmparser-cpp-/wasmasmparser/#ae0649c94bd0699e12841f9abe89b3548">anonymous{WasmAsmParser.cpp}::WasmAsmParser::parseSectionDirective</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a6a3e2feaa7c55f28c3095ef8a747ae7d">transformCallee</a> and <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#af452e21aa5eefd6666ed1d0b693f770c">llvm::MachObjectWriter::writeObject</a>.</p>

</div>
</div>

### getReadOnly() {#af4b0b8bc19062c7b0195fc7239c4dbea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getReadOnly ()</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#a197edfada53c97843b5482baaced303f">llvm::X86AsmPrinter::emitEndOfAsmFile</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25e51557ff442df4d50f2ad5d1f55743">llvm::AsmPrinter::emitXRayTable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a8df1069695195b5c96f1cc2ebf3a3973">llvm::TargetLoweringObjectFileMachO::getSectionForCommandLines</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2e6b27fe4ea0394cff6ef3071a84ccc8">llvm::TargetLoweringObjectFile::getSectionForJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#ad75e2aa4d67c101594e1f7448588c8d3">llvm::TargetLoweringObjectFileCOFF::getSectionForJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a38d2d101b244807c73327e57f705ef7e">llvm::TargetLoweringObjectFileELF::getSectionForJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a59f70e2f83b2a97372e18a6c6316550d">llvm::TargetLoweringObjectFileXCOFF::getSectionForJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry/#aa50c9fb6d457212d9ab13ca370d0f24f">llvm::MachineConstantPoolEntry::getSectionKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmasmparser-cpp-/wasmasmparser/#ae0649c94bd0699e12841f9abe89b3548">anonymous{WasmAsmParser.cpp}::WasmAsmParser::parseSectionDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#ae8bef5533581f6ea443390a077d8e9aa">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseSectionDirectiveRoData</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#afa6dda813be79bdc7753ef52b9b5ec56">llvm::TargetLoweringObjectFileXCOFF::SelectSectionForGlobal</a>.</p>

</div>
</div>

### getReadOnlyWithRel() {#a3d239dea51a80324a3ce44985ed41dd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getReadOnlyWithRel ()</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25e51557ff442df4d50f2ad5d1f55743">llvm::AsmPrinter::emitXRayTable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry/#aa50c9fb6d457212d9ab13ca370d0f24f">llvm::MachineConstantPoolEntry::getSectionKind</a> and <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#afa5185f243533551982527fbbdf43c48">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseSectionDirectiveDataRelRo</a>.</p>

</div>
</div>

### getText() {#a36d55da4fb88dbef3b548a7e25c99dd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getText ()</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#abfcac3a9ee111cfe8a6df190086ca997">createMCSymbolForTlsGetAddr</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a6a9bfa14b2dfa291c65ec9f5c6657d27">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::doBeforeLabelEmit</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a3e40bda8245f90bbe4a72d083b4d8431">llvm::TargetLoweringObjectFileXCOFF::getFunctionEntryPointSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a050de8d61f37b8c99a85fe4a0f8deaf2">llvm::TargetLoweringObjectFileELF::getUniqueSectionForFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a757668838f5767cbf28d9a5b1201a646">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmasmparser-cpp-/wasmasmparser/#ae0649c94bd0699e12841f9abe89b3548">anonymous{WasmAsmParser.cpp}::WasmAsmParser::parseSectionDirective</a> and <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#aa01c3ae3e80c61f5e1b7b3bdd4531d18">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseSectionDirectiveText</a>.</p>

</div>
</div>

### getThreadBSS() {#a9ca4fd7df1d9dc2cf7c4a1046d5b6957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getThreadBSS ()</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a728a93afb3dc13272034c0f59100f0ea">getELFKindForNamedSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a865b1c6f63f4309779f26c93bd7030bf">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveTBSS</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmasmparser-cpp-/wasmasmparser/#ae0649c94bd0699e12841f9abe89b3548">anonymous{WasmAsmParser.cpp}::WasmAsmParser::parseSectionDirective</a> and <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#ad73cf42bb7872b5ac68300d9b983b9d5">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseSectionDirectiveTBSS</a>.</p>

</div>
</div>

### getThreadBSSLocal() {#a3711ddc5bc4960d036233522d9dc4bf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getThreadBSSLocal ()</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a>.</p>

</div>
</div>

### getThreadData() {#a047ddbdfed14ef00dfd7d11718be4cc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::getThreadData ()</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a728a93afb3dc13272034c0f59100f0ea">getELFKindForNamedSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmasmparser-cpp-/wasmasmparser/#ae0649c94bd0699e12841f9abe89b3548">anonymous{WasmAsmParser.cpp}::WasmAsmParser::parseSectionDirective</a> and <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#af83c9d55d064b72dc0495f6931f9107e">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseSectionDirectiveTData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### get() {#a6b65c28d41fecc5dc88ff30aede5d957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind llvm::SectionKind::get (Kind K)</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">SectionKind.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
