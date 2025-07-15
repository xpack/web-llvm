---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/symbol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Symbol` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> representation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::jitlink::Symbol { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">llvm/ExecutionEngine/JITLink/JITLink.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acff959e1f59ad4d940708fe62a722cf2">LinkGraph</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c18f9ab46d326665b4df1640dbe09fe">Symbol</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a null <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a>. <a href="#a1c18f9ab46d326665b4df1640dbe09fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4afe9b759b3f7b954b1d56756657d6d">Symbol</a> (const Symbol &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00b04694b62881379849b8766f8fd696">Symbol</a> (Symbol &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a599a1e4cbf49c619a0b4db084648218d">Symbol</a> (Addressable &amp;Base, orc::ExecutorAddrDiff Offset, orc::SymbolStringPtr &amp;&amp;Name, orc::ExecutorAddrDiff Size, Linkage L, Scope S, bool IsLive, bool IsCallable)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ff8bb7e6669278ec4aa44665b5c13fe">operator=</a> (const Symbol &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a119759ff072623c9bc403849b44290a4">operator=</a> (Symbol &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2cd363c45c4a9b5a8a2716d2effcd5a">hasName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this symbol has a name. <a href="#af2cd363c45c4a9b5a8a2716d2effcd5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">orc::SymbolStringPtr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37941163af977712e6ae68591327a0ad">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the name of this symbol (empty if the symbol is anonymous). <a href="#a37941163af977712e6ae68591327a0ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25d7c78dbe32fcd69796fc678f1fe66e">setName</a> (const orc::SymbolStringPtr Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rename this symbol. <a href="#a25d7c78dbe32fcd69796fc678f1fe66e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43970b0f29022d28a252b08004fd1985">isDefined</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> has content (potentially) defined within this object file (i.e. <a href="#a43970b0f29022d28a252b08004fd1985">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a334cd7ae116c60e38dfae56cea71dc32">isLive</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this symbol is live (i.e. <a href="#a334cd7ae116c60e38dfae56cea71dc32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4b13283e98f0c3bc7bfca579fed4a54">setLive</a> (bool IsLive)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set this symbol's live bit. <a href="#aa4b13283e98f0c3bc7bfca579fed4a54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15d4df0ad60a70e4074ccf11dfdc0164">isCallable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true is this symbol is callable. <a href="#a15d4df0ad60a70e4074ccf11dfdc0164">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1931d466e6005db8c3b8bf4cf92701c">setCallable</a> (bool IsCallable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set this symbol's callable bit. <a href="#af1931d466e6005db8c3b8bf4cf92701c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a31b65e4d98ba6601ffb8d7d3525932">isExternal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the underlying addressable is an unresolved external. <a href="#a0a31b65e4d98ba6601ffb8d7d3525932">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e5bb877f012989dc8e13fcc23af3e47">isAbsolute</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the underlying addressable is an absolute symbol. <a href="#a5e5bb877f012989dc8e13fcc23af3e47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/addressable">Addressable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71d066baade1a594e359a00f20a6b3c5">getAddressable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the addressable that this symbol points to. <a href="#a71d066baade1a594e359a00f20a6b3c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/addressable">Addressable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed1e3edc416186b125941bdf92de62dd">getAddressable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the addressable that this symbol points to. <a href="#aed1e3edc416186b125941bdf92de62dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabff9b121d2ef09251a802eac2c2201b">getBlock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> (<a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> must be defined). <a href="#aabff9b121d2ef09251a802eac2c2201b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a667735b9d55663b7650aca0a3b349abb">getBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> (<a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> must be defined). <a href="#a667735b9d55663b7650aca0a3b349abb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99c40db3f91fad3db60ba33e9fe93977">getSection</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> (<a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> must be defined). <a href="#a99c40db3f91fad3db60ba33e9fe93977">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a59b5f232ad8ec6bf405ddc77c3d6d752">orc::ExecutorAddrDiff</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf99a1d864f4b7910f81fde19758bd7c">getOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the offset for this symbol within the underlying addressable. <a href="#abf99a1d864f4b7910f81fde19758bd7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac64770573639fec35639f53fbf2d7874">setOffset</a> (orc::ExecutorAddrDiff NewOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">orc::ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9266b50b560808e8f69eb394690d79c4">getAddress</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the address of this symbol. <a href="#a9266b50b560808e8f69eb394690d79c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a59b5f232ad8ec6bf405ddc77c3d6d752">orc::ExecutorAddrDiff</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab790ccf24d158f2933ef1c6cf153fb62">getSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the size of this symbol. <a href="#ab790ccf24d158f2933ef1c6cf153fb62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4f650353789d23adbb0925d9a484ca0">setSize</a> (orc::ExecutorAddrDiff Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the size of this symbol. <a href="#ad4f650353789d23adbb0925d9a484ca0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange">orc::ExecutorAddrRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90d9031100757aa7cb003f5376233554">getRange</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the address range of this symbol. <a href="#a90d9031100757aa7cb003f5376233554">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc30302b2d19e010d8e5bfd6f2b8589c">isSymbolZeroFill</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this symbol is backed by a zero-fill block. <a href="#abc30302b2d19e010d8e5bfd6f2b8589c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93b09ffda91456ad8838782c225842d0">getSymbolContent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the content in the underlying block covered by this symbol. <a href="#a93b09ffda91456ad8838782c225842d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55f">Linkage</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76430b8581e0d1748b8615cf8130c283">getLinkage</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the linkage for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a>. <a href="#a76430b8581e0d1748b8615cf8130c283">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa68738aadf6d429383a1681a066ad5a1">setLinkage</a> (Linkage L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the linkage for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a>. <a href="#aa68738aadf6d429383a1681a066ad5a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fd">Scope</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51c33c919f5a66e0d0b9814b6b049363">getScope</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the visibility for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a>. <a href="#a51c33c919f5a66e0d0b9814b6b049363">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a0c8dc0edf87ed24a70d18ceee63c8d">setScope</a> (Scope S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the visibility for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a>. <a href="#a1a0c8dc0edf87ed24a70d18ceee63c8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abc9bc580a689ae42bea77b8de495a70c">TargetFlagsType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a3a9f494399398e41e672eeec440aa4">getTargetFlags</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the target flags of this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a>. <a href="#a2a3a9f494399398e41e672eeec440aa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79317850235f8bbbb52f51e7f3dec9ef">setTargetFlags</a> (TargetFlagsType Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the target flags for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a>. <a href="#a79317850235f8bbbb52f51e7f3dec9ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af217b3129ead780d884267c5ebda6cb2">isWeaklyReferenced</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is a weakly referenced external symbol. <a href="#af217b3129ead780d884267c5ebda6cb2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5a28a8b444f7fec3557f7f2b105ae4f">setWeaklyReferenced</a> (bool WeakRef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the WeaklyReferenced value for this symbol. <a href="#ae5a28a8b444f7fec3557f7f2b105ae4f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a177da4875578829f7085b228a547d533">makeExternal</a> (Addressable &amp;A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeff0882da0b48add7a623d5776195557">makeAbsolute</a> (Addressable &amp;A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2eead45c4d5b412ddb11b0f9abf98e0">setBlock</a> (Block &amp;B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">orc::SymbolStringPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18df29f80afcdd80f42f1ec79a4fbcd9">Name</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/addressable">Addressable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ceb52e51ab426283142e1f01bcb14af">Base</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72b7616b0978df643f2fd9cabc3128f2">Offset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02cda0ac29136fb5125ae0ce6bd00d72">L</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf1ea7335ab6833e7bd61371add0eb83">S</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e601c0fd3099059d8ee54f638ac27ad">IsLive</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80ed2917322fea639e3bd95fba7a022f">IsCallable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76edc320bdec8660ea64f32623865497">WeakRef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87cf84d3dfa583ce6d6782b64feab1a9">TargetFlags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c5736876ee9943ba0d1d2d81dbd2e6d">Size</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1a55753370909590510de3aeabdd8f3">constructExternal</a> (BumpPtrAllocator &amp;Allocator, Addressable &amp;Base, orc::SymbolStringPtr &amp;&amp;Name, orc::ExecutorAddrDiff Size, Linkage L, bool WeaklyReferenced)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96fcb8ce08a68aad21ad2da4e7c528a2">constructAbsolute</a> (BumpPtrAllocator &amp;Allocator, Addressable &amp;Base, orc::SymbolStringPtr &amp;&amp;Name, orc::ExecutorAddrDiff Size, Linkage L, Scope S, bool IsLive)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a071f781e5fbf8914454b394489e334ad">constructAnonDef</a> (BumpPtrAllocator &amp;Allocator, Block &amp;Base, orc::ExecutorAddrDiff Offset, orc::ExecutorAddrDiff Size, bool IsCallable, bool IsLive)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c1bbad999131def7acd1694a31955ce">constructNamedDef</a> (BumpPtrAllocator &amp;Allocator, Block &amp;Base, orc::ExecutorAddrDiff Offset, orc::SymbolStringPtr Name, orc::ExecutorAddrDiff Size, Linkage L, Scope S, bool IsLive, bool IsCallable)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24b126c3c80653ac4ef01abff2722fa8">MaxOffset</a> = (1ULL &lt;&lt; 59) - 1</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> representation.</p>


<p>Symbols represent locations within <a href="/web-llvm/docs/api/classes/llvm/jitlink/addressable">Addressable</a> objects. They can be either Named or Anonymous. Anonymous symbols have neither linkage nor visibility, and must point at ContentBlocks. Named symbols may be in one of four states:</p>


<ul class="doxyList ">
<li>Null: Default initialized. Assignable, but otherwise unusable.</li>
<li>Defined: Has both linkage and visibility and points to a ContentBlock</li>
<li>Common: Has both linkage and visibility, points to a null <a href="/web-llvm/docs/api/classes/llvm/jitlink/addressable">Addressable</a>.</li>
<li>External: Has neither linkage nor visibility, points to an external <a href="/web-llvm/docs/api/classes/llvm/jitlink/addressable">Addressable</a>.</li>
</ul>

<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<div class="doxySectionDef">

## Friends

### LinkGraph {#acff959e1f59ad4d940708fe62a722cf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>References <a href="#acff959e1f59ad4d940708fe62a722cf2">LinkGraph</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="#acff959e1f59ad4d940708fe62a722cf2">LinkGraph</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Symbol() {#a1c18f9ab46d326665b4df1640dbe09fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::Symbol::Symbol ()</td>
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

<p>Create a null <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a>.</p>


<p>This allows Symbols to be default initialized for use in containers (e.g. as map values). Null symbols are only useful for assigning to.</p>


<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### Symbol() {#ad4afe9b759b3f7b954b1d56756657d6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::Symbol::Symbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;)</td>
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



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### Symbol() {#a00b04694b62881379849b8766f8fd696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::Symbol::Symbol (<a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;&amp;)</td>
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



<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### Symbol() {#a599a1e4cbf49c619a0b4db084648218d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::Symbol::Symbol (<a href="/web-llvm/docs/api/classes/llvm/jitlink/addressable">Addressable</a> &amp; Base, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a59b5f232ad8ec6bf405ddc77c3d6d752">orc::ExecutorAddrDiff</a> Offset, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">orc::SymbolStringPtr</a> &amp;&amp; Name, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a59b5f232ad8ec6bf405ddc77c3d6d752">orc::ExecutorAddrDiff</a> Size, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55f">Linkage</a> L, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fd">Scope</a> S, bool IsLive, bool IsCallable)</td>
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



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a9ff8bb7e6669278ec4aa44665b5c13fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::Symbol::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;)</td>
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



<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### operator=() {#a119759ff072623c9bc403849b44290a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::Symbol::operator= (<a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;&amp;)</td>
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



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAddress() {#a9266b50b560808e8f69eb394690d79c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">orc::ExecutorAddr llvm::jitlink::Symbol::getAddress ()</td>
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

<p>Returns the address of this symbol.</p>

<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a86c56f594b268ffb1f273fc4bc0f140b">llvm::orc::addFunctionPointerRelocationsToCurrentSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symboladdressmap/#accd9d70c3caa1eb8cdeb536dc89a19b1">llvm::jitlink::SymbolAddressMap::addSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#a61310b6c90769dc38a55a4b84b1cc054">llvm::jitlink::aarch64::applyFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/i386/#a1cf84875ae743236d8dd98fd56af9f7b">llvm::jitlink::i386::applyFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a5a393f897c1439c03e7ef35e7874a8a1">llvm::jitlink::ppc64::applyFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#a4640b55f4a0124796c017fc725e87add">llvm::jitlink::x86_64::applyFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a53f135c84cfb135c8e3f890659a3f782">llvm::jitlink::aarch32::applyFixupArm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a2cc2e3fa12d8c5d0d37310647c9c3a4d">llvm::jitlink::aarch32::applyFixupData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a183363f7e8482b2c1e193956dea835ee">llvm::jitlink::aarch32::applyFixupThumb</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#ac0d41cae6559f87a6e26f2db6c30f24d">anonymous{PerfSupportPlugin.cpp}::getCodeLoadRecord</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#ac931ae3a09278d920ebb024da87edf2e">anonymous{PerfSupportPlugin.cpp}::getDebugInfoRecord</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-linkgraphlinkinglayer-cpp-/#ad7ab6c07e2f58775b2e014b2951243d7">anonymous{LinkGraphLinkingLayer.cpp}::getJITSymbolPtrForSymbol</a>, <a href="#a90d9031100757aa7cb003f5376233554">getRange</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a7aba1f4a32c3fabbf47d602a87052e46">llvm::jitlink::operator&lt;&lt;</a>.</p>

</div>
</div>

### getAddressable() {#a71d066baade1a594e359a00f20a6b3c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Addressable &amp; llvm::jitlink::Symbol::getAddressable ()</td>
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

<p>Return the addressable that this symbol points to.</p>

<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a07bfacd5c211410dc0226f08c7a5ebce">llvm::jitlink::LinkGraph::makeAbsolute</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a59c9ca37089df82fc40d87466f05dff6">llvm::jitlink::LinkGraph::makeExternal</a>.</p>

</div>
</div>

### getAddressable() {#aed1e3edc416186b125941bdf92de62dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Addressable &amp; llvm::jitlink::Symbol::getAddressable ()</td>
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

<p>Return the addressable that this symbol points to.</p>

<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getBlock() {#aabff9b121d2ef09251a802eac2c2201b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Block &amp; llvm::jitlink::Symbol::getBlock ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> (<a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> must be defined).</p>

<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a86c56f594b268ffb1f273fc4bc0f140b">llvm::orc::addFunctionPointerRelocationsToCurrentSymbol</a>, <a href="#a99c40db3f91fad3db60ba33e9fe93977">getSection</a>, <a href="#a93b09ffda91456ad8838782c225842d0">getSymbolContent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#aad348d4076f9c54b8c66cbd6fbda4453">llvm::jitlink::initRelaxAux</a>, <a href="#abc30302b2d19e010d8e5bfd6f2b8589c">isSymbolZeroFill</a>, <a href="#ac64770573639fec35639f53fbf2d7874">setOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#ad0477be3c74794e35bec0c8f16e8a8ef">llvm::jitlink::LinkGraph::transferBlock</a>.</p>

</div>
</div>

### getBlock() {#a667735b9d55663b7650aca0a3b349abb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Block &amp; llvm::jitlink::Symbol::getBlock ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> (<a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> must be defined).</p>

<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getLinkage() {#a76430b8581e0d1748b8615cf8130c283}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Linkage llvm::jitlink::Symbol::getLinkage ()</td>
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

<p>Get the linkage for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a>.</p>

<p>Definition at line 633 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlayer/#a99fe4a708e2a83ed2e9aaf8c3d909a1b">llvm::orc::LinkGraphLayer::getJITSymbolFlagsForSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a061c97aa3532f0b4a2390febaa911a65">llvm::jitlink::makeTargetOutOfRangeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a7aba1f4a32c3fabbf47d602a87052e46">llvm::jitlink::operator&lt;&lt;</a>.</p>

</div>
</div>

### getName() {#a37941163af977712e6ae68591327a0ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const orc::SymbolStringPtr &amp; llvm::jitlink::Symbol::getName ()</td>
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

<p>Returns the name of this symbol (empty if the symbol is anonymous).</p>

<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a51c33c919f5a66e0d0b9814b6b049363">getScope</a>, <a href="#af2cd363c45c4a9b5a8a2716d2effcd5a">hasName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fda509820290d57f333403f490dde7316f4">llvm::jitlink::Local</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#aca91868ff6f556044eb81de0e58d2d91">llvm::jitlink::LinkGraph::addAbsoluteSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a4dc9623feac4601926e787421a0690f7">llvm::jitlink::LinkGraph::addDefinedSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a86c56f594b268ffb1f273fc4bc0f140b">llvm::orc::addFunctionPointerRelocationsToCurrentSymbol</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#ac0d41cae6559f87a6e26f2db6c30f24d">anonymous{PerfSupportPlugin.cpp}::getCodeLoadRecord</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#ac931ae3a09278d920ebb024da87edf2e">anonymous{PerfSupportPlugin.cpp}::getDebugInfoRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#add5a775ece6c949eb80021abd7f49bc8">llvm::jitlink::identifyELFSectionStartAndEndSymbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#afee996fb446b6f03d652d052d97cf0a5">llvm::jitlink::identifyMachOSectionStartAndEndSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a07bfacd5c211410dc0226f08c7a5ebce">llvm::jitlink::LinkGraph::makeAbsolute</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#ab77236dd7d9ffb67698e20fedb91e64e">llvm::jitlink::LinkGraph::makeDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a59c9ca37089df82fc40d87466f05dff6">llvm::jitlink::LinkGraph::makeExternal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a061c97aa3532f0b4a2390febaa911a65">llvm::jitlink::makeTargetOutOfRangeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a7aba1f4a32c3fabbf47d602a87052e46">llvm::jitlink::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/compactunwindmanager/#ab91679cd4a3a613219f1835a2d25c3f1">llvm::jitlink::CompactUnwindManager&lt; CURecTraits &gt;::prepareForPrune</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a176bad8525301279eb900082ce8491af">llvm::jitlink::LinkGraph::removeExternalSymbol</a>.</p>

</div>
</div>

### getOffset() {#abf99a1d864f4b7910f81fde19758bd7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">orc::ExecutorAddrDiff llvm::jitlink::Symbol::getOffset ()</td>
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

<p>Returns the offset for this symbol within the underlying addressable.</p>

<p>Definition at line 594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a86c56f594b268ffb1f273fc4bc0f140b">llvm::orc::addFunctionPointerRelocationsToCurrentSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#aad348d4076f9c54b8c66cbd6fbda4453">llvm::jitlink::initRelaxAux</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a07bfacd5c211410dc0226f08c7a5ebce">llvm::jitlink::LinkGraph::makeAbsolute</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a59c9ca37089df82fc40d87466f05dff6">llvm::jitlink::LinkGraph::makeExternal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a7aba1f4a32c3fabbf47d602a87052e46">llvm::jitlink::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ad80e7bb9ca75bc924f1a6dfeb9ef3efb">llvm::jitlink::relaxBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/cofflinkgraphbuilder/#a9690c261c77ea099495994241706bc25">llvm::jitlink::COFFLinkGraphBuilder::setGraphSymbol</a>.</p>

</div>
</div>

### getRange() {#a90d9031100757aa7cb003f5376233554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">orc::ExecutorAddrRange llvm::jitlink::Symbol::getRange ()</td>
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

<p>Returns the address range of this symbol.</p>

<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>References <a href="#a9266b50b560808e8f69eb394690d79c4">getAddress</a> and <a href="#ab790ccf24d158f2933ef1c6cf153fb62">getSize</a>.</p>

</div>
</div>

### getScope() {#a51c33c919f5a66e0d0b9814b6b049363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Scope llvm::jitlink::Symbol::getScope ()</td>
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

<p>Get the visibility for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a>.</p>

<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlayer/#a99fe4a708e2a83ed2e9aaf8c3d909a1b">llvm::orc::LinkGraphLayer::getJITSymbolFlagsForSymbol</a>, <a href="#a37941163af977712e6ae68591327a0ad">getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a061c97aa3532f0b4a2390febaa911a65">llvm::jitlink::makeTargetOutOfRangeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a7aba1f4a32c3fabbf47d602a87052e46">llvm::jitlink::operator&lt;&lt;</a>.</p>

</div>
</div>

### getSection() {#a99c40db3f91fad3db60ba33e9fe93977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Section &amp; llvm::jitlink::Symbol::getSection ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> (<a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> must be defined).</p>

<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>References <a href="#aabff9b121d2ef09251a802eac2c2201b">getBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/block/#aa3ac38d81cc73281b480959aed712398">llvm::jitlink::Block::getSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#ac931ae3a09278d920ebb024da87edf2e">anonymous{PerfSupportPlugin.cpp}::getDebugInfoRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a07bfacd5c211410dc0226f08c7a5ebce">llvm::jitlink::LinkGraph::makeAbsolute</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a59c9ca37089df82fc40d87466f05dff6">llvm::jitlink::LinkGraph::makeExternal</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a18d3bcd5006cf1731a7b25315537f48c">llvm::jitlink::LinkGraph::removeDefinedSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#afd9b6af0144fc7780b698c357eac9f9e">llvm::jitlink::LinkGraph::transferDefinedSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/stubsmanager-prev7/#aa7eba3616569c9358af8634c9b93361c">llvm::jitlink::aarch32::StubsManager_prev7::visitEdge</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/stubsmanager-v7/#a70ad29c3ed54a2bf6137e081d60a179c">llvm::jitlink::aarch32::StubsManager_v7::visitEdge</a>.</p>

</div>
</div>

### getSize() {#ab790ccf24d158f2933ef1c6cf153fb62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">orc::ExecutorAddrDiff llvm::jitlink::Symbol::getSize ()</td>
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

<p>Returns the size of this symbol.</p>

<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a86c56f594b268ffb1f273fc4bc0f140b">llvm::orc::addFunctionPointerRelocationsToCurrentSymbol</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#ac0d41cae6559f87a6e26f2db6c30f24d">anonymous{PerfSupportPlugin.cpp}::getCodeLoadRecord</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#ac931ae3a09278d920ebb024da87edf2e">anonymous{PerfSupportPlugin.cpp}::getDebugInfoRecord</a>, <a href="#a90d9031100757aa7cb003f5376233554">getRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#aad348d4076f9c54b8c66cbd6fbda4453">llvm::jitlink::initRelaxAux</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a7aba1f4a32c3fabbf47d602a87052e46">llvm::jitlink::operator&lt;&lt;</a>, <a href="#ac64770573639fec35639f53fbf2d7874">setOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#afd9b6af0144fc7780b698c357eac9f9e">llvm::jitlink::LinkGraph::transferDefinedSymbol</a>.</p>

</div>
</div>

### getSymbolContent() {#a93b09ffda91456ad8838782c225842d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; char &gt; llvm::jitlink::Symbol::getSymbolContent ()</td>
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

<p>Returns the content in the underlying block covered by this symbol.</p>


<p>This method may only be called on defined non-zero-fill symbols.</p>


<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>References <a href="#aabff9b121d2ef09251a802eac2c2201b">getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block/#a4e670b08f3b3affac8a6916a2fc04b23">llvm::jitlink::Block::getContent</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>.</p>

</div>
</div>

### getTargetFlags() {#a2a3a9f494399398e41e672eeec440aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetFlagsType llvm::jitlink::Symbol::getTargetFlags ()</td>
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

<p>Get the target flags of this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a>.</p>

<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a6521de2d14ab48fafe3427e34a1e0405">llvm::jitlink::aarch32::hasTargetFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/stubsmanager-v7/#a70ad29c3ed54a2bf6137e081d60a179c">llvm::jitlink::aarch32::StubsManager_v7::visitEdge</a>.</p>

</div>
</div>

### hasName() {#af2cd363c45c4a9b5a8a2716d2effcd5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::Symbol::hasName ()</td>
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

<p>Returns true if this symbol has a name.</p>

<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Referenced by <a href="#a37941163af977712e6ae68591327a0ad">getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a7aba1f4a32c3fabbf47d602a87052e46">llvm::jitlink::operator&lt;&lt;</a> and <a href="#a1a0c8dc0edf87ed24a70d18ceee63c8d">setScope</a>.</p>

</div>
</div>

### isAbsolute() {#a5e5bb877f012989dc8e13fcc23af3e47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::Symbol::isAbsolute ()</td>
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

<p>Returns true if the underlying addressable is an absolute symbol.</p>

<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a07bfacd5c211410dc0226f08c7a5ebce">llvm::jitlink::LinkGraph::makeAbsolute</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#ab77236dd7d9ffb67698e20fedb91e64e">llvm::jitlink::LinkGraph::makeDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a59c9ca37089df82fc40d87466f05dff6">llvm::jitlink::LinkGraph::makeExternal</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a414fc8c567a84c2316b3ae237a19f562">llvm::jitlink::LinkGraph::removeAbsoluteSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a176bad8525301279eb900082ce8491af">llvm::jitlink::LinkGraph::removeExternalSymbol</a>.</p>

</div>
</div>

### isCallable() {#a15d4df0ad60a70e4074ccf11dfdc0164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::Symbol::isCallable ()</td>
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

<p>Returns true is this symbol is callable.</p>

<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlayer/#a99fe4a708e2a83ed2e9aaf8c3d909a1b">llvm::orc::LinkGraphLayer::getJITSymbolFlagsForSymbol</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-linkgraphlinkinglayer-cpp-/#ad7ab6c07e2f58775b2e014b2951243d7">anonymous{LinkGraphLinkingLayer.cpp}::getJITSymbolPtrForSymbol</a>.</p>

</div>
</div>

### isDefined() {#a43970b0f29022d28a252b08004fd1985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::Symbol::isDefined ()</td>
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

<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> has content (potentially) defined within this object file (i.e.</p>


<p>is anything but an external or absolute symbol).</p>


<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#aad348d4076f9c54b8c66cbd6fbda4453">llvm::jitlink::initRelaxAux</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a07bfacd5c211410dc0226f08c7a5ebce">llvm::jitlink::LinkGraph::makeAbsolute</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#ab77236dd7d9ffb67698e20fedb91e64e">llvm::jitlink::LinkGraph::makeDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a59c9ca37089df82fc40d87466f05dff6">llvm::jitlink::LinkGraph::makeExternal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a7aba1f4a32c3fabbf47d602a87052e46">llvm::jitlink::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/compactunwindmanager/#ab91679cd4a3a613219f1835a2d25c3f1">llvm::jitlink::CompactUnwindManager&lt; CURecTraits &gt;::prepareForPrune</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a414fc8c567a84c2316b3ae237a19f562">llvm::jitlink::LinkGraph::removeAbsoluteSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a18d3bcd5006cf1731a7b25315537f48c">llvm::jitlink::LinkGraph::removeDefinedSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a176bad8525301279eb900082ce8491af">llvm::jitlink::LinkGraph::removeExternalSymbol</a>.</p>

</div>
</div>

### isExternal() {#a0a31b65e4d98ba6601ffb8d7d3525932}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::Symbol::isExternal ()</td>
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

<p>Returns true if the underlying addressable is an unresolved external.</p>

<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#af217b3129ead780d884267c5ebda6cb2">isWeaklyReferenced</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a07bfacd5c211410dc0226f08c7a5ebce">llvm::jitlink::LinkGraph::makeAbsolute</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a59c9ca37089df82fc40d87466f05dff6">llvm::jitlink::LinkGraph::makeExternal</a> and <a href="#ae5a28a8b444f7fec3557f7f2b105ae4f">setWeaklyReferenced</a>.</p>

</div>
</div>

### isLive() {#a334cd7ae116c60e38dfae56cea71dc32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::Symbol::isLive ()</td>
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

<p>Returns true if this symbol is live (i.e.</p>


<p>should be treated as a root for dead stripping).</p>


<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a7aba1f4a32c3fabbf47d602a87052e46">llvm::jitlink::operator&lt;&lt;</a>.</p>

</div>
</div>

### isSymbolZeroFill() {#abc30302b2d19e010d8e5bfd6f2b8589c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::Symbol::isSymbolZeroFill ()</td>
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

<p>Returns true if this symbol is backed by a zero-fill block.</p>


<p>This method may only be called on defined symbols.</p>


<p>Definition at line 624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>References <a href="#aabff9b121d2ef09251a802eac2c2201b">getBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/block/#a6c9f7974883a2018cfa20b1b17c9ec98">llvm::jitlink::Block::isZeroFill</a>.</p>

</div>
</div>

### isWeaklyReferenced() {#af217b3129ead780d884267c5ebda6cb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::Symbol::isWeaklyReferenced ()</td>
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

<p>Returns true if this is a weakly referenced external symbol.</p>


<p>This method may only be called on external symbols.</p>


<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a0a31b65e4d98ba6601ffb8d7d3525932">isExternal</a>.</p>

</div>
</div>

### setCallable() {#af1931d466e6005db8c3b8bf4cf92701c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::Symbol::setCallable (bool IsCallable)</td>
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

<p>Set this symbol's callable bit.</p>

<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### setLinkage() {#aa68738aadf6d429383a1681a066ad5a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::Symbol::setLinkage (<a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55f">Linkage</a> L)</td>
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

<p>Set the linkage for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a>.</p>

<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55fac43e0fd449c758dab8f891d8e19eb1a9">llvm::jitlink::Strong</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#ab77236dd7d9ffb67698e20fedb91e64e">llvm::jitlink::LinkGraph::makeDefined</a>.</p>

</div>
</div>

### setLive() {#aa4b13283e98f0c3bc7bfca579fed4a54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::Symbol::setLive (bool IsLive)</td>
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

<p>Set this symbol's live bit.</p>

<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/cofflinkgraphbuilder/#aeab440ede1331d38fac1426b6fdb050e">llvm::jitlink::COFFLinkGraphBuilder::addImageBaseSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#ab77236dd7d9ffb67698e20fedb91e64e">llvm::jitlink::LinkGraph::makeDefined</a>.</p>

</div>
</div>

### setName() {#a25d7c78dbe32fcd69796fc678f1fe66e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::Symbol::setName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">orc::SymbolStringPtr</a> Name)</td>
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

<p>Rename this symbol.</p>


<p>The client is responsible for updating scope and linkage if this name-change requires it.</p>


<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### setOffset() {#ac64770573639fec35639f53fbf2d7874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::Symbol::setOffset (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a59b5f232ad8ec6bf405ddc77c3d6d752">orc::ExecutorAddrDiff</a> NewOffset)</td>
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



<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aabff9b121d2ef09251a802eac2c2201b">getBlock</a> and <a href="#ab790ccf24d158f2933ef1c6cf153fb62">getSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#ab77236dd7d9ffb67698e20fedb91e64e">llvm::jitlink::LinkGraph::makeDefined</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#afd9b6af0144fc7780b698c357eac9f9e">llvm::jitlink::LinkGraph::transferDefinedSymbol</a>.</p>

</div>
</div>

### setScope() {#a1a0c8dc0edf87ed24a70d18ceee63c8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::Symbol::setScope (<a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fd">Scope</a> S)</td>
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

<p>Set the visibility for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a>.</p>

<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af2cd363c45c4a9b5a8a2716d2effcd5a">hasName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fda509820290d57f333403f490dde7316f4">llvm::jitlink::Local</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a07bfacd5c211410dc0226f08c7a5ebce">llvm::jitlink::LinkGraph::makeAbsolute</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#ab77236dd7d9ffb67698e20fedb91e64e">llvm::jitlink::LinkGraph::makeDefined</a>.</p>

</div>
</div>

### setSize() {#ad4f650353789d23adbb0925d9a484ca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::Symbol::setSize (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a59b5f232ad8ec6bf405ddc77c3d6d752">orc::ExecutorAddrDiff</a> Size)</td>
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

<p>Set the size of this symbol.</p>

<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/block/#aa637382b37ac3809d3998c2ed8fb3118">llvm::jitlink::Block::getSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#ab77236dd7d9ffb67698e20fedb91e64e">llvm::jitlink::LinkGraph::makeDefined</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#afd9b6af0144fc7780b698c357eac9f9e">llvm::jitlink::LinkGraph::transferDefinedSymbol</a>.</p>

</div>
</div>

### setTargetFlags() {#a79317850235f8bbbb52f51e7f3dec9ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::Symbol::setTargetFlags (<a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abc9bc580a689ae42bea77b8de495a70c">TargetFlagsType</a> Flags)</td>
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

<p>Set the target flags for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a>.</p>

<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/stubsmanager-v7/#a70ad29c3ed54a2bf6137e081d60a179c">llvm::jitlink::aarch32::StubsManager_v7::visitEdge</a>.</p>

</div>
</div>

### setWeaklyReferenced() {#ae5a28a8b444f7fec3557f7f2b105ae4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::Symbol::setWeaklyReferenced (bool WeakRef)</td>
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

<p>Set the WeaklyReferenced value for this symbol.</p>


<p>This method may only be called on external symbols.</p>


<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a0a31b65e4d98ba6601ffb8d7d3525932">isExternal</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### makeAbsolute() {#aeff0882da0b48add7a623d5776195557}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::Symbol::makeAbsolute (<a href="/web-llvm/docs/api/classes/llvm/jitlink/addressable">Addressable</a> &amp; A)</td>
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



<p>Definition at line 688 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### makeExternal() {#a177da4875578829f7085b228a547d533}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::Symbol::makeExternal (<a href="/web-llvm/docs/api/classes/llvm/jitlink/addressable">Addressable</a> &amp; A)</td>
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



<p>Definition at line 678 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### setBlock() {#ac2eead45c4d5b412ddb11b0f9abf98e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::Symbol::setBlock (<a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B)</td>
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



<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Base {#a4ceb52e51ab426283142e1f01bcb14af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Addressable* llvm::jitlink::Symbol::Base = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### IsCallable {#a80ed2917322fea639e3bd95fba7a022f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::jitlink::Symbol::IsCallable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 705 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### IsLive {#a6e601c0fd3099059d8ee54f638ac27ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::jitlink::Symbol::IsLive</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 704 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### L {#a02cda0ac29136fb5125ae0ce6bd00d72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::jitlink::Symbol::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 702 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### Name {#a18df29f80afcdd80f42f1ec79a4fbcd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">orc::SymbolStringPtr llvm::jitlink::Symbol::Name = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### Offset {#a72b7616b0978df643f2fd9cabc3128f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::jitlink::Symbol::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 701 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### S {#adf1ea7335ab6833e7bd61371add0eb83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::jitlink::Symbol::S</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### Size {#a8c5736876ee9943ba0d1d2d81dbd2e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::jitlink::Symbol::Size = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### TargetFlags {#a87cf84d3dfa583ce6d6782b64feab1a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::jitlink::Symbol::TargetFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### WeakRef {#a76edc320bdec8660ea64f32623865497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::jitlink::Symbol::WeakRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 706 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### constructAbsolute() {#a96fcb8ce08a68aad21ad2da4e7c528a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::Symbol::constructAbsolute (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/classes/llvm/jitlink/addressable">Addressable</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">orc::SymbolStringPtr</a> &amp;&amp; Name, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a59b5f232ad8ec6bf405ddc77c3d6d752">orc::ExecutorAddrDiff</a> Size, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55f">Linkage</a> L, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fd">Scope</a> S, bool IsLive)</td>
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



<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### constructAnonDef() {#a071f781e5fbf8914454b394489e334ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::Symbol::constructAnonDef (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; Base, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a59b5f232ad8ec6bf405ddc77c3d6d752">orc::ExecutorAddrDiff</a> Offset, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a59b5f232ad8ec6bf405ddc77c3d6d752">orc::ExecutorAddrDiff</a> Size, bool IsCallable, bool IsLive)</td>
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



<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### constructExternal() {#aa1a55753370909590510de3aeabdd8f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::Symbol::constructExternal (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/classes/llvm/jitlink/addressable">Addressable</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">orc::SymbolStringPtr</a> &amp;&amp; Name, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a59b5f232ad8ec6bf405ddc77c3d6d752">orc::ExecutorAddrDiff</a> Size, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55f">Linkage</a> L, bool WeaklyReferenced)</td>
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



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### constructNamedDef() {#a3c1bbad999131def7acd1694a31955ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::Symbol::constructNamedDef (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; Base, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a59b5f232ad8ec6bf405ddc77c3d6d752">orc::ExecutorAddrDiff</a> Offset, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">orc::SymbolStringPtr</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a59b5f232ad8ec6bf405ddc77c3d6d752">orc::ExecutorAddrDiff</a> Size, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55f">Linkage</a> L, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fd">Scope</a> S, bool IsLive, bool IsCallable)</td>
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



<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### MaxOffset {#a24b126c3c80653ac4ef01abff2722fa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::jitlink::Symbol::MaxOffset = (1ULL &lt;&lt; 59) - 1</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
