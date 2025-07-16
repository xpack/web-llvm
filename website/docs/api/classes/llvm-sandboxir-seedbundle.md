---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/seedbundle
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SeedBundle` Class Reference

<p>A set of candidate Instructions for vectorizing together. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::SeedBundle { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">llvm/Transforms/Vectorize/SandboxVectorizer/SeedCollector.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/memseedbundle">MemSeedBundle&lt;LoadOrStoreT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialization of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedbundle">SeedBundle</a> for memory access instructions. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memseedbundle/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/memseedbundle">MemSeedBundle&lt;LoadOrStoreT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialization of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedbundle">SeedBundle</a> for memory access instructions. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memseedbundle/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/memseedbundle">MemSeedBundle&lt;LoadOrStoreT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialization of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedbundle">SeedBundle</a> for memory access instructions. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memseedbundle/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25966e0212c8c200c3f108a41d7e22ba">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * &gt;::iterator</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3b55625ec1cf41a52fd3fd60d7b6008">const_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * &gt;::const_iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcf041cbce38b40cc2765f7a1c5183c9">SeedBundle</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize a bundle with <span class="doxyComputerOutput">I</span>. <a href="#abcf041cbce38b40cc2765f7a1c5183c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca41cf5428be5168a21ead42cccc6cc">SeedBundle</a> (SmallVector&lt; Instruction * &gt; &amp;&amp;L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a932695b91d038b3bffe080e1ec9900ee">SeedBundle</a> (const SeedBundle &amp;)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>No need to allow copies. <a href="#a932695b91d038b3bffe080e1ec9900ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17b7404d7e1c1631d27cb76b3bb8ca1e">~SeedBundle</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedbundle">SeedBundle</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1528b30d9333f038ea368ab7b997178d">operator=</a> (const SeedBundle &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac42d15e5cc1ecea396bba3b9a523e6a1">operator[]</a> (unsigned Idx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a25966e0212c8c200c3f108a41d7e22ba">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29e64a05490817b14b7f8e26f57e1a6b">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a25966e0212c8c200c3f108a41d7e22ba">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d71a328a2b9b1827dd4f8f704581047">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac3b55625ec1cf41a52fd3fd60d7b6008">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88763e0728d69e6f25d9f06ce4f36fa1">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac3b55625ec1cf41a52fd3fd60d7b6008">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad444fde3846e19fd5ef957b612a04ee8">end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d63423056e426e6f51b8a866a4021fa">insertAt</a> (iterator Pos, Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert <span class="doxyComputerOutput">I</span> into position <span class="doxyComputerOutput">P</span>. <a href="#a7d63423056e426e6f51b8a866a4021fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab66fdbedf113c1f09824ab89e65b8886">insert</a> (Instruction *I, ScalarEvolution &amp;SE)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd00778d6d1868b3b847ad3a678a7c4d">getFirstUnusedElementIdx</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9823456565f3d5c54902857ef08eb379">setUsed</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Marks instruction <span class="doxyComputerOutput">I</span> "used" within the bundle. <a href="#a9823456565f3d5c54902857ef08eb379">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b326cc642a333805cfa5aa71497e0c9">setUsed</a> (unsigned ElementIdx, unsigned Sz=1, bool VerifyUnused=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fb177e5ac1738fdc4dd1dfc2bf619b2">isUsed</a> (unsigned Element) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns whether or not <span class="doxyComputerOutput">Element</span> has been used. <a href="#a2fb177e5ac1738fdc4dd1dfc2bf619b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bbf6a3cdafc7ddcefb14736bfcbbe31">allUsed</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80e62a5d59fb4223760482558e69094b">getNumUnusedBits</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75a54304c99ee264027c946c229d2ab6">getSlice</a> (unsigned StartIdx, unsigned MaxVecRegBits, bool ForcePowOf2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns a slice of seed elements, starting at the element <span class="doxyComputerOutput">StartIdx</span>, with a total size &lt;= <span class="doxyComputerOutput">MaxVecRegBits</span>, or an empty slice if the requirements cannot be met . <a href="#a75a54304c99ee264027c946c229d2ab6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac37f71f52281256162fb50cdc7117a31">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the number of seed elements in the bundle. <a href="#ac37f71f52281256162fb50cdc7117a31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4df5511d40840b3d310d92bfbe6806d">dump</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb2341568ceba242cfe990f24680a7e5">dump</a> () const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5df5d71163f4407f8d995939b4c5993a">Seeds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1353bd4e3ac7b3c60cd0cff03fcb499">UsedLanes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The lanes that we have already vectorized. <a href="#ad1353bd4e3ac7b3c60cd0cff03fcb499">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4a9272150a492d070f1be20a5f9bf52">UsedLaneCount</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tracks used lanes for constant-time accessor. <a href="#ad4a9272150a492d070f1be20a5f9bf52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8edc4eafc77c1d87a3a6ea498931aa0b">NumUnusedBits</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tracks the remaining bits available to vectorize. <a href="#a8edc4eafc77c1d87a3a6ea498931aa0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A set of candidate Instructions for vectorizing together.</p>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#ac3b55625ec1cf41a52fd3fd60d7b6008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sandboxir::SeedBundle::const_iterator =  SmallVector&lt;Instruction *&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>

</div>
</div>

### iterator {#a25966e0212c8c200c3f108a41d7e22ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sandboxir::SeedBundle::iterator =  SmallVector&lt;Instruction *&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SeedBundle() {#abcf041cbce38b40cc2765f7a1c5183c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::SeedBundle::SeedBundle (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize a bundle with <span class="doxyComputerOutput">I</span>.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>References <a href="#a29e64a05490817b14b7f8e26f57e1a6b">begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a7d63423056e426e6f51b8a866a4021fa">insertAt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memseedbundle/#afaf77f4e01bfce176b32a6218375374d">llvm::sandboxir::MemSeedBundle&lt; sandboxir::StoreInst &gt;::MemSeedBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memseedbundle/#a5d9eeeed10260d334e4fa005d77f6637">llvm::sandboxir::MemSeedBundle&lt; sandboxir::StoreInst &gt;::MemSeedBundle</a>, <a href="#a1528b30d9333f038ea368ab7b997178d">operator=</a> and <a href="#a932695b91d038b3bffe080e1ec9900ee">SeedBundle</a>.</p>

</div>
</div>

### SeedBundle() {#aaca41cf5428be5168a21ead42cccc6cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::SeedBundle::SeedBundle (<a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * &gt; &amp;&amp; L)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/utils/#a880037a6ce1e268642581425f4f44c5f">llvm::sandboxir::Utils::getNumBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#a8edc4eafc77c1d87a3a6ea498931aa0b">NumUnusedBits</a> and <a href="#a5df5d71163f4407f8d995939b4c5993a">Seeds</a>.</p>

</div>
</div>

### SeedBundle() {#a932695b91d038b3bffe080e1ec9900ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::SeedBundle::SeedBundle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedbundle">SeedBundle</a> &amp;)</td>
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

<p>No need to allow copies.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>Reference <a href="#abcf041cbce38b40cc2765f7a1c5183c9">SeedBundle</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SeedBundle() {#a17b7404d7e1c1631d27cb76b3bb8ca1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::sandboxir::SeedBundle::~SeedBundle ()</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#ac42d15e5cc1ecea396bba3b9a523e6a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::sandboxir::SeedBundle::operator[] (unsigned Idx)</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>Reference <a href="#a5df5d71163f4407f8d995939b4c5993a">Seeds</a>.</p>

</div>
</div>

### operator=() {#a1528b30d9333f038ea368ab7b997178d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SeedBundle &amp; llvm::sandboxir::SeedBundle::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedbundle">SeedBundle</a> &amp;)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>Reference <a href="#abcf041cbce38b40cc2765f7a1c5183c9">SeedBundle</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allUsed() {#a5bbf6a3cdafc7ddcefb14736bfcbbe31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::SeedBundle::allUsed ()</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>References <a href="#a5df5d71163f4407f8d995939b4c5993a">Seeds</a> and <a href="#ad4a9272150a492d070f1be20a5f9bf52">UsedLaneCount</a>.</p>

</div>
</div>

### begin() {#a29e64a05490817b14b7f8e26f57e1a6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::sandboxir::SeedBundle::begin ()</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>Reference <a href="#a5df5d71163f4407f8d995939b4c5993a">Seeds</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memseedbundle/#af9bf47b55127bc4dab70c2a450ee1a27">llvm::sandboxir::MemSeedBundle&lt; sandboxir::StoreInst &gt;::insert</a>, <a href="#abcf041cbce38b40cc2765f7a1c5183c9">SeedBundle</a> and <a href="#a9823456565f3d5c54902857ef08eb379">setUsed</a>.</p>

</div>
</div>

### begin() {#a88763e0728d69e6f25d9f06ce4f36fa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::sandboxir::SeedBundle::begin ()</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>Reference <a href="#a5df5d71163f4407f8d995939b4c5993a">Seeds</a>.</p>

</div>
</div>

### dump() {#ad4df5511d40840b3d310d92bfbe6806d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::SeedBundle::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a> and <a href="#a2fb177e5ac1738fdc4dd1dfc2bf619b2">isUsed</a>.</p>

</div>
</div>

### dump() {#adb2341568ceba242cfe990f24680a7e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void llvm::sandboxir::SeedBundle::dump ()</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#adb2341568ceba242cfe990f24680a7e5">dump</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>


<p>Referenced by <a href="#adb2341568ceba242cfe990f24680a7e5">dump</a>.</p>

</div>
</div>

### end() {#a9d71a328a2b9b1827dd4f8f704581047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::sandboxir::SeedBundle::end ()</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>Reference <a href="#a5df5d71163f4407f8d995939b4c5993a">Seeds</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memseedbundle/#af9bf47b55127bc4dab70c2a450ee1a27">llvm::sandboxir::MemSeedBundle&lt; sandboxir::StoreInst &gt;::insert</a> and <a href="#a9823456565f3d5c54902857ef08eb379">setUsed</a>.</p>

</div>
</div>

### end() {#ad444fde3846e19fd5ef957b612a04ee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::sandboxir::SeedBundle::end ()</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>Reference <a href="#a5df5d71163f4407f8d995939b4c5993a">Seeds</a>.</p>

</div>
</div>

### getFirstUnusedElementIdx() {#abd00778d6d1868b3b847ad3a678a7c4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::SeedBundle::getFirstUnusedElementIdx ()</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>References <a href="#a2fb177e5ac1738fdc4dd1dfc2bf619b2">isUsed</a>, <a href="#a5df5d71163f4407f8d995939b4c5993a">Seeds</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>.</p>

</div>
</div>

### getNumUnusedBits() {#a80e62a5d59fb4223760482558e69094b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::SeedBundle::getNumUnusedBits ()</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>Reference <a href="#a8edc4eafc77c1d87a3a6ea498931aa0b">NumUnusedBits</a>.</p>

</div>
</div>

### getSlice() {#a75a54304c99ee264027c946c229d2ab6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Instruction * &gt; llvm::sandboxir::SeedBundle::getSlice (unsigned StartIdx, unsigned MaxVecRegBits, bool ForcePowOf2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\Returns a slice of seed elements, starting at the element <span class="doxyComputerOutput">StartIdx</span>, with a total size &lt;= <span class="doxyComputerOutput">MaxVecRegBits</span>, or an empty slice if the requirements cannot be met .</p>


<p>If <span class="doxyComputerOutput">ForcePowOf2</span> is true, then the returned slice will have a total number of bits that is a power of 2.</p>


<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/seedcollector-cpp">SeedCollector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/utils/#a880037a6ce1e268642581425f4f44c5f">llvm::sandboxir::Utils::getNumBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="#a2fb177e5ac1738fdc4dd1dfc2bf619b2">isUsed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="#a5df5d71163f4407f8d995939b4c5993a">Seeds</a>.</p>

</div>
</div>

### insert() {#ab66fdbedf113c1f09824ab89e65b8886}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::sandboxir::SeedBundle::insert (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### insertAt() {#a7d63423056e426e6f51b8a866a4021fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::SeedBundle::insertAt (<a href="#a25966e0212c8c200c3f108a41d7e22ba">iterator</a> Pos, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
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

<p>Insert <span class="doxyComputerOutput">I</span> into position <span class="doxyComputerOutput">P</span>.</p>


<p>Clients should choose Pos by symbol, symbol-offset, and program order (which depends if scheduling bottom-up or top-down).</p>


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/utils/#a880037a6ce1e268642581425f4f44c5f">llvm::sandboxir::Utils::getNumBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a8edc4eafc77c1d87a3a6ea498931aa0b">NumUnusedBits</a> and <a href="#a5df5d71163f4407f8d995939b4c5993a">Seeds</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memseedbundle/#af9bf47b55127bc4dab70c2a450ee1a27">llvm::sandboxir::MemSeedBundle&lt; sandboxir::StoreInst &gt;::insert</a> and <a href="#abcf041cbce38b40cc2765f7a1c5183c9">SeedBundle</a>.</p>

</div>
</div>

### isUsed() {#a2fb177e5ac1738fdc4dd1dfc2bf619b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::SeedBundle::isUsed (unsigned Element)</td>
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

<p>\Returns whether or not <span class="doxyComputerOutput">Element</span> has been used.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>Reference <a href="#ad1353bd4e3ac7b3c60cd0cff03fcb499">UsedLanes</a>.</p>


<p>Referenced by <a href="#ad4df5511d40840b3d310d92bfbe6806d">dump</a>, <a href="#abd00778d6d1868b3b847ad3a678a7c4d">getFirstUnusedElementIdx</a> and <a href="#a75a54304c99ee264027c946c229d2ab6">getSlice</a>.</p>

</div>
</div>

### setUsed() {#a9823456565f3d5c54902857ef08eb379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::SeedBundle::setUsed (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
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

<p>Marks instruction <span class="doxyComputerOutput">I</span> "used" within the bundle.</p>


<p>Clients use this property when assembling a vectorized instruction from the seeds in a bundle. This allows constant time evaluation and "removal" from the list.</p>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a29e64a05490817b14b7f8e26f57e1a6b">begin</a>, <a href="#a9d71a328a2b9b1827dd4f8f704581047">end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a9823456565f3d5c54902857ef08eb379">setUsed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedcontainer/#af9677e9c84bd51005de775c187f17c3c">llvm::sandboxir::SeedContainer::erase</a> and <a href="#a9823456565f3d5c54902857ef08eb379">setUsed</a>.</p>

</div>
</div>

### setUsed() {#a6b326cc642a333805cfa5aa71497e0c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::SeedBundle::setUsed (unsigned ElementIdx, unsigned Sz=1, bool VerifyUnused=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/utils/#a880037a6ce1e268642581425f4f44c5f">llvm::sandboxir::Utils::getNumBits</a>, <a href="#a8edc4eafc77c1d87a3a6ea498931aa0b">NumUnusedBits</a>, <a href="#a5df5d71163f4407f8d995939b4c5993a">Seeds</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>, <a href="#ad4a9272150a492d070f1be20a5f9bf52">UsedLaneCount</a> and <a href="#ad1353bd4e3ac7b3c60cd0cff03fcb499">UsedLanes</a>.</p>

</div>
</div>

### size() {#ac37f71f52281256162fb50cdc7117a31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::size_t llvm::sandboxir::SeedBundle::size ()</td>
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

<p>\Returns the number of seed elements in the bundle.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>Reference <a href="#a5df5d71163f4407f8d995939b4c5993a">Seeds</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### NumUnusedBits {#a8edc4eafc77c1d87a3a6ea498931aa0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::SeedBundle::NumUnusedBits = 0</td>
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

<p>Tracks the remaining bits available to vectorize.</p>

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>Referenced by <a href="#a80e62a5d59fb4223760482558e69094b">getNumUnusedBits</a>, <a href="#a7d63423056e426e6f51b8a866a4021fa">insertAt</a>, <a href="#aaca41cf5428be5168a21ead42cccc6cc">SeedBundle</a> and <a href="#a6b326cc642a333805cfa5aa71497e0c9">setUsed</a>.</p>

</div>
</div>

### Seeds {#a5df5d71163f4407f8d995939b4c5993a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *&gt; llvm::sandboxir::SeedBundle::Seeds</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>Referenced by <a href="#a5bbf6a3cdafc7ddcefb14736bfcbbe31">allUsed</a>, <a href="#a29e64a05490817b14b7f8e26f57e1a6b">begin</a>, <a href="#a88763e0728d69e6f25d9f06ce4f36fa1">begin</a>, <a href="#a9d71a328a2b9b1827dd4f8f704581047">end</a>, <a href="#ad444fde3846e19fd5ef957b612a04ee8">end</a>, <a href="#abd00778d6d1868b3b847ad3a678a7c4d">getFirstUnusedElementIdx</a>, <a href="#a75a54304c99ee264027c946c229d2ab6">getSlice</a>, <a href="#a7d63423056e426e6f51b8a866a4021fa">insertAt</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memseedbundle/#a5d9eeeed10260d334e4fa005d77f6637">llvm::sandboxir::MemSeedBundle&lt; sandboxir::StoreInst &gt;::MemSeedBundle</a>, <a href="#ac42d15e5cc1ecea396bba3b9a523e6a1">operator[]</a>, <a href="#aaca41cf5428be5168a21ead42cccc6cc">SeedBundle</a>, <a href="#a6b326cc642a333805cfa5aa71497e0c9">setUsed</a> and <a href="#ac37f71f52281256162fb50cdc7117a31">size</a>.</p>

</div>
</div>

### UsedLaneCount {#ad4a9272150a492d070f1be20a5f9bf52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::SeedBundle::UsedLaneCount = 0</td>
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

<p>Tracks used lanes for constant-time accessor.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>Referenced by <a href="#a5bbf6a3cdafc7ddcefb14736bfcbbe31">allUsed</a> and <a href="#a6b326cc642a333805cfa5aa71497e0c9">setUsed</a>.</p>

</div>
</div>

### UsedLanes {#ad1353bd4e3ac7b3c60cd0cff03fcb499}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::sandboxir::SeedBundle::UsedLanes</td>
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

<p>The lanes that we have already vectorized.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<p>Referenced by <a href="#a2fb177e5ac1738fdc4dd1dfc2bf619b2">isUsed</a> and <a href="#a6b326cc642a333805cfa5aa71497e0c9">setUsed</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/seedcollector-cpp">SeedCollector.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
