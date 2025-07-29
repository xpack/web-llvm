---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-itaniumdemangle-cpp-/dumpvisitor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DumpVisitor` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{ItaniumDemangle.cpp}::DumpVisitor { ... }
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8aecf1e1b41604c04d6559f6f9def83d">operator()</a> (const NodeT *Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2bf9104c6037ff8ef12cf560e845a4f">operator()</a> (const ForwardTemplateReference *Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb5ca37e4e26e1b317c584ce32ea8a4a">printStr</a> (const char *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85d4ab57f49038be69f5929b7d5aa13f">print</a> (std::string_view SV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82c5934505b75b1d9c6c4f123898d47a">print</a> (const Node *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad493cd30055fca3c8953054af0bbac6c">print</a> (NodeArray A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b19772d566a227d7ee3412e6878e6c3">print</a> (bool B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a71e5603c77c723604579181fe73a2071">print</a> (T N) -&gt; std::enable_if_t&lt; std::is_unsigned&lt; T &gt;::value &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a72c6b8210aedd61c26061553f986efad">print</a> (T N) -&gt; std::enable_if_t&lt; std::is_signed&lt; T &gt;::value &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6f47cbf23cf79359de8f9947bea7c0a">print</a> (ReferenceKind RK)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab31d33de475da7e5d8be9c1e9892c83">print</a> (FunctionRefQual RQ)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb68459feaef20fb703f83971fbad74c">print</a> (Qualifiers Qs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cba228c4947aea0c4a81fbed5b10265">print</a> (SpecialSubKind SSK)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ec9d1fe52dce6cf6aa301208b74469a">print</a> (TemplateParamKind TPK)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca05f09059ec0a63b4b90d25a041169b">print</a> (Node::Prec P)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba7119d112800473620a7a272e0d7601">newLine</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adb58919e1518cf971d39119d95ce6ea6">printWithPendingNewline</a> (T V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5b674f3db7ad09bf91972556ab8fec9a">printWithComma</a> (T V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbbe78c88213ee05e9d19f269f9564e3">Depth</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af61d12d26f7e264567c49302e815a46e">PendingNewline</a> = false</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a49029f66b28963d785ce43127d03c96f">wantsNewline</a> (const NodeT *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8176dda374a1cc5080e2122d30a44b02">wantsNewline</a> (NodeArray A)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07cc1c634ad5a82d961e2c0942226408">wantsNewline</a> (...)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ... Ts&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad773e440ab05129881d403e88492fcaf">anyWantNewline</a> (Ts ...Vs)</td>
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


<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator()() {#a8aecf1e1b41604c04d6559f6f9def83d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumDemangle.cpp}::DumpVisitor::operator() (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeT * Node)</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>Reference <a href="#adbbe78c88213ee05e9d19f269f9564e3">Depth</a>.</p>

</div>
</div>

### operator()() {#ad2bf9104c6037ff8ef12cf560e845a4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumDemangle.cpp}::DumpVisitor::operator() (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/forwardtemplatereference">ForwardTemplateReference</a> * Node)</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>Reference <a href="#adbbe78c88213ee05e9d19f269f9564e3">Depth</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### newLine() {#aba7119d112800473620a7a272e0d7601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumDemangle.cpp}::DumpVisitor::newLine ()</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="#adbbe78c88213ee05e9d19f269f9564e3">Depth</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af61d12d26f7e264567c49302e815a46e">PendingNewline</a> and <a href="#aeb5ca37e4e26e1b317c584ce32ea8a4a">printStr</a>.</p>


<p>Referenced by <a href="#a5b674f3db7ad09bf91972556ab8fec9a">printWithComma</a>.</p>

</div>
</div>

### print() {#a85d4ab57f49038be69f5929b7d5aa13f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumDemangle.cpp}::DumpVisitor::print (std::string_view SV)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>

</div>
</div>

### print() {#a82c5934505b75b1d9c6c4f123898d47a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumDemangle.cpp}::DumpVisitor::print (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/node">Node</a> * N)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#aeb5ca37e4e26e1b317c584ce32ea8a4a">printStr</a>.</p>

</div>
</div>

### print() {#ad493cd30055fca3c8953054af0bbac6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumDemangle.cpp}::DumpVisitor::print (<a href="/web-llvm/docs/api/classes/nodearray">NodeArray</a> A)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#adbbe78c88213ee05e9d19f269f9564e3">Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>, <a href="#aeb5ca37e4e26e1b317c584ce32ea8a4a">printStr</a> and <a href="#a5b674f3db7ad09bf91972556ab8fec9a">printWithComma</a>.</p>

</div>
</div>

### print() {#a4b19772d566a227d7ee3412e6878e6c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumDemangle.cpp}::DumpVisitor::print (bool B)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#aeb5ca37e4e26e1b317c584ce32ea8a4a">printStr</a>.</p>

</div>
</div>

### print() {#a71e5603c77c723604579181fe73a2071}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; std::is_unsigned&lt; T &gt;::value &gt; anonymous{ItaniumDemangle.cpp}::DumpVisitor::print (T N)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### print() {#a72c6b8210aedd61c26061553f986efad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; std::is_signed&lt; T &gt;::value &gt; anonymous{ItaniumDemangle.cpp}::DumpVisitor::print (T N)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### print() {#ab6f47cbf23cf79359de8f9947bea7c0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumDemangle.cpp}::DumpVisitor::print (<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ab67ef02b75c3226cfe0b2791e2b48b06">ReferenceKind</a> RK)</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ab67ef02b75c3226cfe0b2791e2b48b06a74accfde3d3f8e8a27c326eba229d16c">LValue</a>, <a href="#aeb5ca37e4e26e1b317c584ce32ea8a4a">printStr</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ab67ef02b75c3226cfe0b2791e2b48b06ac756c8b5e0e5217b000321397a40be7e">RValue</a>.</p>

</div>
</div>

### print() {#aab31d33de475da7e5d8be9c1e9892c83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumDemangle.cpp}::DumpVisitor::print (<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a9fef0832b445332ae7862de6f08ac8ed">FunctionRefQual</a> RQ)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a9fef0832b445332ae7862de6f08ac8eda1aae950c29f9ecb1c243fd467c11e459">FrefQualLValue</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a9fef0832b445332ae7862de6f08ac8eda74a742e365bc15a3ee3b9a2a4b0e79f3">FrefQualNone</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a9fef0832b445332ae7862de6f08ac8edafbc3331ba3ee5c71530408d486058abe">FrefQualRValue</a> and <a href="#aeb5ca37e4e26e1b317c584ce32ea8a4a">printStr</a>.</p>

</div>
</div>

### print() {#aeb68459feaef20fb703f83971fbad74c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumDemangle.cpp}::DumpVisitor::print (<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7">Qualifiers</a> Qs)</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="#aeb5ca37e4e26e1b317c584ce32ea8a4a">printStr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7ad6035faf42d8a83f52624853a1ade2ea">QualConst</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7a6b9478659a0508affa81b92965259e51">QualRestrict</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7a2dada893b2fc28c908763cf4599e5a07">QualVolatile</a>.</p>

</div>
</div>

### print() {#a2cba228c4947aea0c4a81fbed5b10265}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumDemangle.cpp}::DumpVisitor::print (<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54ed">SpecialSubKind</a> SSK)</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54eda3ea9a0394aab44aadd148cfafa5c6693">allocator</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54eda7a4f49a6af0ccc6be090f967fde97f4e">basic_string</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54eda79abd8cf35895c560cc4d955c5355dbe">iostream</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab2d5d0d1cb71d3cef4032b3cad9fcb77">istream</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54eda28ddb00d829f83a7197c5c48a97a9e0d">ostream</a>, <a href="#aeb5ca37e4e26e1b317c584ce32ea8a4a">printStr</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">string</a>.</p>

</div>
</div>

### print() {#a7ec9d1fe52dce6cf6aa301208b74469a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumDemangle.cpp}::DumpVisitor::print (<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a88ee8e4eea43084bd8964682683da88c">TemplateParamKind</a> TPK)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a88ee8e4eea43084bd8964682683da88ca8627a9054b6f456c6e15d7a0d57a9030">NonType</a>, <a href="#aeb5ca37e4e26e1b317c584ce32ea8a4a">printStr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a88ee8e4eea43084bd8964682683da88ca278c491bdd8a53618c149c4ac790da34">Template</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a88ee8e4eea43084bd8964682683da88caa1fa27779242b4902f7ae3bdd5c6d508">Type</a>.</p>

</div>
</div>

### print() {#aca05f09059ec0a63b4b90d25a041169b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumDemangle.cpp}::DumpVisitor::print (<a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220b">Node::Prec</a> P)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220ba3f7b3d8ee7bf0d542bd50821c083888f">Node::Additive</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220bac33315685a0cba3ce53be378b3c7874b">Node::And</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220ba7e701bf20fc279f4e724fb546bff87ef">Node::AndIf</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220ba185b7133db22230701a857c059360cc2">Node::Assign</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220ba4cd9f3996d60790cd11c04f842ebc43c">Node::Cast</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220ba58be47db9455679e6a44df2eff9c9fa6">Node::Comma</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220ba9d3afea73e90192d96dda8d38c87a4fe">Node::Conditional</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220ba7a1920d61156abc05a60135aefe8bc67">Node::Default</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220ba890ebf2ce6beb154deb673b3af2d03d4">Node::Equality</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220ba7e7f41b0027e4c9ccc5c0bc8311460e6">Node::Ior</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220ba0d73bf5decac382ed6a8adc3838fd7e2">Node::Multiplicative</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220ba537c997386c93ba3fcebf9d62497ade4">Node::OrIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220bae5cc2a8a065c6272466ee0277ccc417f">Node::Postfix</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220ba074de7e7c226d5c60f8af14c20725352">Node::Primary</a>, <a href="#aeb5ca37e4e26e1b317c584ce32ea8a4a">printStr</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220bad2319c7d84b12595350ebf789d8c40ea">Node::PtrMem</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220ba14ecfbc5403b00fa4432000ad75d6e92">Node::Relational</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220ba825a3d98017bab11815ad2817201324c">Node::Shift</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220ba6451b7e603bba95e2da31f1dacd7754d">Node::Spaceship</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220ba19c6e8d6e2caeaff0ac8881e05c25010">Node::Unary</a> and <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220ba76feb79109026728a20736a8c6504548">Node::Xor</a>.</p>

</div>
</div>

### printStr() {#aeb5ca37e4e26e1b317c584ce32ea8a4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumDemangle.cpp}::DumpVisitor::printStr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * S)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>Referenced by <a href="#aba7119d112800473620a7a272e0d7601">newLine</a>, <a href="#a4b19772d566a227d7ee3412e6878e6c3">print</a>, <a href="#a82c5934505b75b1d9c6c4f123898d47a">print</a>, <a href="#aab31d33de475da7e5d8be9c1e9892c83">print</a>, <a href="#aca05f09059ec0a63b4b90d25a041169b">print</a>, <a href="#ad493cd30055fca3c8953054af0bbac6c">print</a>, <a href="#aeb68459feaef20fb703f83971fbad74c">print</a>, <a href="#ab6f47cbf23cf79359de8f9947bea7c0a">print</a>, <a href="#a2cba228c4947aea0c4a81fbed5b10265">print</a>, <a href="#a7ec9d1fe52dce6cf6aa301208b74469a">print</a> and <a href="#a5b674f3db7ad09bf91972556ab8fec9a">printWithComma</a>.</p>

</div>
</div>

### printWithComma() {#a5b674f3db7ad09bf91972556ab8fec9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumDemangle.cpp}::DumpVisitor::printWithComma (T V)</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="#aba7119d112800473620a7a272e0d7601">newLine</a>, <a href="#af61d12d26f7e264567c49302e815a46e">PendingNewline</a>, <a href="#aeb5ca37e4e26e1b317c584ce32ea8a4a">printStr</a>, <a href="#adb58919e1518cf971d39119d95ce6ea6">printWithPendingNewline</a> and <a href="#a49029f66b28963d785ce43127d03c96f">wantsNewline</a>.</p>


<p>Referenced by <a href="#ad493cd30055fca3c8953054af0bbac6c">print</a>.</p>

</div>
</div>

### printWithPendingNewline() {#adb58919e1518cf971d39119d95ce6ea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumDemangle.cpp}::DumpVisitor::printWithPendingNewline (T V)</td>
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



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="#af61d12d26f7e264567c49302e815a46e">PendingNewline</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a> and <a href="#a49029f66b28963d785ce43127d03c96f">wantsNewline</a>.</p>


<p>Referenced by <a href="#a5b674f3db7ad09bf91972556ab8fec9a">printWithComma</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Depth {#adbbe78c88213ee05e9d19f269f9564e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ItaniumDemangle.cpp}::DumpVisitor::Depth = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>Referenced by <a href="#aba7119d112800473620a7a272e0d7601">newLine</a>, <a href="#ad2bf9104c6037ff8ef12cf560e845a4f">operator()</a>, <a href="#a8aecf1e1b41604c04d6559f6f9def83d">operator()</a> and <a href="#ad493cd30055fca3c8953054af0bbac6c">print</a>.</p>

</div>
</div>

### PendingNewline {#af61d12d26f7e264567c49302e815a46e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ItaniumDemangle.cpp}::DumpVisitor::PendingNewline = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>Referenced by <a href="#aba7119d112800473620a7a272e0d7601">newLine</a>, <a href="#a5b674f3db7ad09bf91972556ab8fec9a">printWithComma</a> and <a href="#adb58919e1518cf971d39119d95ce6ea6">printWithPendingNewline</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### anyWantNewline() {#ad773e440ab05129881d403e88492fcaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ... Ts&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ItaniumDemangle.cpp}::DumpVisitor::anyWantNewline (Ts ... Vs)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#a49029f66b28963d785ce43127d03c96f">wantsNewline</a>.</p>

</div>
</div>

### wantsNewline() {#a49029f66b28963d785ce43127d03c96f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr bool anonymous{ItaniumDemangle.cpp}::DumpVisitor::wantsNewline (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeT *)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>Referenced by <a href="#ad773e440ab05129881d403e88492fcaf">anyWantNewline</a>, <a href="#a5b674f3db7ad09bf91972556ab8fec9a">printWithComma</a> and <a href="#adb58919e1518cf971d39119d95ce6ea6">printWithPendingNewline</a>.</p>

</div>
</div>

### wantsNewline() {#a8176dda374a1cc5080e2122d30a44b02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ItaniumDemangle.cpp}::DumpVisitor::wantsNewline (<a href="/web-llvm/docs/api/classes/nodearray">NodeArray</a> A)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>

</div>
</div>

### wantsNewline() {#a07cc1c634ad5a82d961e2c0942226408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr bool anonymous{ItaniumDemangle.cpp}::DumpVisitor::wantsNewline (...)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
