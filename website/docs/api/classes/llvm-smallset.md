---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/smallset
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SmallSet` Class Template Reference

<p><a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a> - This maintains a set of unique values, optimizing for the case when the set is small (less than N). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;
class llvm::SmallSet&lt;T, N, C&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a415fafb747d0aaf1e2f44adb4299297f">key_type</a> = T</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7661e59c6b08b41c98031595ae8007f9">size_type</a> = size_t</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a92339d5306ea2a5153ca8688bde5b814">value_type</a> = T</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2b2485e23744fb5f349b2a4d29417e0b">const_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallsetiterator">SmallSetIterator</a>&lt; T, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">C</a> &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a642ef3f957486e94785fdc2ccafcb692">SmallSet</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa92bbdb8568f16a3729854362203aa1f">SmallSet</a> (const SmallSet &amp;)=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa2df2a9c432ae7bc07354a0b50a71d49">SmallSet</a> (SmallSet &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aca40736363928e517cf3b4d810c04a42">SmallSet</a> (IterT Begin, IterT End)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename RangeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a0515d5a20ae68db02fe65e3e9c43e3ee">SmallSet</a> (const iterator_range&lt; RangeT &gt; &amp;R)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a55c37829263bbc9d089bb45a43c91643">SmallSet</a> (std::initializer_list&lt; T &gt; L)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a95d576b12e0c94402da943f5577a44dc">operator=</a> (const SmallSet &amp;)=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aefea379389d05a17d6c41018aec98a94">operator=</a> (SmallSet &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a34384400167eb6ebf71fa89d98ba03bc">empty</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a7661e59c6b08b41c98031595ae8007f9">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afd7c135e18f2d7253d4f8545cd7b1756">size</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a7661e59c6b08b41c98031595ae8007f9">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2a98f19750ba941ce791b75ca6d77e48">count</a> (const T &amp;V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>count - Return 1 if the element is in the set, 0 otherwise. <a href="#a2a98f19750ba941ce791b75ca6d77e48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afcadfef2cf37c3e6dbdbc9cd7bea50a0">insert</a> (const T &amp;V) -&gt; std::pair&lt; <a href="#a2b2485e23744fb5f349b2a4d29417e0b">const_iterator</a>, bool &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>insert - Insert an element into the set if it isn't already there. <a href="#afcadfef2cf37c3e6dbdbc9cd7bea50a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4f9e8fa45afc21ffd30b6b4afb4477f2">insert</a> (T &amp;&amp;V) -&gt; std::pair&lt; <a href="#a2b2485e23744fb5f349b2a4d29417e0b">const_iterator</a>, bool &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a36a9c780e819dd796564004fefef1ff7">insert</a> (IterT I, IterT E)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a75a2d2ad3b3dce6702750d570ee8f343">erase</a> (const T &amp;V)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a76b3fc7c102561fb5210d5151531e409">clear</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a2b2485e23744fb5f349b2a4d29417e0b">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0d7ad8e1022557e52ac17dddf1f5db2f">begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a2b2485e23744fb5f349b2a4d29417e0b">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac51f13177f0eb63f139dde87ef60a149">end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae04ad615dfdd885e85cbddda146787c6">contains</a> (const T &amp;V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a> contains the given element. <a href="#ae04ad615dfdd885e85cbddda146787c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab07ead69498036a832887447358c106a">isSmall</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ArgType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a582eb85fe30636ead9ce7a878b6b45e2">insertImpl</a> (ArgType &amp;&amp;V) -&gt; std::pair&lt; <a href="#a2b2485e23744fb5f349b2a4d29417e0b">const_iterator</a>, bool &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aff468b65d353cf34e740458bb5e4708d">vfind</a> (const T &amp;V) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; T, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> &gt;::const_iterator</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; T, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa6a8e1e0357935e8229c34f8f9b5ffeb">Vector</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> a <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> to hold the elements here (even though it will never reach its 'large' stage) to avoid calling the default ctors of elements we will never use. <a href="#aa6a8e1e0357935e8229c34f8f9b5ffeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::set&lt; T, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">C</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adcd05a9877124808635cff8fb00298e5">Set</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a> - This maintains a set of unique values, optimizing for the case when the set is small (less than N).</p>


<p>In this case, the set can be maintained with no mallocs. If the set gets large, we expand to using an std::set to maintain reasonable lookup times.</p>


<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a2b2485e23744fb5f349b2a4d29417e0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallSet&lt; T, N, C &gt;::const_iterator =  SmallSetIterator&lt;T, N, C&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

### key\_type {#a415fafb747d0aaf1e2f44adb4299297f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallSet&lt; T, N, C &gt;::key_type =  T</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

### size\_type {#a7661e59c6b08b41c98031595ae8007f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallSet&lt; T, N, C &gt;::size_type =  size_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

### value\_type {#a92339d5306ea2a5153ca8688bde5b814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallSet&lt; T, N, C &gt;::value_type =  T</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SmallSet() {#a642ef3f957486e94785fdc2ccafcb692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallSet&lt; T, N, C &gt;::SmallSet ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

### SmallSet() {#aa92bbdb8568f16a3729854362203aa1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallSet&lt; T, N, C &gt;::SmallSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a> &amp;)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

### SmallSet() {#aa2df2a9c432ae7bc07354a0b50a71d49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallSet&lt; T, N, C &gt;::SmallSet (<a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a> &amp;&amp;)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

### SmallSet() {#aca40736363928e517cf3b4d810c04a42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallSet&lt; T, N, C &gt;::SmallSet (IterT Begin, IterT End)</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

### SmallSet() {#a0515d5a20ae68db02fe65e3e9c43e3ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RangeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallSet&lt; T, N, C &gt;::SmallSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; RangeT &gt; &amp; R)</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

### SmallSet() {#a55c37829263bbc9d089bb45a43c91643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallSet&lt; T, N, C &gt;::SmallSet (std::initializer_list&lt; T &gt; L)</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a95d576b12e0c94402da943f5577a44dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSet &amp; llvm::SmallSet&lt; T, N, C &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a> &amp;)</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

### operator=() {#aefea379389d05a17d6c41018aec98a94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSet &amp; llvm::SmallSet&lt; T, N, C &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a> &amp;&amp;)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a0d7ad8e1022557e52ac17dddf1f5db2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::SmallSet&lt; T, N, C &gt;::begin ()</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a88d50bb943ed6d9b7bf0a34367d018af">interpretValues</a>.</p>

</div>
</div>

### clear() {#a76b3fc7c102561fb5210d5151531e409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallSet&lt; T, N, C &gt;::clear ()</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a101c3c30a65314c6f3fe10fbc1fa1539">llvm::HexagonSubtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a1e2f76e32afeff50a4cae3055b365099">findConsecutiveLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp/#a1429d1fad1503cf63298bd5441e0e04b">isProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ac33f356faceb9655cb64611d2971d24f">ReduceLoopStrength</a> and <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizer/#ae6c94cc4b29dfbcc1cc39b73e871ec2a">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizer::run</a>.</p>

</div>
</div>

### contains() {#ae04ad615dfdd885e85cbddda146787c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallSet&lt; T, N, C &gt;::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; V)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a> contains the given element.</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp/#a8380bda17afbeb9b1792136a17e55f74">clobberRegEntries</a>, <a href="#a2a98f19750ba941ce791b75ca6d77e48">llvm::SmallSet&lt; PlatformType, 3 &gt;::count</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#ad60e02442ef62d5d7f19fd7f73aa0508">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::findRegistersToSpill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#ade8ad153c39e5550054c7873486dd21d">foldConstantsIntoIntrinsics</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9e4f7b81913ac2176cac1eaa2b66a0b7">gatherPossiblyVectorizableLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#ae26138aceef07cf5465c2840b437e1d8">llvm::SMSchedule::normalizeNonPipelinedInstructions</a> and <a href="/web-llvm/docs/api/classes/anonymous-promotememorytoregister-cpp-/assignmenttrackinginfo/#a92fba2b8745329ee14995b36cf720f68">anonymous{PromoteMemoryToRegister.cpp}::AssignmentTrackingInfo::updateForDeletedStore</a>.</p>

</div>
</div>

### count() {#a2a98f19750ba941ce791b75ca6d77e48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::SmallSet&lt; T, N, C &gt;::count (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; V)</td>
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

<p>count - Return 1 if the element is in the set, 0 otherwise.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzregisterinfo-cpp/#aaf08c51751e9ec671a84a92af1daab99">addHints</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a23d6b914952799027040a351f501a0ad">llvm::SMSchedule::computeUnpipelineableNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abef9f720617461778f1a2e49d17ea159">llvm::ARMBaseInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9c5f771f232bbd4cf6ec230bd78f9174">llvm::Instruction::dropUnknownNonDebugMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a533cd1035e03cdca3da433e98e77e430">llvm::AMDGPURegisterBankInfo::executeInWaterfallLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a43ffe9d0de2c3fc1eb0c8bb0b6c7526d">anonymous{ARMAsmParser.cpp}::ARMAsmParser::FilterNearMisses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a077981b5798a5d7a95cec16ece863aeb">llvm::finalizeBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a1e2f76e32afeff50a4cae3055b365099">findConsecutiveLoad</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#a0c3a1721c534dbc63fdc081a9365fd9c">llvm::rdf::Liveness::getAllReachingDefs</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#ad490ad7663a07141538a6f4049299550">llvm::RISCVRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a31e904f48ac2baf80f9222c49059ef63">llvm::SystemZRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#ada2b3cb4854ef22758c48e3721ddb1e2">llvm::X86RegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics/#a54d9af6b4c656c782e017020406e8291">llvm::slpvectorizer::BoUpSLP::LookAheadHeuristics::getScoreAtLevelRec</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp/#ad84119ef27970279d969c50b73d8d62b">getUniqueCaseValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a4e0750d12818ab0f8a301e4be935ea72">hoistAndMergeSGPRInits</a>, <a href="/web-llvm/docs/api/classes/llvm/windowscheduler/#af02c395926a140c8121e0e7d16e1dfe1">llvm::WindowScheduler::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-delayslotfiller-cpp-/filler/#a69c882828373f9113a87c3bb0823695d">anonymous{DelaySlotFiller.cpp}::Filler::IsRegInSet</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaidelayslotfiller-cpp-/filler/#a72a4812c58fcd7d9724a62d3b313871d">anonymous{LanaiDelaySlotFiller.cpp}::Filler::isRegInSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a1c1669c081e93349baa5bcf3ca5aaae4">IsSafeAndProfitableToMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#afb4050a6cd4ceb53360df94a2ff6be39">MaySpeculate</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a1ac412f2e4cc981d3b9d3f6cf6d5988a">anonymous{MachineOutliner.cpp}::MachineOutliner::outline</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp/#a10d5495926e5659dbcefde78541b29a8">ProcessSourceNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ae1f1125c20c109a1dedb0cafbb501c22">programUndefinedIfUndefOrPoison</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizer/#ae6c94cc4b29dfbcc1cc39b73e871ec2a">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizer::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86pretileconfig-cpp-/x86pretileconfig/#a5d1d05840235d52ee7fb4b0ce9a63b76">anonymous{X86PreTileConfig.cpp}::X86PreTileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a302583dfd143c9bb87f8274ba0dc727b">verifyCTRBranch</a>.</p>

</div>
</div>

### empty() {#a34384400167eb6ebf71fa89d98ba03bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallSet&lt; T, N, C &gt;::empty ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a1d33fd387b81b22c1074a78d30192fea">llvm::AMDGPURegisterBankInfo::collectWaterfallOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#ad60e02442ef62d5d7f19fd7f73aa0508">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::findRegistersToSpill</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#a96179307953b47569983bcd440f76130">IsValueFullyAvailableInBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/shuffleblockstrategy/#a3bad39b7c7fd81aa15068f082eb6f0a6">llvm::ShuffleBlockStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizer/#ae6c94cc4b29dfbcc1cc39b73e871ec2a">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizer::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86pretileconfig-cpp-/x86pretileconfig/#a5d1d05840235d52ee7fb4b0ce9a63b76">anonymous{X86PreTileConfig.cpp}::X86PreTileConfig::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a49a46654ca2c32ce99be52de089052f8">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::Visit</a>.</p>

</div>
</div>

### end() {#ac51f13177f0eb63f139dde87ef60a149}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::SmallSet&lt; T, N, C &gt;::end ()</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a88d50bb943ed6d9b7bf0a34367d018af">interpretValues</a>.</p>

</div>
</div>

### erase() {#a75a2d2ad3b3dce6702750d570ee8f343}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallSet&lt; T, N, C &gt;::erase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; V)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a077981b5798a5d7a95cec16ece863aeb">llvm::finalizeBundle</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#abbf02514d481b5292b34f111865e4605">anonymous{MachineCopyPropagation.cpp}::CopyTracker::invalidateRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#a96179307953b47569983bcd440f76130">IsValueFullyAvailableInBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a1ac412f2e4cc981d3b9d3f6cf6d5988a">anonymous{MachineOutliner.cpp}::MachineOutliner::outline</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizer/#ae6c94cc4b29dfbcc1cc39b73e871ec2a">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizer::run</a> and <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a49a46654ca2c32ce99be52de089052f8">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::Visit</a>.</p>

</div>
</div>

### insert() {#afcadfef2cf37c3e6dbdbc9cd7bea50a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; const_iterator, bool &gt; llvm::SmallSet&lt; T, N, C &gt;::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; V)</td>
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

<p>insert - Insert an element into the set if it isn't already there.</p>


<p>Returns a pair. The first value of it is an iterator to the inserted element or the existing element in the set. The second value is true if the element is inserted (it was not in the set before).</p>


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a9a91b779e07acc1400574b81f1ba1a70">addConstantsToTrack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzregisterinfo-cpp/#aaf08c51751e9ec671a84a92af1daab99">addHints</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a3c04d483e66e81efc4812a2d38b93a8d">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; IndexCallsiteContextGraph, FunctionSummary, IndexCall &gt;::addStackNodesForMIB</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/offsetinfo/#afc62d5cbad359ff2a03b831053c470ec">llvm::AAPointerInfo::OffsetInfo::addToAll</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a222d514d23098e92ecbd53e36b3c5084">llvm::GCNDownwardRPTracker::advanceBeforeNext</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp/#a4a408b05eacd6ea605ddc856dcf57f11">AntiDepEdges</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#afb1a8a9ef7b460687963fb7968fb7626">llvm::AMDGPURegisterBankInfo::applyMappingSBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a28512659006140e4ac78ee3a68043dd5">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdatesPermissive</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#affbf848c4397f6d186cfdde655e6dd0e">AssignProtectedObjSet</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a97370114df349e0996f133e3402c1595">llvm::changeToUnreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp/#abbaf6b527fda317964759a8917f436cd">CheckForLiveRegDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a37a1b9361cb4ed78aa4af0973696f7fb">CheckForLiveRegDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#affd5619a70ecc254d62f604150468f1d">CheckForLiveRegDefMasked</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp/#a8380bda17afbeb9b1792136a17e55f74">clobberRegEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a44f91224211f7d2538f311f9a916264d">llvm::JumpThreadingPass::cloneInstructions</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#a5290bdffbf68a26e47345d1bb2abb246">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::collectCandidateRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a8dc41af84f49f4b418bddf15547755af">llvm::VPRecipeBuilder::collectScaledReductions</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a1d33fd387b81b22c1074a78d30192fea">llvm::AMDGPURegisterBankInfo::collectWaterfallOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ade03879f56390aad1613d54401f911a5">combineShuffleOfScalars</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ab92b093e430b26d0fe06b8365fc1ebd8">anonymous{AArch64AsmParser.cpp}::AArch64Operand::ComputeRegsForAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a23d6b914952799027040a351f501a0ad">llvm::SMSchedule::computeUnpipelineableNodes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a152d8c380cc937c9dceb402ceec943b6">llvm::ConstantFoldTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ab8b249a6f01a1f333bc2bfbc6463251c">llvm::PPCInstrInfo::convertToImmediateForm</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abef9f720617461778f1a2e49d17ea159">llvm::ARMBaseInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#adfad68845808cb6acd116e50b15bc281">despeculateCountZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9c5f771f232bbd4cf6ec230bd78f9174">llvm::Instruction::dropUnknownNonDebugMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a096fcb1d6b0da7425a8cc7dbb8ddd526">llvm::HexagonRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a013467bb98e0c35a48763e22de49cc75">llvm::WebAssemblyAsmPrinter::EmitProducerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a43ffe9d0de2c3fc1eb0c8bb0b6c7526d">anonymous{ARMAsmParser.cpp}::ARMAsmParser::FilterNearMisses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a077981b5798a5d7a95cec16ece863aeb">llvm::finalizeBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a1e2f76e32afeff50a4cae3055b365099">findConsecutiveLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a63fa5eea47d71eee71631388500cc8e5">llvm::DWARFDie::findRecursively</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#ad60e02442ef62d5d7f19fd7f73aa0508">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::findRegistersToSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a537788ca2a4d7bbdbfad2ac8e5dfabca">llvm::R600InstrInfo::fitsConstReadLimitations</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#af950841a4443ffb7aff66ae75fee8442">foldURemOfLoopIncrement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9e4f7b81913ac2176cac1eaa2b66a0b7">gatherPossiblyVectorizableLoads</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ae86be98f39008a27ba987e282fc8dc2c">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::genericValueTraversal</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#a0c3a1721c534dbc63fdc081a9365fd9c">llvm::rdf::Liveness::getAllReachingDefs</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#ad490ad7663a07141538a6f4049299550">llvm::RISCVRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a31e904f48ac2baf80f9222c49059ef63">llvm::SystemZRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#afc99d2835eb4b8cde9e81db9abca597c">llvm::TargetRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#ada2b3cb4854ef22758c48e3721ddb1e2">llvm::X86RegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics/#a54d9af6b4c656c782e017020406e8291">llvm::slpvectorizer::BoUpSLP::LookAheadHeuristics::getScoreAtLevelRec</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp/#ad84119ef27970279d969c50b73d8d62b">getUniqueCaseValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#ad025b047378266c13a216920a6ec3346">handleNormalInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchoptwinstrs-cpp/#acc4b9161e5bdda1e0f5482ad8b9a64ba">hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#aaa5ecbb121a4af66e98e1ddbff7b925d">hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a4e0750d12818ab0f8a301e4be935ea72">hoistAndMergeSGPRInits</a>, <a href="/web-llvm/docs/api/classes/anonymous-promotememorytoregister-cpp-/assignmenttrackinginfo/#ab80aaa2bd158207080b9e7345a12fce3">anonymous{PromoteMemoryToRegister.cpp}::AssignmentTrackingInfo::init</a>, <a href="/web-llvm/docs/api/classes/llvm/windowscheduler/#af02c395926a140c8121e0e7d16e1dfe1">llvm::WindowScheduler::initialize</a>, <a href="#a36a9c780e819dd796564004fefef1ff7">llvm::SmallSet&lt; PlatformType, 3 &gt;::insert</a>, <a href="/web-llvm/docs/api/structs/anonymous-delayslotfiller-cpp-/filler/#a38691dc780e36d270e9f13eeb4fdb28f">anonymous{DelaySlotFiller.cpp}::Filler::insertCallDefsUses</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a21fc5eae685ef3e2dce4403a75d5ff2f">llvm::MemorySSAUpdater::insertDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-delayslotfiller-cpp-/filler/#a5cb3123a65f33114054eb5ab842b2d76">anonymous{DelaySlotFiller.cpp}::Filler::insertDefsUses</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaidelayslotfiller-cpp-/filler/#afca8ae34e03582f93e75d11b23cbe245">anonymous{LanaiDelaySlotFiller.cpp}::Filler::insertDefsUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a88d50bb943ed6d9b7bf0a34367d018af">interpretValues</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#abbf02514d481b5292b34f111865e4605">anonymous{MachineCopyPropagation.cpp}::CopyTracker::invalidateRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af55cf9792d5f9186df02c58b337a1511">llvm::AMDGPU::isClobberedInFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ae32b03825183735233b4142e1945abf8">isLoadCombineCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp/#a1429d1fad1503cf63298bd5441e0e04b">isProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a1c1669c081e93349baa5bcf3ca5aaae4">IsSafeAndProfitableToMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchoptwinstrs-cpp/#a7b61861295f70647f6dd85931782b93d">isSignExtendedW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#a333d3161d9b4420d11b777bd154148bf">isSignExtendedW</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#a96179307953b47569983bcd440f76130">IsValueFullyAvailableInBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#af664c713571d51d8130da27b28cc2088">liesBetween</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a32cff45e4cfd323ecc3896adcb08c2a9">llvm::SelectionDAGBuilder::LowerStatepoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#a7df4bae7dbd152d7a3c399384a110fe8">anonymous{SLPVectorizer.cpp}::HorizontalReduction::matchAssociativeReduction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a023f82db84f5e5ed13398308496689e7">llvm::mustExecuteUBIfPoisonOnPathTo</a>, <a href="/web-llvm/docs/api/classes/llvm/shuffleblockstrategy/#a3bad39b7c7fd81aa15068f082eb6f0a6">llvm::ShuffleBlockStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#a776834e825e7fd9cd90c27f7ace1d9d2">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::needToBeConvertedToVALU</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a1ac412f2e4cc981d3b9d3f6cf6d5988a">anonymous{MachineOutliner.cpp}::MachineOutliner::outline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a89d936a98d65c79ddb962452b2d670bd">llvm::PointerMayBeCaptured</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#aadcf47d2bfa2abd153d66b001715198c">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::processPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp/#a10d5495926e5659dbcefde78541b29a8">ProcessSourceNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ae1f1125c20c109a1dedb0cafbb501c22">programUndefinedIfUndefOrPoison</a>, <a href="/web-llvm/docs/api/classes/llvm/swifterrorvaluetracking/#afc960ff953a4a9d9fbf91baf590222d2">llvm::SwiftErrorValueTracking::propagateVRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a19e092ecf7889abf7277f13824e0c601">replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/anonymous-canonicalizefreezeinloops-cpp-/canonicalizefreezeinloopsimpl/#aff534de0962628bba1821ef3c0821308">anonymous{CanonicalizeFreezeInLoops.cpp}::CanonicalizeFreezeInLoopsImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpusetwavepriority-cpp-/amdgpusetwavepriority/#abca075108e917d65c698fd137d0afdd9">anonymous{AMDGPUSetWavePriority.cpp}::AMDGPUSetWavePriority::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86pretileconfig-cpp-/x86pretileconfig/#a5d1d05840235d52ee7fb4b0ce9a63b76">anonymous{X86PreTileConfig.cpp}::X86PreTileConfig::runOnMachineFunction</a>, <a href="#a0515d5a20ae68db02fe65e3e9c43e3ee">llvm::SmallSet&lt; PlatformType, 3 &gt;::SmallSet</a>, <a href="#aca40736363928e517cf3b4d810c04a42">llvm::SmallSet&lt; PlatformType, 3 &gt;::SmallSet</a>, <a href="#a55c37829263bbc9d089bb45a43c91643">llvm::SmallSet&lt; PlatformType, 3 &gt;::SmallSet</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa6739b4a0bc5d6540e53c1688aefeed4">llvm::InstCombinerImpl::tryToSinkInstructionDbgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad4296b2b81379548b300c4676f0d2125">llvm::InstCombinerImpl::tryToSinkInstructionDbgVariableRecords</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a1d739ace36dfd7ba0b4069716611fd74">unique_unsorted</a>, <a href="/web-llvm/docs/api/classes/anonymous-promotememorytoregister-cpp-/assignmenttrackinginfo/#a92fba2b8745329ee14995b36cf720f68">anonymous{PromoteMemoryToRegister.cpp}::AssignmentTrackingInfo::updateForDeletedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a302583dfd143c9bb87f8274ba0dc727b">verifyCTRBranch</a> and <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a49a46654ca2c32ce99be52de089052f8">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::Visit</a>.</p>

</div>
</div>

### insert() {#a4f9e8fa45afc21ffd30b6b4afb4477f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; const_iterator, bool &gt; llvm::SmallSet&lt; T, N, C &gt;::insert (T &amp;&amp; V)</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

### insert() {#a36a9c780e819dd796564004fefef1ff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallSet&lt; T, N, C &gt;::insert (IterT I, IterT E)</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

### size() {#afd7c135e18f2d7253d4f8545cd7b1756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::SmallSet&lt; T, N, C &gt;::size ()</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a97370114df349e0996f133e3402c1595">llvm::changeToUnreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a152d8c380cc937c9dceb402ceec943b6">llvm::ConstantFoldTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a096fcb1d6b0da7425a8cc7dbb8ddd526">llvm::HexagonRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a537788ca2a4d7bbdbfad2ac8e5dfabca">llvm::R600InstrInfo::fitsConstReadLimitations</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a21fc5eae685ef3e2dce4403a75d5ff2f">llvm::MemorySSAUpdater::insertDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp/#a1429d1fad1503cf63298bd5441e0e04b">isProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a1c1669c081e93349baa5bcf3ca5aaae4">IsSafeAndProfitableToMove</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#a776834e825e7fd9cd90c27f7ace1d9d2">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::needToBeConvertedToVALU</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a89d936a98d65c79ddb962452b2d670bd">llvm::PointerMayBeCaptured</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### insertImpl() {#a582eb85fe30636ead9ce7a878b6b45e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ArgType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; const_iterator, bool &gt; llvm::SmallSet&lt; T, N, C &gt;::insertImpl (ArgType &amp;&amp; V)</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

### isSmall() {#ab07ead69498036a832887447358c106a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallSet&lt; T, N, C &gt;::isSmall ()</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

### vfind() {#aff468b65d353cf34e740458bb5e4708d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; T, N &gt;::const_iterator llvm::SmallSet&lt; T, N, C &gt;::vfind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; V)</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Set {#adcd05a9877124808635cff8fb00298e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;T, C&gt; llvm::SmallSet&lt; T, N, C &gt;::Set</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

### Vector {#aa6a8e1e0357935e8229c34f8f9b5ffeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C = std::less&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;T, N&gt; llvm::SmallSet&lt; T, N, C &gt;::Vector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> a <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> to hold the elements here (even though it will never reach its 'large' stage) to avoid calling the default ctors of elements we will never use.</p>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
