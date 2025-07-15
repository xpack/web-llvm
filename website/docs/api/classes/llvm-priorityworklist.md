---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/priorityworklist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PriorityWorklist` Class Template Reference

<p>A FILO worklist that prioritizes on re-insertion without duplication. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, typename VectorT = std::vector&lt;T&gt;, typename MapT = DenseMap&lt;T, ptrdiff_t&gt;&gt;
class llvm::PriorityWorklist&lt;T, VectorT, MapT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">llvm/ADT/PriorityWorklist.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a414680285db9c2beaddd5ae0c133603e">value_type</a> = T</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaf87249f8c63e6f9bd508a573ed8cc0f">key_type</a> = T</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aac0da3c25165d8bb4ea8cb041a4b66e1">reference</a> = T &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a142bf5109ba82ca02fadd7846b70f77d">const_reference</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a792cf25babb64672b2dff09915058827">size_type</a> = typename MapT::size_type</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a181449bc327b9ad9222336e1c963d417">PriorityWorklist</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an empty <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a>. <a href="#a181449bc327b9ad9222336e1c963d417">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adc2ef5f0964becc28dfa58a7abc2f1e7">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a> is empty or not. <a href="#adc2ef5f0964becc28dfa58a7abc2f1e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a792cf25babb64672b2dff09915058827">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7b4c8a248c75cf5c264c74f26055d77d">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of elements in the worklist. <a href="#a7b4c8a248c75cf5c264c74f26055d77d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a792cf25babb64672b2dff09915058827">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5f0d26c174e877cd300ffffea988fd17">count</a> (const key_type &amp;key) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Count the number of elements of a given key in the <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a>. <a href="#a5f0d26c174e877cd300ffffea988fd17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0de474a0d8de9597fc17bb366769f2f2">back</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the last element of the <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a>. <a href="#a0de474a0d8de9597fc17bb366769f2f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af74058cc2f8163b1d7128b467432a09b">insert</a> (const T &amp;X)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a new element into the <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a>. <a href="#af74058cc2f8163b1d7128b467432a09b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SequenceT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afef4ecccecce83942fb9d8a1d3b29eb5">insert</a> (SequenceT &amp;&amp;Input) -&gt; std::enable_if_t&lt;!std::is_convertible&lt; SequenceT, T &gt;::value &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a sequence of new elements into the <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a>. <a href="#afef4ecccecce83942fb9d8a1d3b29eb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac777f7757bc8cc92e2f597b3b5b4bad8">pop_back</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the last element of the <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a>. <a href="#ac777f7757bc8cc92e2f597b3b5b4bad8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab89ceb7695256590499de818b5360c54">pop_back_val</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa68247df77e6ce59aa067a7d96bfe55a">erase</a> (const T &amp;X)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase an item from the worklist. <a href="#aa68247df77e6ce59aa067a7d96bfe55a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UnaryPredicate&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa15f397454cd43bae729cbbb71dbcc6e">erase_if</a> (UnaryPredicate P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase items from the set vector based on a predicate function. <a href="#aa15f397454cd43bae729cbbb71dbcc6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6fe5ccc5a4840551db5d9216a4f7117d">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reverse the items in the <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a>. <a href="#a6fe5ccc5a4840551db5d9216a4f7117d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/mapt">MapT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ace4072552d40a5bb23c72059fff91f62">M</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The map from value to index in the vector. <a href="#ace4072552d40a5bb23c72059fff91f62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">VectorT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af85caeea17750c1793398330bfa4bab4">V</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The vector of elements in insertion order. <a href="#af85caeea17750c1793398330bfa4bab4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A FILO worklist that prioritizes on re-insertion without duplication.</p>


<p>This is very similar to a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a></span> with the primary difference that while re-insertion does not create a duplicate, it does adjust the visitation order to respect the last insertion point. This can be useful when the visit order needs to be prioritized based on insertion point without actually having duplicate visits.</p>


<p>Note that this doesn't prevent re-insertion of elements which have been visited – if you need to break cycles, a set will still be necessary.</p>


<p>The type <span class="doxyComputerOutput">T</span> must be default constructable to a null value that will be ignored. It is an error to insert such a value, and popping elements will never produce such a value. It is expected to be used with common nullable types like pointers or optionals.</p>


<p>Internally this uses a vector to store the worklist and a map to identify existing elements in the worklist. Both of these may be customized, but the map must support the basic <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> API for mapping from a T to an integer index into the vector.</p>


<p>A partial specialization is provided to automatically select a <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> and a <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a> if custom data structures are not provided.</p>


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_reference {#a142bf5109ba82ca02fadd7846b70f77d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename VectorT = std::vector&lt;T&gt;, typename MapT = DenseMap&lt;T, ptrdiff_t&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::const_reference =  const T&amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>

</div>
</div>

### key\_type {#aaf87249f8c63e6f9bd508a573ed8cc0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename VectorT = std::vector&lt;T&gt;, typename MapT = DenseMap&lt;T, ptrdiff_t&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::key_type =  T</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>

</div>
</div>

### reference {#aac0da3c25165d8bb4ea8cb041a4b66e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename VectorT = std::vector&lt;T&gt;, typename MapT = DenseMap&lt;T, ptrdiff_t&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::reference =  T&amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>

</div>
</div>

### size\_type {#a792cf25babb64672b2dff09915058827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename VectorT = std::vector&lt;T&gt;, typename MapT = DenseMap&lt;T, ptrdiff_t&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::size_type =  typename MapT::size_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>

</div>
</div>

### value\_type {#a414680285db9c2beaddd5ae0c133603e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename VectorT = std::vector&lt;T&gt;, typename MapT = DenseMap&lt;T, ptrdiff_t&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::value_type =  T</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PriorityWorklist() {#a181449bc327b9ad9222336e1c963d417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename VectorT = std::vector&lt;T&gt;, typename MapT = DenseMap&lt;T, ptrdiff_t&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::PriorityWorklist ()</td>
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

<p>Construct an empty <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a>.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### back() {#a0de474a0d8de9597fc17bb366769f2f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename VectorT = std::vector&lt;T&gt;, typename MapT = DenseMap&lt;T, ptrdiff_t&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T &amp; llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::back ()</td>
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

<p>Return the last element of the <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a>.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#adc2ef5f0964becc28dfa58a7abc2f1e7">llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::empty</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#ac777f7757bc8cc92e2f597b3b5b4bad8">llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::pop_back</a> and <a href="#ab89ceb7695256590499de818b5360c54">llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::pop_back_val</a>.</p>

</div>
</div>

### clear() {#a6fe5ccc5a4840551db5d9216a4f7117d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename VectorT = std::vector&lt;T&gt;, typename MapT = DenseMap&lt;T, ptrdiff_t&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::clear ()</td>
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

<p>Reverse the items in the <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a>.</p>


<p>This does an in-place reversal. Other kinds of reverse aren't easy to support in the face of the worklist semantics. Completely clear the <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a></p>


<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>

</div>
</div>

### count() {#a5f0d26c174e877cd300ffffea988fd17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename VectorT = std::vector&lt;T&gt;, typename MapT = DenseMap&lt;T, ptrdiff_t&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::count (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aaf87249f8c63e6f9bd508a573ed8cc0f">key_type</a> &amp; key)</td>
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

<p>Count the number of elements of a given key in the <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>0 if the element is not in the <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a>, 1 if it is.</p></dd>
</dl>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>

</div>
</div>

### empty() {#adc2ef5f0964becc28dfa58a7abc2f1e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename VectorT = std::vector&lt;T&gt;, typename MapT = DenseMap&lt;T, ptrdiff_t&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::empty ()</td>
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

<p>Determine if the <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a> is empty or not.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>


<p>Referenced by <a href="#a0de474a0d8de9597fc17bb366769f2f2">llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::back</a>, <a href="#ac777f7757bc8cc92e2f597b3b5b4bad8">llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ircepass/#ac7e45d3f509c7e40c4d6666a24e88f73">llvm::IRCEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfoprinterpass/#ac64f34186e4e16d5b0baca6d232c810d">llvm::LoopAccessInfoPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass/#a62ed17cf8aa893362e6c3c1f6d8a0898">llvm::LoopUnrollPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af1236d17bc9dd1041e95f1724eb9cfa6">llvm::sinkRegionForLoopNest</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a0da6529029f6f71768e36765c25d54d5">tryToUnrollAndJamLoop</a>.</p>

</div>
</div>

### erase() {#aa68247df77e6ce59aa067a7d96bfe55a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename VectorT = std::vector&lt;T&gt;, typename MapT = DenseMap&lt;T, ptrdiff_t&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::erase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; X)</td>
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

<p>Erase an item from the worklist.</p>


<p>Note that this is constant time due to the nature of the worklist implementation.</p>


<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### erase\_if() {#aa15f397454cd43bae729cbbb71dbcc6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UnaryPredicate&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::erase_if (UnaryPredicate P)</td>
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

<p>Erase items from the set vector based on a predicate function.</p>


<p>This is intended to be equivalent to the following code, if we could write it:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">V.erase(<a href="/web-llvm/docs/api/namespaces/llvm/#a9ec2517b6489e71067be03afebb4d350">remove_if</a>(V, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>), V.end());</span></span></div>

</div>


<p>However, <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a> doesn't expose non-const iterators, making any algorithm like remove_if impossible to use.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if any element is removed.</p></dd>
</dl>


<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ec2517b6489e71067be03afebb4d350">llvm::remove_if</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### insert() {#af74058cc2f8163b1d7128b467432a09b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename VectorT = std::vector&lt;T&gt;, typename MapT = DenseMap&lt;T, ptrdiff_t&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; X)</td>
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

<p>Insert a new element into the <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the element was inserted into the <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a>.</p></dd>
</dl>


<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a253deb4046b74b2df2b5acd762b95d58">llvm::appendReversedLoopsToWorklist</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af1236d17bc9dd1041e95f1724eb9cfa6">llvm::sinkRegionForLoopNest</a>.</p>

</div>
</div>

### insert() {#afef4ecccecce83942fb9d8a1d3b29eb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SequenceT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt;!std::is_convertible&lt; SequenceT, T &gt;::value &gt; llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::insert (SequenceT &amp;&amp; Input)</td>
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

<p>Insert a sequence of new elements into the <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a>.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### pop\_back() {#ac777f7757bc8cc92e2f597b3b5b4bad8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename VectorT = std::vector&lt;T&gt;, typename MapT = DenseMap&lt;T, ptrdiff_t&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::pop_back ()</td>
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

<p>Remove the last element of the <a href="/web-llvm/docs/api/classes/llvm/priorityworklist">PriorityWorklist</a>.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0de474a0d8de9597fc17bb366769f2f2">llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::back</a>, <a href="#adc2ef5f0964becc28dfa58a7abc2f1e7">llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::empty</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#ab89ceb7695256590499de818b5360c54">llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::pop_back_val</a>.</p>

</div>
</div>

### pop\_back\_val() {#ab89ceb7695256590499de818b5360c54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename VectorT = std::vector&lt;T&gt;, typename MapT = DenseMap&lt;T, ptrdiff_t&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::pop_back_val ()</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>


<p>References <a href="#a0de474a0d8de9597fc17bb366769f2f2">llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::back</a>, <a href="#ac777f7757bc8cc92e2f597b3b5b4bad8">llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::pop_back</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ircepass/#ac7e45d3f509c7e40c4d6666a24e88f73">llvm::IRCEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfoprinterpass/#ac64f34186e4e16d5b0baca6d232c810d">llvm::LoopAccessInfoPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass/#a62ed17cf8aa893362e6c3c1f6d8a0898">llvm::LoopUnrollPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af1236d17bc9dd1041e95f1724eb9cfa6">llvm::sinkRegionForLoopNest</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a0da6529029f6f71768e36765c25d54d5">tryToUnrollAndJamLoop</a>.</p>

</div>
</div>

### size() {#a7b4c8a248c75cf5c264c74f26055d77d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename VectorT = std::vector&lt;T&gt;, typename MapT = DenseMap&lt;T, ptrdiff_t&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::size ()</td>
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

<p>Returns the number of elements in the worklist.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### M {#ace4072552d40a5bb23c72059fff91f62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename VectorT = std::vector&lt;T&gt;, typename MapT = DenseMap&lt;T, ptrdiff_t&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapT llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The map from value to index in the vector.</p>

<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>

</div>
</div>

### V {#af85caeea17750c1793398330bfa4bab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename VectorT = std::vector&lt;T&gt;, typename MapT = DenseMap&lt;T, ptrdiff_t&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorT llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::V</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The vector of elements in insertion order.</p>

<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">PriorityWorklist.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
