---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/equivalenceclasses
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `EquivalenceClasses` Class Template Reference

<p><a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses">EquivalenceClasses</a> - This represents a collection of equivalence classes and supports three efficient operations: insert an element into a class of its own, union two classes, and find the class for a given element. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;
class llvm::EquivalenceClasses&lt;ElemTy, Compare&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">llvm/ADT/EquivalenceClasses.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0f6658f41713c51e16cb0eb989242c8f">iterator</a> = typename std::set&lt; ECValue, ECValueComparator &gt;::const_iterator</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>iterator* - Provides a way to iterate over all values in the set. <a href="#a0f6658f41713c51e16cb0eb989242c8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a9dc0b27026bcd7953eada1a9f3c6d1c8">EquivalenceClasses</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#abd87362689b356e445f304da38054053">EquivalenceClasses</a> (const EquivalenceClasses &amp;RHS)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses">EquivalenceClasses</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa32185c0533ff79a97c58515e3df87fe">operator=</a> (const EquivalenceClasses &amp;RHS)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a0f6658f41713c51e16cb0eb989242c8f">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16b4dce05aecd01ea12d90301d275dbf">begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a0f6658f41713c51e16cb0eb989242c8f">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7dff16816ce91085cecdc90e119356bc">end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad4c32f51bafcb62c48aac61d332b0d09">empty</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses/member-iterator">member_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9b2fb7a349a72d78d495c7a6af9150b2">member_begin</a> (iterator I) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses/member-iterator">member_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a355ac386262a099693abd5b51c60e137">member_end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a0f6658f41713c51e16cb0eb989242c8f">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a08a0899420552a8b2359ed963c77daa8">findValue</a> (const ElemTy &amp;V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findValue - Return an iterator to the specified value. <a href="#a08a0899420552a8b2359ed963c77daa8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ElemTy &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac0ff4be03ce0a4d0b5b60c713db9aef3">getLeaderValue</a> (const ElemTy &amp;V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getLeaderValue - Return the leader for the specified value that is in the set. <a href="#ac0ff4be03ce0a4d0b5b60c713db9aef3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ElemTy &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2c9e1f400adf2107158b1588ac10faa6">getOrInsertLeaderValue</a> (const ElemTy &amp;V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getOrInsertLeaderValue - Return the leader for the specified value that is in the set. <a href="#a2c9e1f400adf2107158b1588ac10faa6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a47b18572e436b87afaa132e4e46656e7">getNumClasses</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getNumClasses - Return the number of equivalence classes in this set. <a href="#a47b18572e436b87afaa132e4e46656e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a0f6658f41713c51e16cb0eb989242c8f">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3374117a1d6fa56b240853fb8da871b1">insert</a> (const ElemTy &amp;Data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>insert - Insert a new value into the union/find set, ignoring the request if the value already exists. <a href="#a3374117a1d6fa56b240853fb8da871b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses/member-iterator">member_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a108b85871dae49e6793d7aeeac969c5f">findLeader</a> (iterator I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findLeader - Given a value in the set, return a member iterator for the equivalence class it is in. <a href="#a108b85871dae49e6793d7aeeac969c5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses/member-iterator">member_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a851430356c44176578007977c550f91d">findLeader</a> (const ElemTy &amp;V) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses/member-iterator">member_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9f74b404e98ecd2608f87f7d561771e2">unionSets</a> (const ElemTy &amp;V1, const ElemTy &amp;V2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>union - Merge the two equivalence sets for the specified values, inserting them if they do not already exist in the equivalence set. <a href="#a9f74b404e98ecd2608f87f7d561771e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses/member-iterator">member_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abf907bded6ddfb5a9bc7431f159b0046">unionSets</a> (member_iterator L1, member_iterator L2)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeecd078bb48b46969da2dcb745b0b0f0">isEquivalent</a> (const ElemTy &amp;V1, const ElemTy &amp;V2) const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::set&lt; ECValue, ECValueComparator &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad4e3953e7a57e1be00672294e87d912f">TheMapping</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TheMapping - This implicitly provides a mapping from ElemTy values to the ECValues, it just keeps the key as part of the value. <a href="#ad4e3953e7a57e1be00672294e87d912f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses">EquivalenceClasses</a> - This represents a collection of equivalence classes and supports three efficient operations: insert an element into a class of its own, union two classes, and find the class for a given element.</p>


<p>In addition to these modification methods, it is possible to iterate over all of the equivalence classes and all of the elements in a class.</p>


<p>This implementation is an efficient implementation that only stores one copy of the element being indexed per entry in the set, and allows any arbitrary type to be indexed (as long as it can be ordered with operator&lt; or a comparator is provided).</p>


<p>Here is a simple example using integers:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9dc0b27026bcd7953eada1a9f3c6d1c8">EquivalenceClasses&lt;int&gt;</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">EC</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">EC</a>.unionSets(1, 2);                </span><span class="doxyHighlightComment">// insert 1, 2 into the same set</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">EC</a>.insert(4); <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">EC</a>.insert(5);        </span><span class="doxyHighlightComment">// insert 4, 5 into own sets</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">EC</a>.unionSets(5, 1);                </span><span class="doxyHighlightComment">// merge the set for 1 with 5's set.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (<a href="#a9dc0b27026bcd7953eada1a9f3c6d1c8">EquivalenceClasses&lt;int&gt;::iterator</a> <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> = <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">EC</a>.begin(), <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> = <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">EC</a>.end();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">     <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> != <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>; ++<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>) {           </span><span class="doxyHighlightComment">// Iterate over all of the equivalence sets.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>-&gt;isLeader()) </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;   </span><span class="doxyHighlightComment">// Ignore non-leader sets.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (<a href="#a9dc0b27026bcd7953eada1a9f3c6d1c8">EquivalenceClasses&lt;int&gt;::member_iterator</a> <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> = <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">EC</a>.member_begin(<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">       <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> != <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">EC</a>.member_end(); ++<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>)   </span><span class="doxyHighlightComment">// Loop over members in this set.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    cerr &lt;&lt; *<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;  </span><span class="doxyHighlightComment">// Print member.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  cerr &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;   </span><span class="doxyHighlightComment">// Finish set.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>This example prints: 4 5 1 2</p>


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#a0f6658f41713c51e16cb0eb989242c8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::iterator = 
      typename std::set&lt;ECValue, ECValueComparator&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>iterator* - Provides a way to iterate over all values in the set.</p>

<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### EquivalenceClasses() {#a9dc0b27026bcd7953eada1a9f3c6d1c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::EquivalenceClasses ()</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>

</div>
</div>

### EquivalenceClasses() {#abd87362689b356e445f304da38054053}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::EquivalenceClasses (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses">EquivalenceClasses</a> &amp; RHS)</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#aa32185c0533ff79a97c58515e3df87fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EquivalenceClasses &amp; llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses">EquivalenceClasses</a> &amp; RHS)</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>


<p>Referenced by <a href="#abd87362689b356e445f304da38054053">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::EquivalenceClasses</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a16b4dce05aecd01ea12d90301d275dbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::begin ()</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af7b6ae12af3578f7a20ccc11a4458f9f">llvm::computeMinimumValueSizes</a> and <a href="#a47b18572e436b87afaa132e4e46656e7">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::getNumClasses</a>.</p>

</div>
</div>

### empty() {#ad4c32f51bafcb62c48aac61d332b0d09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::empty ()</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>

</div>
</div>

### end() {#a7dff16816ce91085cecdc90e119356bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::end ()</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af7b6ae12af3578f7a20ccc11a4458f9f">llvm::computeMinimumValueSizes</a> and <a href="#a47b18572e436b87afaa132e4e46656e7">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::getNumClasses</a>.</p>

</div>
</div>

### findLeader() {#a108b85871dae49e6793d7aeeac969c5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">member_iterator llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::findLeader (<a href="#a0f6658f41713c51e16cb0eb989242c8f">iterator</a> I)</td>
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

<p>findLeader - Given a value in the set, return a member iterator for the equivalence class it is in.</p>


<p>This does the path-compression part that makes union-find "union findy". This returns an end iterator if the value is not in the equivalence class.</p>


<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>


<p>Referenced by <a href="#a851430356c44176578007977c550f91d">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::findLeader</a>, <a href="#ac0ff4be03ce0a4d0b5b60c713db9aef3">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::getLeaderValue</a>, <a href="#a2c9e1f400adf2107158b1588ac10faa6">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::getOrInsertLeaderValue</a>, <a href="#aeecd078bb48b46969da2dcb745b0b0f0">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::isEquivalent</a> and <a href="#a9f74b404e98ecd2608f87f7d561771e2">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::unionSets</a>.</p>

</div>
</div>

### findLeader() {#a851430356c44176578007977c550f91d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">member_iterator llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::findLeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ElemTy &amp; V)</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>

</div>
</div>

### findValue() {#a08a0899420552a8b2359ed963c77daa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::findValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ElemTy &amp; V)</td>
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

<p>findValue - Return an iterator to the specified value.</p>


<p>If it does not exist, <a href="#a7dff16816ce91085cecdc90e119356bc">end()</a> is returned.</p>


<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#a2e54d4cd15784b0f0480ca88bcf3165f">llvm::MemoryDepChecker::areDepsSafe</a>.</p>

</div>
</div>

### getLeaderValue() {#ac0ff4be03ce0a4d0b5b60c713db9aef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ElemTy &amp; llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::getLeaderValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ElemTy &amp; V)</td>
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

<p>getLeaderValue - Return the leader for the specified value that is in the set.</p>


<p>It is an error to call this method for a value that is not yet in the set. For that, call getOrInsertLeaderValue(V).</p>


<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#a2e54d4cd15784b0f0480ca88bcf3165f">llvm::MemoryDepChecker::areDepsSafe</a>.</p>

</div>
</div>

### getNumClasses() {#a47b18572e436b87afaa132e4e46656e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::getNumClasses ()</td>
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

<p>getNumClasses - Return the number of equivalence classes in this set.</p>


<p>Note that this is a linear time operation.</p>


<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>

</div>
</div>

### getOrInsertLeaderValue() {#a2c9e1f400adf2107158b1588ac10faa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ElemTy &amp; llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::getOrInsertLeaderValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ElemTy &amp; V)</td>
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

<p>getOrInsertLeaderValue - Return the leader for the specified value that is in the set.</p>


<p>If the member is not in the set, it is inserted, then returned.</p>


<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af7b6ae12af3578f7a20ccc11a4458f9f">llvm::computeMinimumValueSizes</a>.</p>

</div>
</div>

### insert() {#a3374117a1d6fa56b240853fb8da871b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ElemTy &amp; Data)</td>
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

<p>insert - Insert a new value into the union/find set, ignoring the request if the value already exists.</p>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>


<p>Referenced by <a href="#a2c9e1f400adf2107158b1588ac10faa6">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::getOrInsertLeaderValue</a>, <a href="#aa32185c0533ff79a97c58515e3df87fe">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::operator=</a> and <a href="#a9f74b404e98ecd2608f87f7d561771e2">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::unionSets</a>.</p>

</div>
</div>

### isEquivalent() {#aeecd078bb48b46969da2dcb745b0b0f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::isEquivalent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ElemTy &amp; V1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ElemTy &amp; V2)</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a342ca2d063631fda10c6c47cbdc397f3">CompareSCEVComplexity</a>.</p>

</div>
</div>

### member\_begin() {#a9b2fb7a349a72d78d495c7a6af9150b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">member_iterator llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::member_begin (<a href="#a0f6658f41713c51e16cb0eb989242c8f">iterator</a> I)</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#a2e54d4cd15784b0f0480ca88bcf3165f">llvm::MemoryDepChecker::areDepsSafe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7b6ae12af3578f7a20ccc11a4458f9f">llvm::computeMinimumValueSizes</a> and <a href="#aa32185c0533ff79a97c58515e3df87fe">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::operator=</a>.</p>

</div>
</div>

### member\_end() {#a355ac386262a099693abd5b51c60e137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">member_iterator llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::member_end ()</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#a2e54d4cd15784b0f0480ca88bcf3165f">llvm::MemoryDepChecker::areDepsSafe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7b6ae12af3578f7a20ccc11a4458f9f">llvm::computeMinimumValueSizes</a>, <a href="#a108b85871dae49e6793d7aeeac969c5f">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::findLeader</a>, <a href="#ac0ff4be03ce0a4d0b5b60c713db9aef3">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::getLeaderValue</a>, <a href="#a2c9e1f400adf2107158b1588ac10faa6">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::getOrInsertLeaderValue</a>, <a href="#aeecd078bb48b46969da2dcb745b0b0f0">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::isEquivalent</a>, <a href="#aa32185c0533ff79a97c58515e3df87fe">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::operator=</a> and <a href="#abf907bded6ddfb5a9bc7431f159b0046">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::unionSets</a>.</p>

</div>
</div>

### unionSets() {#a9f74b404e98ecd2608f87f7d561771e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">member_iterator llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::unionSets (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ElemTy &amp; V1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ElemTy &amp; V2)</td>
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

<p>union - Merge the two equivalence sets for the specified values, inserting them if they do not already exist in the equivalence set.</p>

<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a342ca2d063631fda10c6c47cbdc397f3">CompareSCEVComplexity</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7b6ae12af3578f7a20ccc11a4458f9f">llvm::computeMinimumValueSizes</a>, <a href="#aa32185c0533ff79a97c58515e3df87fe">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::operator=</a> and <a href="#a9f74b404e98ecd2608f87f7d561771e2">llvm::EquivalenceClasses&lt; BasicBlock * &gt;::unionSets</a>.</p>

</div>
</div>

### unionSets() {#abf907bded6ddfb5a9bc7431f159b0046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">member_iterator llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::unionSets (<a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses/member-iterator">member_iterator</a> L1, <a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses/member-iterator">member_iterator</a> L2)</td>
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



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### TheMapping {#ad4e3953e7a57e1be00672294e87d912f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ElemTy, class Compare = std::less&lt;ElemTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;ECValue, ECValueComparator&gt; llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::TheMapping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>TheMapping - This implicitly provides a mapping from ElemTy values to the ECValues, it just keeps the key as part of the value.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/equivalenceclasses-h">EquivalenceClasses.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
