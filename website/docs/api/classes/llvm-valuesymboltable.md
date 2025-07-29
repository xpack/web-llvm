---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/valuesymboltable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ValueSymbolTable` Class

<p>This class provides a symbol table of name/value pairs. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ValueSymbolTable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">llvm/IR/ValueSymbolTable.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad70c1404a34a6688de61d1b8f4bfbda7">SymbolTableListTraits&lt; Argument &gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11c7b04e5390fe7e163bf1ad039c757a">SymbolTableListTraits&lt; BasicBlock &gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a660ff91040216811606e493f778936bc">SymbolTableListTraits&lt; Function &gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1989fb0fd1aa69b4142d1e911b92ba50">SymbolTableListTraits&lt; GlobalAlias &gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa096b32e127043e3d34a2eec20637a71">SymbolTableListTraits&lt; GlobalIFunc &gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdb1b42eb1df67c3f9354c0607adeada">SymbolTableListTraits&lt; GlobalVariable &gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1c602c4fb0faa383cdd33bdaee7c58">SymbolTableListTraits&lt; Instruction, ilist_iterator_bits&lt; true &gt;, ilist_parent&lt; BasicBlock &gt; &gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a></td>
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

## Types Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae96e8369c74046a10061c77671589543">ValueMap</a> = <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A mapping of names to values. <a href="#ae96e8369c74046a10061c77671589543">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af70ae50ad5c7be0eba091f868bb09fee">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a84ddb88b13b4bc68478bed9ea1fcf20e">ValueMap::iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An iterator over a <a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a>. <a href="#af70ae50ad5c7be0eba091f868bb09fee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaefca086fa2daa5991fb7d6bcc4f44a9">const_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a075230b87e113348fc39b4f5c30ffaa6">ValueMap::const_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="#aaefca086fa2daa5991fb7d6bcc4f44a9">const_iterator</a> over a <a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a>. <a href="#aaefca086fa2daa5991fb7d6bcc4f44a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Internal Data Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae96e8369c74046a10061c77671589543">ValueMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35b9b47b5a35c6d166cf34be87cffebd">vmap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The map that holds the symbol table. <a href="#a35b9b47b5a35c6d166cf34be87cffebd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16b6e6dd47521f61945f2ff27b2b959c">MaxNameSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum size for each name. <a href="#a16b6e6dd47521f61945f2ff27b2b959c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a543d557dd1892334e78bd65b90e79dec">LastUnique</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Counter for tracking unique names. <a href="#a543d557dd1892334e78bd65b90e79dec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d010dcf5742b976fd1c8a9b3fb84046">ValueSymbolTable</a> (int MaxNameSize=-1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada82898afe6c8ab2d19db4bb28d7d464">~ValueSymbolTable</a> ()</td>
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

## Accessors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7886be195af2a1ec188748a1997b8d75">lookup</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method finds the value with the given <span class="doxyComputerOutput">Name</span> in the the symbol table. <a href="#a7886be195af2a1ec188748a1997b8d75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b012ea30457425f177507538b3edd45">empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3e8a250086a4717b288c738c722919f">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of name/type pairs is returned. <a href="#af3e8a250086a4717b288c738c722919f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e9cc2b295b104ebd2c7d5b4d7960f10">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function can be used from the debugger to display the content of the symbol table while debugging. <a href="#a4e9cc2b295b104ebd2c7d5b4d7960f10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Iteration Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af70ae50ad5c7be0eba091f868bb09fee">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4c7a859b6d520a4a696b6f7dfc0c37e">begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an iterator that from the beginning of the symbol table. <a href="#af4c7a859b6d520a4a696b6f7dfc0c37e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aaefca086fa2daa5991fb7d6bcc4f44a9">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67f15de6368d915a69d31f9d18e5ce6d">begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a <a href="#aaefca086fa2daa5991fb7d6bcc4f44a9">const_iterator</a> that from the beginning of the symbol table. <a href="#a67f15de6368d915a69d31f9d18e5ce6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af70ae50ad5c7be0eba091f868bb09fee">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1ab0e9b37f0d828e42ad5117706cdce">end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an iterator to the end of the symbol table. <a href="#ad1ab0e9b37f0d828e42ad5117706cdce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aaefca086fa2daa5991fb7d6bcc4f44a9">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4a219a2ed4389d522d9af7d849c035c">end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a <a href="#aaefca086fa2daa5991fb7d6bcc4f44a9">const_iterator</a> to the end of the symbol table. <a href="#ac4a219a2ed4389d522d9af7d849c035c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Mutators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a0974858ce658c475882ec1f6082145de">ValueName</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6271475a5a567406c3600c9a3799d0b5">makeUniqueName</a> (Value *V, SmallString&lt; 256 &gt; &amp;UniqueName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c39d5be6f523b9811f7634b0979d1f1">reinsertValue</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method adds the provided value <span class="doxyComputerOutput">N</span> to the symbol table. <a href="#a2c39d5be6f523b9811f7634b0979d1f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a0974858ce658c475882ec1f6082145de">ValueName</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b148e13ea071a2e4a3f4385851381a3">createValueName</a> (StringRef Name, Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createValueName - This method attempts to create a value name and insert it into the symbol table with the specified name. <a href="#a3b148e13ea071a2e4a3f4385851381a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4ecee5790193c2d18a9fc6055f7ec7d">removeValueName</a> (ValueName *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method removes a value from the symbol table. <a href="#af4ecee5790193c2d18a9fc6055f7ec7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class provides a symbol table of name/value pairs.</p>


<p>It is essentially a std::map&lt;std::string,Value*&gt; but has a controlled interface provided by LLVM as well as ensuring uniqueness of names.</p>


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>


<div class="doxySectionDef">

## Friends

### SymbolTableListTraits&lt; Argument &gt; {#ad70c1404a34a6688de61d1b8f4bfbda7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/symboltablelisttraits">SymbolTableListTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

### SymbolTableListTraits&lt; BasicBlock &gt; {#a11c7b04e5390fe7e163bf1ad039c757a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/symboltablelisttraits">SymbolTableListTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

### SymbolTableListTraits&lt; Function &gt; {#a660ff91040216811606e493f778936bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/symboltablelisttraits">SymbolTableListTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

### SymbolTableListTraits&lt; GlobalAlias &gt; {#a1989fb0fd1aa69b4142d1e911b92ba50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/symboltablelisttraits">SymbolTableListTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

### SymbolTableListTraits&lt; GlobalIFunc &gt; {#aa096b32e127043e3d34a2eec20637a71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/symboltablelisttraits">SymbolTableListTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalifunc">GlobalIFunc</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

### SymbolTableListTraits&lt; GlobalVariable &gt; {#acdb1b42eb1df67c3f9354c0607adeada}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/symboltablelisttraits">SymbolTableListTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

### SymbolTableListTraits&lt; Instruction, ilist\_iterator\_bits&lt; true &gt;, ilist\_parent&lt; BasicBlock &gt; &gt; {#a4a1c602c4fb0faa383cdd33bdaee7c58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/symboltablelisttraits">SymbolTableListTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-iterator-bits">ilist_iterator_bits</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;, <a href="/web-llvm/docs/api/structs/llvm/ilist-parent">ilist_parent</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt; &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

### Value {#aeceedf6e1a7d48a588516ce2b1983d6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/value">Value</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>


<p>Reference <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>


<p>Referenced by <a href="#a7886be195af2a1ec188748a1997b8d75">lookup</a> and <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Types

### const\_iterator {#aaefca086fa2daa5991fb7d6bcc4f44a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ValueSymbolTable::const_iterator =  ValueMap::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A <a href="#aaefca086fa2daa5991fb7d6bcc4f44a9">const_iterator</a> over a <a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a>.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

### iterator {#af70ae50ad5c7be0eba091f868bb09fee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ValueSymbolTable::iterator =  ValueMap::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An iterator over a <a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a>.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

### ValueMap {#ae96e8369c74046a10061c77671589543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ValueSymbolTable::ValueMap =  StringMap&lt;Value*&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A mapping of names to values.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Internal Data

### LastUnique {#a543d557dd1892334e78bd65b90e79dec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ValueSymbolTable::LastUnique = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Counter for tracking unique names.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

### MaxNameSize {#a16b6e6dd47521f61945f2ff27b2b959c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ValueSymbolTable::MaxNameSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum size for each name.</p>


<p>If the limit is exceeded, the name is capped.</p>


<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

### vmap {#a35b9b47b5a35c6d166cf34be87cffebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueMap llvm::ValueSymbolTable::vmap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The map that holds the symbol table.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Constructors

### \~ValueSymbolTable {#ada82898afe6c8ab2d19db4bb28d7d464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueSymbolTable::~ValueSymbolTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/valuesymboltable-cpp">ValueSymbolTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>.</p>

</div>
</div>

### ValueSymbolTable {#a0d010dcf5742b976fd1c8a9b3fb84046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueSymbolTable::ValueSymbolTable (int MaxNameSize=-1)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Accessors

### dump {#a4e9cc2b295b104ebd2c7d5b4d7960f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void ValueSymbolTable::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function can be used from the debugger to display the content of the symbol table while debugging.</p>


<p>Print out symbol table on stderr</p>


<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>, definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/valuesymboltable-cpp">ValueSymbolTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

### empty {#a0b012ea30457425f177507538b3edd45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueSymbolTable::empty ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true iff the symbol table is empty Determine if the symbol table is empty</p></dd>
</dl>


<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

### lookup {#a7886be195af2a1ec188748a1997b8d75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::ValueSymbolTable::lookup (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>This method finds the value with the given <span class="doxyComputerOutput">Name</span> in the the symbol table.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the value associated with the <span class="doxyComputerOutput">Name</span> Lookup a named <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p></dd>
</dl>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>


<p>Reference <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a35017776f5e9dd9dbc7f71d56a77135a">parseIRValue</a>.</p>

</div>
</div>

### size {#af3e8a250086a4717b288c738c722919f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ValueSymbolTable::size ()</td>
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

<p>The number of name/type pairs is returned.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Iteration

### begin {#af4c7a859b6d520a4a696b6f7dfc0c37e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::ValueSymbolTable::begin ()</td>
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

<p>Get an iterator that from the beginning of the symbol table.</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

### begin {#a67f15de6368d915a69d31f9d18e5ce6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::ValueSymbolTable::begin ()</td>
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

<p>Get a <a href="#aaefca086fa2daa5991fb7d6bcc4f44a9">const_iterator</a> that from the beginning of the symbol table.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

### end {#ad1ab0e9b37f0d828e42ad5117706cdce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::ValueSymbolTable::end ()</td>
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

<p>Get an iterator to the end of the symbol table.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

### end {#ac4a219a2ed4389d522d9af7d849c035c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::ValueSymbolTable::end ()</td>
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

<p>Get a <a href="#aaefca086fa2daa5991fb7d6bcc4f44a9">const_iterator</a> to the end of the symbol table.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Mutators

### createValueName {#a3b148e13ea071a2e4a3f4385851381a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueName * ValueSymbolTable::createValueName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>createValueName - This method attempts to create a value name and insert it into the symbol table with the specified name.</p>


<p>If it conflicts, it auto-renames the name and returns that instead.</p>


<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/valuesymboltable-cpp">ValueSymbolTable.cpp</a>.</p>

</div>
</div>

### makeUniqueName {#a6271475a5a567406c3600c9a3799d0b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueName * ValueSymbolTable::makeUniqueName (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 256 &gt; &amp; UniqueName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/valuesymboltable-cpp">ValueSymbolTable.cpp</a>.</p>

</div>
</div>

### reinsertValue {#a2c39d5be6f523b9811f7634b0979d1f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueSymbolTable::reinsertValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method adds the provided value <span class="doxyComputerOutput">N</span> to the symbol table.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> must have a name which is used to place the value in the symbol table. If the inserted name conflicts, this renames the value. Add a named value to the symbol table</p>


<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/valuesymboltable-cpp">ValueSymbolTable.cpp</a>.</p>

</div>
</div>

### removeValueName {#af4ecee5790193c2d18a9fc6055f7ec7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueSymbolTable::removeValueName (<a href="/web-llvm/docs/api/namespaces/llvm/#a0974858ce658c475882ec1f6082145de">ValueName</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method removes a value from the symbol table.</p>


<p>It leaves the <a href="/web-llvm/docs/api/namespaces/llvm/#a0974858ce658c475882ec1f6082145de">ValueName</a> attached to the value, but it is no longer inserted in the symtab.</p>


<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/valuesymboltable-cpp">ValueSymbolTable.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">ValueSymbolTable.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/valuesymboltable-cpp">ValueSymbolTable.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
