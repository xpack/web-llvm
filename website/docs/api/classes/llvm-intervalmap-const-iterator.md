---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/intervalmap/const-iterator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `const_iterator` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::IntervalMap::const_iterator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">llvm/ADT/IntervalMap.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a880b0421e35e2cd54a1c81a6d6b2a519">iterator_category</a> = std::bidirectional_iterator_tag</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2af4b7566086ebfcd645d48f24222ab5">value_type</a> = ValT</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7ad83147b66da85d17e7dd49908a7b7">difference_type</a> = std::ptrdiff_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbd95d92725b5e6692e175849ea2c5dc">pointer</a> = <a href="#a2af4b7566086ebfcd645d48f24222ab5">value_type</a> *</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af08c4b19a0bf3dff0c0428e504fb330e">reference</a> = <a href="#a2af4b7566086ebfcd645d48f24222ab5">value_type</a> &amp;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae974639f12394e77cf9c059c6b064499">IntervalMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2798e2ab3b9024314e3699990a26f2a9">const_iterator</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/intervalmap/const-iterator">const_iterator</a> - Create an iterator that isn't pointing anywhere. <a href="#a2798e2ab3b9024314e3699990a26f2a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19785dafd2ac873fe41085bf3125e0f9">const_iterator</a> (const IntervalMap &amp;map)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ValT &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a840f7c85b9dfb849db4758270cc41523">operator*</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b8e82aa59078f5275fc515e1a6ed7c4">operator==</a> (const const_iterator &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4086e1b263b9635b84318392337c5193">operator!=</a> (const const_iterator &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap/const-iterator">const_iterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b8573afd2c65e3391bfdd92e5c42d8d">operator++</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>preincrement - Move to the next interval. <a href="#a4b8573afd2c65e3391bfdd92e5c42d8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap/const-iterator">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebe4ede02d1a719cd9bffee7c29c4ddf">operator++</a> (int)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>postincrement - Don't do that! <a href="#aebe4ede02d1a719cd9bffee7c29c4ddf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap/const-iterator">const_iterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace4989cb01faf6a4cde20e40d7df8c0c">operator--</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>predecrement - Move to the previous interval. <a href="#ace4989cb01faf6a4cde20e40d7df8c0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap/const-iterator">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a904adab37bae4b17fc62f87dc7631c5d">operator--</a> (int)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>postdecrement - Don't do that! <a href="#a904adab37bae4b17fc62f87dc7631c5d">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16b2c8e378000a0894391bc4f741369a">setMap</a> (const IntervalMap &amp;m)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setMap - Change the map iterated over. <a href="#a16b2c8e378000a0894391bc4f741369a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a548db093f880ebc0c1706229e898c2f2">valid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>valid - Return true if the current position is valid, false for <a href="/web-llvm/docs/api/classes/llvm/intervalmap/#a9f207a7ea5e716ddd6e894086b593941">end()</a>. <a href="#a548db093f880ebc0c1706229e898c2f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0e25ec43a32750831019356a025f75d">atBegin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>atBegin - Return true if the current position is the first map entry. <a href="#ab0e25ec43a32750831019356a025f75d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f262ebbf77347c4999ae7455a59dd99">start</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>start - Return the beginning of the current interval. <a href="#a6f262ebbf77347c4999ae7455a59dd99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a437e7639824aff20c0def7dc276db2f7">stop</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>stop - Return the end of the current interval. <a href="#a437e7639824aff20c0def7dc276db2f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ValT &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88ec9c35789c76004d1f7dcf690db2b4">value</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>value - Return the mapped value at the current interval. <a href="#a88ec9c35789c76004d1f7dcf690db2b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaec49caab60813b87e4efb180ce1675">goToBegin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>goToBegin - Move to the first interval in map. <a href="#adaec49caab60813b87e4efb180ce1675">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42aaf8d56d380b52f087ba238ce10c52">goToEnd</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>goToEnd - Move beyond the last interval in map. <a href="#a42aaf8d56d380b52f087ba238ce10c52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab827f91e03f3338b2b943a00f0bee07d">find</a> (KeyT x)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>find - Move to the first interval with stop &gt;= x, or <a href="/web-llvm/docs/api/classes/llvm/intervalmap/#a9f207a7ea5e716ddd6e894086b593941">end()</a>. <a href="#ab827f91e03f3338b2b943a00f0bee07d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27e1981325e2267e65652eaddb2cb236">advanceTo</a> (KeyT x)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>advanceTo - Move to the first interval with stop &gt;= x, or <a href="/web-llvm/docs/api/classes/llvm/intervalmap/#a9f207a7ea5e716ddd6e894086b593941">end()</a>. <a href="#a27e1981325e2267e65652eaddb2cb236">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adddc6e7d112bd7d8e211c46e3d0d2e7b">branched</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa02ccfd91f0ae5d754f370be26e3191e">setRoot</a> (unsigned Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3187b02e986777ccb9953b73ac6fda6b">pathFillFind</a> (KeyT x)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>pathFillFind - Complete path by searching for x. <a href="#a3187b02e986777ccb9953b73ac6fda6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafa139bd49fa2f2b3df1e7a223e1bc2e">treeFind</a> (KeyT x)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>treeFind - Find in a branched tree. <a href="#aafa139bd49fa2f2b3df1e7a223e1bc2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7136191f76b76ad1bef786f47f2c9846">treeAdvanceTo</a> (KeyT x)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>treeAdvanceTo - Find position after the current one. <a href="#a7136191f76b76ad1bef786f47f2c9846">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">KeyT &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad77530a792ede3ca10c8e07d61122afc">unsafeStart</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>unsafeStart - Writable access to <a href="#a6f262ebbf77347c4999ae7455a59dd99">start()</a> for iterator. <a href="#ad77530a792ede3ca10c8e07d61122afc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">KeyT &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a468d104ec5d2a57389590ae1d04f94cf">unsafeStop</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>unsafeStop - Writable access to <a href="#a437e7639824aff20c0def7dc276db2f7">stop()</a> for iterator. <a href="#a468d104ec5d2a57389590ae1d04f94cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">ValT &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82942d6073064b572e72b0f6ed853934">unsafeValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>unsafeValue - Writable access to <a href="#a88ec9c35789c76004d1f7dcf690db2b4">value()</a> for iterator. <a href="#a82942d6073064b572e72b0f6ed853934">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24c3474afac43c88fc6a212441971a90">map</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/path">IntervalMapImpl::Path</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9698a846e49b6c946d5fbe616dc9e2ea">path</a></td>
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


<p>Definition at line 1343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### difference\_type {#ab7ad83147b66da85d17e7dd49908a7b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::difference_type =  std::ptrdiff_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### iterator\_category {#a880b0421e35e2cd54a1c81a6d6b2a519}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::iterator_category =  std::bidirectional_iterator_tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### pointer {#abbd95d92725b5e6692e175849ea2c5dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::pointer =  value_type *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### reference {#af08c4b19a0bf3dff0c0428e504fb330e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::reference =  value_type &amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### value\_type {#a2af4b7566086ebfcd645d48f24222ab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::value_type =  ValT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### IntervalMap {#ae974639f12394e77cf9c059c6b064499}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="#ae974639f12394e77cf9c059c6b064499">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::IntervalMap</a>.</p>


<p>Referenced by <a href="#a19785dafd2ac873fe41085bf3125e0f9">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::const_iterator</a>, <a href="#ae974639f12394e77cf9c059c6b064499">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::IntervalMap</a> and <a href="#a16b2c8e378000a0894391bc4f741369a">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::setMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### const\_iterator() {#a2798e2ab3b9024314e3699990a26f2a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::const_iterator ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/intervalmap/const-iterator">const_iterator</a> - Create an iterator that isn't pointing anywhere.</p>

<p>Definition at line 1403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### const\_iterator() {#a19785dafd2ac873fe41085bf3125e0f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::const_iterator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a> &amp; map)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#ae974639f12394e77cf9c059c6b064499">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::IntervalMap</a> and <a href="#a24c3474afac43c88fc6a212441971a90">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::map</a>.</p>


<p>Referenced by <a href="#a4086e1b263b9635b84318392337c5193">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator!=</a>, <a href="#a4b8573afd2c65e3391bfdd92e5c42d8d">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator++</a>, <a href="#aebe4ede02d1a719cd9bffee7c29c4ddf">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator++</a>, <a href="#ace4989cb01faf6a4cde20e40d7df8c0c">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator--</a>, <a href="#a904adab37bae4b17fc62f87dc7631c5d">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator--</a> and <a href="#a3b8e82aa59078f5275fc515e1a6ed7c4">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator--() {#ace4989cb01faf6a4cde20e40d7df8c0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator-- ()</td>
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

<p>predecrement - Move to the previous interval.</p>

<p>Definition at line 1467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#adddc6e7d112bd7d8e211c46e3d0d2e7b">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::branched</a>, <a href="#a19785dafd2ac873fe41085bf3125e0f9">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::const_iterator</a>, <a href="#a24c3474afac43c88fc6a212441971a90">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::map</a>, <a href="#a9698a846e49b6c946d5fbe616dc9e2ea">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::path</a> and <a href="#a548db093f880ebc0c1706229e898c2f2">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::valid</a>.</p>


<p>Referenced by <a href="#a904adab37bae4b17fc62f87dc7631c5d">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator--</a> and <a href="/web-llvm/docs/api/classes/llvm/intervalmap/iterator/#afd69cead0145a5c1e5696124b8caa16b">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::operator--</a>.</p>

</div>
</div>

### operator--() {#a904adab37bae4b17fc62f87dc7631c5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator-- (int)</td>
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

<p>postdecrement - Don't do that!</p>

<p>Definition at line 1476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#a19785dafd2ac873fe41085bf3125e0f9">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::const_iterator</a> and <a href="#ace4989cb01faf6a4cde20e40d7df8c0c">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator--</a>.</p>

</div>
</div>

### operator!=() {#a4086e1b263b9635b84318392337c5193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intervalmap/const-iterator">const_iterator</a> &amp; RHS)</td>
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



<p>Definition at line 1435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#a19785dafd2ac873fe41085bf3125e0f9">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::const_iterator</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/mergedfunctionsinfo-cpp/#ad5db311411b09e79fcad62e7cee12e6b">operator==</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\*() {#a840f7c85b9dfb849db4758270cc41523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ValT &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator* ()</td>
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



<p>Definition at line 1424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="#a88ec9c35789c76004d1f7dcf690db2b4">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::value</a>.</p>

</div>
</div>

### operator++() {#a4b8573afd2c65e3391bfdd92e5c42d8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator++ ()</td>
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

<p>preincrement - Move to the next interval.</p>

<p>Definition at line 1452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#adddc6e7d112bd7d8e211c46e3d0d2e7b">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::branched</a>, <a href="#a19785dafd2ac873fe41085bf3125e0f9">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::const_iterator</a>, <a href="#a24c3474afac43c88fc6a212441971a90">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::map</a>, <a href="#a9698a846e49b6c946d5fbe616dc9e2ea">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::path</a> and <a href="#a548db093f880ebc0c1706229e898c2f2">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::valid</a>.</p>


<p>Referenced by <a href="#aebe4ede02d1a719cd9bffee7c29c4ddf">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator++</a> and <a href="/web-llvm/docs/api/classes/llvm/intervalmap/iterator/#a7d39e7b0ab77b166377686adae5ea4fe">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::operator++</a>.</p>

</div>
</div>

### operator++() {#aebe4ede02d1a719cd9bffee7c29c4ddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator++ (int)</td>
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

<p>postincrement - Don't do that!</p>

<p>Definition at line 1460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#a19785dafd2ac873fe41085bf3125e0f9">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::const_iterator</a> and <a href="#a4b8573afd2c65e3391bfdd92e5c42d8d">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator++</a>.</p>

</div>
</div>

### operator==() {#a3b8e82aa59078f5275fc515e1a6ed7c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intervalmap/const-iterator">const_iterator</a> &amp; RHS)</td>
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



<p>Definition at line 1426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a19785dafd2ac873fe41085bf3125e0f9">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::const_iterator</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmap/#ad2ca2ac99610417e4b68debafe2185d2">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::leaf</a>, <a href="#a24c3474afac43c88fc6a212441971a90">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::map</a>, <a href="#a9698a846e49b6c946d5fbe616dc9e2ea">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::path</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a548db093f880ebc0c1706229e898c2f2">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::valid</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### advanceTo() {#a27e1981325e2267e65652eaddb2cb236}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::advanceTo (KeyT x)</td>
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

<p>advanceTo - Move to the first interval with stop &gt;= x, or <a href="/web-llvm/docs/api/classes/llvm/intervalmap/#a9f207a7ea5e716ddd6e894086b593941">end()</a>.</p>


<p>The search is started from the current position, and no earlier positions can be found. This is much faster than <a href="#ab827f91e03f3338b2b943a00f0bee07d">find()</a> for small moves.</p>


<p>Definition at line 1494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#adddc6e7d112bd7d8e211c46e3d0d2e7b">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::branched</a>, <a href="#a24c3474afac43c88fc6a212441971a90">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::map</a>, <a href="#a9698a846e49b6c946d5fbe616dc9e2ea">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::path</a>, <a href="#a7136191f76b76ad1bef786f47f2c9846">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::treeAdvanceTo</a> and <a href="#a548db093f880ebc0c1706229e898c2f2">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::valid</a>.</p>

</div>
</div>

### atBegin() {#ab0e25ec43a32750831019356a025f75d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::atBegin ()</td>
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

<p>atBegin - Return true if the current position is the first map entry.</p>

<p>Definition at line 1413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="#a9698a846e49b6c946d5fbe616dc9e2ea">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::path</a>.</p>

</div>
</div>

### find() {#ab827f91e03f3338b2b943a00f0bee07d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::find (KeyT x)</td>
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

<p>find - Move to the first interval with stop &gt;= x, or <a href="/web-llvm/docs/api/classes/llvm/intervalmap/#a9f207a7ea5e716ddd6e894086b593941">end()</a>.</p>


<p>This is a full search from the root, the current position is ignored.</p>


<p>Definition at line 1484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#adddc6e7d112bd7d8e211c46e3d0d2e7b">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::branched</a>, <a href="#a24c3474afac43c88fc6a212441971a90">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::map</a>, <a href="#aa02ccfd91f0ae5d754f370be26e3191e">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::setRoot</a> and <a href="#aafa139bd49fa2f2b3df1e7a223e1bc2e">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::treeFind</a>.</p>

</div>
</div>

### goToBegin() {#adaec49caab60813b87e4efb180ce1675}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::goToBegin ()</td>
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

<p>goToBegin - Move to the first interval in map.</p>

<p>Definition at line 1440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#adddc6e7d112bd7d8e211c46e3d0d2e7b">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::branched</a>, <a href="#a24c3474afac43c88fc6a212441971a90">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::map</a>, <a href="#a9698a846e49b6c946d5fbe616dc9e2ea">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::path</a> and <a href="#aa02ccfd91f0ae5d754f370be26e3191e">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::setRoot</a>.</p>

</div>
</div>

### goToEnd() {#a42aaf8d56d380b52f087ba238ce10c52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::goToEnd ()</td>
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

<p>goToEnd - Move beyond the last interval in map.</p>

<p>Definition at line 1447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#a24c3474afac43c88fc6a212441971a90">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::map</a> and <a href="#aa02ccfd91f0ae5d754f370be26e3191e">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::setRoot</a>.</p>

</div>
</div>

### setMap() {#a16b2c8e378000a0894391bc4f741369a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::setMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a> &amp; m)</td>
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

<p>setMap - Change the map iterated over.</p>


<p>This call must be followed by a call to <a href="#adaec49caab60813b87e4efb180ce1675">goToBegin()</a>, <a href="#a42aaf8d56d380b52f087ba238ce10c52">goToEnd()</a>, or <a href="#ab827f91e03f3338b2b943a00f0bee07d">find()</a></p>


<p>Definition at line 1407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#ae974639f12394e77cf9c059c6b064499">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::IntervalMap</a> and <a href="#a24c3474afac43c88fc6a212441971a90">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::map</a>.</p>

</div>
</div>

### start() {#a6f262ebbf77347c4999ae7455a59dd99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const KeyT &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::start ()</td>
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

<p>start - Return the beginning of the current interval.</p>

<p>Definition at line 1416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="#ad77530a792ede3ca10c8e07d61122afc">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::unsafeStart</a>.</p>


<p>Referenced by <a href="#ad77530a792ede3ca10c8e07d61122afc">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::unsafeStart</a>.</p>

</div>
</div>

### stop() {#a437e7639824aff20c0def7dc276db2f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const KeyT &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::stop ()</td>
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

<p>stop - Return the end of the current interval.</p>

<p>Definition at line 1419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="#a468d104ec5d2a57389590ae1d04f94cf">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::unsafeStop</a>.</p>


<p>Referenced by <a href="#a468d104ec5d2a57389590ae1d04f94cf">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::unsafeStop</a>.</p>

</div>
</div>

### valid() {#a548db093f880ebc0c1706229e898c2f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::valid ()</td>
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

<p>valid - Return true if the current position is valid, false for <a href="/web-llvm/docs/api/classes/llvm/intervalmap/#a9f207a7ea5e716ddd6e894086b593941">end()</a>.</p>

<p>Definition at line 1410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="#a9698a846e49b6c946d5fbe616dc9e2ea">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::path</a>.</p>


<p>Referenced by <a href="#a27e1981325e2267e65652eaddb2cb236">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::advanceTo</a>, <a href="#a4b8573afd2c65e3391bfdd92e5c42d8d">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator++</a>, <a href="#ace4989cb01faf6a4cde20e40d7df8c0c">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator--</a>, <a href="#a3b8e82aa59078f5275fc515e1a6ed7c4">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator==</a>, <a href="#a7136191f76b76ad1bef786f47f2c9846">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::treeAdvanceTo</a>, <a href="#aafa139bd49fa2f2b3df1e7a223e1bc2e">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::treeFind</a>, <a href="#ad77530a792ede3ca10c8e07d61122afc">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::unsafeStart</a>, <a href="#a468d104ec5d2a57389590ae1d04f94cf">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::unsafeStop</a> and <a href="#a82942d6073064b572e72b0f6ed853934">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::unsafeValue</a>.</p>

</div>
</div>

### value() {#a88ec9c35789c76004d1f7dcf690db2b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ValT &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::value ()</td>
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

<p>value - Return the mapped value at the current interval.</p>

<p>Definition at line 1422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="#a82942d6073064b572e72b0f6ed853934">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::unsafeValue</a>.</p>


<p>Referenced by <a href="#a840f7c85b9dfb849db4758270cc41523">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator*</a> and <a href="#a82942d6073064b572e72b0f6ed853934">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::unsafeValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### branched() {#adddc6e7d112bd7d8e211c46e3d0d2e7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::branched ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a24c3474afac43c88fc6a212441971a90">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::map</a>.</p>


<p>Referenced by <a href="#a27e1981325e2267e65652eaddb2cb236">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::advanceTo</a>, <a href="#ab827f91e03f3338b2b943a00f0bee07d">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::find</a>, <a href="#adaec49caab60813b87e4efb180ce1675">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::goToBegin</a>, <a href="#a4b8573afd2c65e3391bfdd92e5c42d8d">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator++</a>, <a href="#ace4989cb01faf6a4cde20e40d7df8c0c">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator--</a>, <a href="#aa02ccfd91f0ae5d754f370be26e3191e">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::setRoot</a>, <a href="#ad77530a792ede3ca10c8e07d61122afc">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::unsafeStart</a>, <a href="#a468d104ec5d2a57389590ae1d04f94cf">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::unsafeStop</a> and <a href="#a82942d6073064b572e72b0f6ed853934">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::unsafeValue</a>.</p>

</div>
</div>

### pathFillFind() {#a3187b02e986777ccb9953b73ac6fda6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::pathFillFind (KeyT x)</td>
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

<p>pathFillFind - Complete path by searching for x.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">x</td>
<td class="doxyParamItemDescription"><p>Key to search for.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef/#a72f4d80e311bbd788942cedb25e0ff4e">llvm::IntervalMapImpl::NodeRef::get</a>, <a href="#a24c3474afac43c88fc6a212441971a90">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::map</a>, <a href="#a9698a846e49b6c946d5fbe616dc9e2ea">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::path</a> and <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef/#ad56a61be137a6adfe4327233a4e492f9">llvm::IntervalMapImpl::NodeRef::subtree</a>.</p>


<p>Referenced by <a href="#a7136191f76b76ad1bef786f47f2c9846">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::treeAdvanceTo</a> and <a href="#aafa139bd49fa2f2b3df1e7a223e1bc2e">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::treeFind</a>.</p>

</div>
</div>

### setRoot() {#aa02ccfd91f0ae5d754f370be26e3191e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::setRoot (unsigned Offset)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#adddc6e7d112bd7d8e211c46e3d0d2e7b">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::branched</a>, <a href="#a24c3474afac43c88fc6a212441971a90">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::map</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a9698a846e49b6c946d5fbe616dc9e2ea">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::path</a>.</p>


<p>Referenced by <a href="#ab827f91e03f3338b2b943a00f0bee07d">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::find</a>, <a href="#adaec49caab60813b87e4efb180ce1675">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::goToBegin</a>, <a href="#a42aaf8d56d380b52f087ba238ce10c52">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::goToEnd</a>, <a href="#a7136191f76b76ad1bef786f47f2c9846">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::treeAdvanceTo</a> and <a href="#aafa139bd49fa2f2b3df1e7a223e1bc2e">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::treeFind</a>.</p>

</div>
</div>

### treeAdvanceTo() {#a7136191f76b76ad1bef786f47f2c9846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::treeAdvanceTo (KeyT x)</td>
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

<p>treeAdvanceTo - Find position after the current one.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">x</td>
<td class="doxyParamItemDescription"><p>Key to search for.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#a24c3474afac43c88fc6a212441971a90">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::map</a>, <a href="#a9698a846e49b6c946d5fbe616dc9e2ea">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::path</a>, <a href="#a3187b02e986777ccb9953b73ac6fda6b">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::pathFillFind</a>, <a href="#aa02ccfd91f0ae5d754f370be26e3191e">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::setRoot</a> and <a href="#a548db093f880ebc0c1706229e898c2f2">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::valid</a>.</p>


<p>Referenced by <a href="#a27e1981325e2267e65652eaddb2cb236">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::advanceTo</a>.</p>

</div>
</div>

### treeFind() {#aafa139bd49fa2f2b3df1e7a223e1bc2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::treeFind (KeyT x)</td>
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

<p>treeFind - Find in a branched tree.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">x</td>
<td class="doxyParamItemDescription"><p>Key to search for.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#a24c3474afac43c88fc6a212441971a90">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::map</a>, <a href="#a3187b02e986777ccb9953b73ac6fda6b">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::pathFillFind</a>, <a href="#aa02ccfd91f0ae5d754f370be26e3191e">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::setRoot</a> and <a href="#a548db093f880ebc0c1706229e898c2f2">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::valid</a>.</p>


<p>Referenced by <a href="#ab827f91e03f3338b2b943a00f0bee07d">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::find</a>.</p>

</div>
</div>

### unsafeStart() {#ad77530a792ede3ca10c8e07d61122afc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KeyT &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::unsafeStart ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>unsafeStart - Writable access to <a href="#a6f262ebbf77347c4999ae7455a59dd99">start()</a> for iterator.</p>

<p>Definition at line 1381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#adddc6e7d112bd7d8e211c46e3d0d2e7b">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::branched</a>, <a href="#a9698a846e49b6c946d5fbe616dc9e2ea">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::path</a>, <a href="#a6f262ebbf77347c4999ae7455a59dd99">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::start</a> and <a href="#a548db093f880ebc0c1706229e898c2f2">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::valid</a>.</p>


<p>Referenced by <a href="#a6f262ebbf77347c4999ae7455a59dd99">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::start</a>.</p>

</div>
</div>

### unsafeStop() {#a468d104ec5d2a57389590ae1d04f94cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KeyT &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::unsafeStop ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>unsafeStop - Writable access to <a href="#a437e7639824aff20c0def7dc276db2f7">stop()</a> for iterator.</p>

<p>Definition at line 1388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#adddc6e7d112bd7d8e211c46e3d0d2e7b">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::branched</a>, <a href="#a9698a846e49b6c946d5fbe616dc9e2ea">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::path</a>, <a href="#a437e7639824aff20c0def7dc276db2f7">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::stop</a> and <a href="#a548db093f880ebc0c1706229e898c2f2">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::valid</a>.</p>


<p>Referenced by <a href="#a437e7639824aff20c0def7dc276db2f7">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::stop</a>.</p>

</div>
</div>

### unsafeValue() {#a82942d6073064b572e72b0f6ed853934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValT &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::unsafeValue ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>unsafeValue - Writable access to <a href="#a88ec9c35789c76004d1f7dcf690db2b4">value()</a> for iterator.</p>

<p>Definition at line 1395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#adddc6e7d112bd7d8e211c46e3d0d2e7b">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::branched</a>, <a href="#a9698a846e49b6c946d5fbe616dc9e2ea">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::path</a>, <a href="#a548db093f880ebc0c1706229e898c2f2">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::valid</a> and <a href="#a88ec9c35789c76004d1f7dcf690db2b4">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::value</a>.</p>


<p>Referenced by <a href="#a88ec9c35789c76004d1f7dcf690db2b4">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### map {#a24c3474afac43c88fc6a212441971a90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntervalMap* llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::map = nullptr</td>
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



<p>Definition at line 1355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#a27e1981325e2267e65652eaddb2cb236">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::advanceTo</a>, <a href="#adddc6e7d112bd7d8e211c46e3d0d2e7b">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::branched</a>, <a href="#a19785dafd2ac873fe41085bf3125e0f9">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::const_iterator</a>, <a href="#ab827f91e03f3338b2b943a00f0bee07d">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::find</a>, <a href="#adaec49caab60813b87e4efb180ce1675">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::goToBegin</a>, <a href="#a42aaf8d56d380b52f087ba238ce10c52">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::goToEnd</a>, <a href="#a4b8573afd2c65e3391bfdd92e5c42d8d">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator++</a>, <a href="#ace4989cb01faf6a4cde20e40d7df8c0c">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator--</a>, <a href="#a3b8e82aa59078f5275fc515e1a6ed7c4">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator==</a>, <a href="#a3187b02e986777ccb9953b73ac6fda6b">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::pathFillFind</a>, <a href="#a16b2c8e378000a0894391bc4f741369a">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::setMap</a>, <a href="#aa02ccfd91f0ae5d754f370be26e3191e">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::setRoot</a>, <a href="#a7136191f76b76ad1bef786f47f2c9846">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::treeAdvanceTo</a> and <a href="#aafa139bd49fa2f2b3df1e7a223e1bc2e">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::treeFind</a>.</p>

</div>
</div>

### path {#a9698a846e49b6c946d5fbe616dc9e2ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntervalMapImpl::Path llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::path</td>
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



<p>Definition at line 1359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#a27e1981325e2267e65652eaddb2cb236">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::advanceTo</a>, <a href="#ab0e25ec43a32750831019356a025f75d">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::atBegin</a>, <a href="#adaec49caab60813b87e4efb180ce1675">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::goToBegin</a>, <a href="#a4b8573afd2c65e3391bfdd92e5c42d8d">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator++</a>, <a href="#ace4989cb01faf6a4cde20e40d7df8c0c">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator--</a>, <a href="#a3b8e82aa59078f5275fc515e1a6ed7c4">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator==</a>, <a href="#a3187b02e986777ccb9953b73ac6fda6b">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::pathFillFind</a>, <a href="#aa02ccfd91f0ae5d754f370be26e3191e">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::setRoot</a>, <a href="#a7136191f76b76ad1bef786f47f2c9846">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::treeAdvanceTo</a>, <a href="#ad77530a792ede3ca10c8e07d61122afc">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::unsafeStart</a>, <a href="#a468d104ec5d2a57389590ae1d04f94cf">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::unsafeStop</a>, <a href="#a82942d6073064b572e72b0f6ed853934">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::unsafeValue</a> and <a href="#a548db093f880ebc0c1706229e898c2f2">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::valid</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
