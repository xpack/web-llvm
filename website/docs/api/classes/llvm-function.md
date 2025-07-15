---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/function
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Function` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::Function { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node&lt;T, Options&gt;</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e3bfa03a4f2a697d3002154c48f2c7a">BasicBlockListType</a> = <a href="/web-llvm/docs/api/classes/llvm/symboltablelist">SymbolTableList</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19595c245bd2e3eefa93ce22db5ad15f">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">BasicBlockListType::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e04cb9e3897c6b3b5ae22349695fa69">const_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a3a5c6f429b19022105ee49f587c7ed04">BasicBlockListType::const_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c9f2f058966db1f8ca270398bda8362">arg_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> *</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8dcf6aa51ec5887c9c52c148535c021">const_arg_iterator</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> *</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a410341838f0c4b80b5beddec4719782f">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bits from GlobalObject::GlobalObjectSubclassData. <a href="#a410341838f0c4b80b5beddec4719782f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ProfileCountType { <a href="#a438d2f246b76817114ade2a005a6bcab">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d6fd92c5a6d2931b039e6405475322f">TargetLibraryInfoImpl</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BB_t, class BB_i_t, class BI_t, class II_t&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abe80de7eff41fd5161782104539568c1">InstIterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af18ee185be80bb60b1c47f8d0ab78711">llvm::SymbolTableListTraits&lt; llvm::BasicBlock &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e2ab800c636979b14ada45510861743">llvm::ilist_node_with_parent&lt; llvm::BasicBlock, llvm::Function &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f65cbf6fd290b525f04667d9a952ae">BasicBlock::setParent</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c3fa281c85f015ea3ba20c7efc41714">BasicBlock::removeFromParent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iplist">iplist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt;<a href="#a19595c245bd2e3eefa93ce22db5ad15f">::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8d611ee05eb26761a65e560e1481464">BasicBlock::eraseFromParent</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e09342bb3ccc55b803067615284552">Function</a> (const Function &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a1f910efbc2a5d9a81b5bab38f0331a">Function</a> (FunctionType *Ty, LinkageTypes Linkage, unsigned AddrSpace, const Twine &amp;N="", Module *M=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> ctor - If the (optional) <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> argument is specified, the function is automatically inserted into the end of the function list for the module. <a href="#a9a1f910efbc2a5d9a81b5bab38f0331a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b03f7cf0b75d16edebdda1dee1db6fd">~Function</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc545a99211445342e8907df8f841e6f">operator=</a> (const Function &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad93d1f4325f9ecee231d5f62adf8d74e">hasLazyArguments</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasLazyArguments/CheckLazyArguments - The argument list of a function is built on demand, so that the list isn't allocated until the first client needs it. <a href="#ad93d1f4325f9ecee231d5f62adf8d74e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e97db06807fee808c3db2f33012556">convertToNewDbgValues</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e506a1fad2bb34972806851b52478e1">convertFromNewDbgValues</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd4e7f960071723676ea5cc199a49df6">setIsNewDbgInfoFormat</a> (bool NewVal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f1ae275a74d61d2b50c7be97490ec4b">setNewDbgInfoFormatFlag</a> (bool NewVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8743c58384e11cb6228f6f871304ad35">getFunction</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec04f4ee74f001679174332506c0cebc">DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a> (Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af67f86066ad1891d424553b352dfa821">getInstructionCount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of non-debug IR instructions in this function. <a href="#af67f86066ad1891d424553b352dfa821">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21075305f0e463b24aafc2fb99514ace">getFunctionType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> for me. <a href="#a21075305f0e463b24aafc2fb99514ace">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdd05db170cbfee8a0fcbc047b8504e5">getReturnType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the type of the ret val. <a href="#acdd05db170cbfee8a0fcbc047b8504e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fffac2512fe651f0d5e37e27f5bd51c">getContext</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getContext - Return a reference to the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> associated with this function. <a href="#a9fffac2512fe651f0d5e37e27f5bd51c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3275c50993afaf4fdd723640c2c3ca0f">getDataLayout</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the data layout of the module this function belongs to. <a href="#a3275c50993afaf4fdd723640c2c3ca0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af457a58a84b500d44feb7b699aa43ec1">isVarArg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isVarArg - Return true if this function takes a variable number of arguments. <a href="#af457a58a84b500d44feb7b699aa43ec1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d8ab5e89ddab6695d95b3857f9b8c06">isMaterializable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59f288adc3400b81160f04f674b7f6bf">setIsMaterializable</a> (bool V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d0a7baab8d078065b2de10e3460892a">getIntrinsicID</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getIntrinsicID - This method returns the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> number of the specified function, or <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a35fedf4db6d756bd82501607f93c1e79aab5fb650050f184fa7c19c26abde5226">Intrinsic::not_intrinsic</a> if the function is not an intrinsic, or if the pointer is null. <a href="#a4d0a7baab8d078065b2de10e3460892a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a900a32da3983469187b1848189681705">isIntrinsic</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isIntrinsic - Returns true if the function's name starts with "llvm.". <a href="#a900a32da3983469187b1848189681705">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6367bc9050fb76e2d686108abcf5a212">isTargetIntrinsic</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isTargetIntrinsic - Returns true if this function is an intrinsic and the intrinsic is specific to a certain target. <a href="#a6367bc9050fb76e2d686108abcf5a212">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d7c400bd90654692d8137528c0ef52f">isConstrainedFPIntrinsic</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the function is one of the "Constrained Floating-Point
Intrinsics". <a href="#a4d7c400bd90654692d8137528c0ef52f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab38fb46aad998f695de33966a62b4f66">updateAfterNameChange</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update internal caches that depend on the function name (such as the intrinsic <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> and libcall cache). <a href="#ab38fb46aad998f695de33966a62b4f66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f494edc0a569c7fc9ff4181243be1ed">getCallingConv</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a5f494edc0a569c7fc9ff4181243be1ed">getCallingConv()</a>/setCallingConv(CC) - These method get and set the calling convention of this function. <a href="#a5f494edc0a569c7fc9ff4181243be1ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6db8746934e6feae3649a8709fce3cc">setCallingConv</a> (CallingConv::ID CC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefb3254278b224f10e5b966cea653e01">setEntryCount</a> (ProfileCount Count, const DenseSet&lt; GlobalValue::GUID &gt; *Imports=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the entry count for this function. <a href="#aefb3254278b224f10e5b966cea653e01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a758c8ee1f227a4958e0e6820ccff5ff3">setEntryCount</a> (uint64_t Count, ProfileCountType Type=PCT_Real, const DenseSet&lt; GlobalValue::GUID &gt; *Imports=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A convenience wrapper for setting entry count. <a href="#a758c8ee1f227a4958e0e6820ccff5ff3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/function/profilecount">ProfileCount</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac154f7a85081237665c89b83bbd3d7e2">getEntryCount</a> (bool AllowSynthetic=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the entry count for this function. <a href="#ac154f7a85081237665c89b83bbd3d7e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9084ce2576fad285c1c0dc1e165dd4b6">hasProfileData</a> (bool IncludeSynthetic=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the function is annotated with profile data. <a href="#a9084ce2576fad285c1c0dc1e165dd4b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a786802ed087c3a22a667532d2930087a">getImportGUIDs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the set of GUIDs that needs to be imported to the function for sample PGO, to enable the same inlines as the profiled optimized binary. <a href="#a786802ed087c3a22a667532d2930087a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60c157d9fa21a214f5ce40cab0514b85">setSectionPrefix</a> (StringRef Prefix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the section prefix for this function. <a href="#a60c157d9fa21a214f5ce40cab0514b85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11ab3c8bd6ff4445d7cb45a62806353b">getSectionPrefix</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the section prefix for this function. <a href="#a11ab3c8bd6ff4445d7cb45a62806353b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e63b88c979e47ac7da57890a45bd2c2">hasGC</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasGC/getGC/setGC/clearGC - The name of the garbage collection algorithm to use during code generation. <a href="#a5e63b88c979e47ac7da57890a45bd2c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa180549a789e99a98e599e8e183c4773">getGC</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a455032eb7bfb230b908159d9b1c1fbf1">setGC</a> (std::string Str)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3ba7e58bebd9bbadb647fe4691a7e6e">clearGC</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">AttributeList</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7477aafbbe989ad35b96fac186d8e9fd">getAttributes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute list for this <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>. <a href="#a7477aafbbe989ad35b96fac186d8e9fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e4c6c67f4b2528b5648299db4a86926">setAttributes</a> (AttributeList Attrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the attribute list for this <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>. <a href="#a9e4c6c67f4b2528b5648299db4a86926">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9603b8b801fc36a29ea533b19c1baca">addAttributeAtIndex</a> (unsigned i, Attribute Attr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>adds the attribute to the list of attributes. <a href="#af9603b8b801fc36a29ea533b19c1baca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01875e4204852069dd4b7938cab4140b">addFnAttr</a> (Attribute::AttrKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add function attributes to this function. <a href="#a01875e4204852069dd4b7938cab4140b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7b919df259dce5480774e656791c079">addFnAttr</a> (StringRef Kind, StringRef Val=StringRef())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add function attributes to this function. <a href="#ae7b919df259dce5480774e656791c079">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2902ff168f1dbd817ebf6bbb9c468e5a">addFnAttr</a> (Attribute Attr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add function attributes to this function. <a href="#a2902ff168f1dbd817ebf6bbb9c468e5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34cf0c64f57241d690ee7009afc629b1">addFnAttrs</a> (const AttrBuilder &amp;Attrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add function attributes to this function. <a href="#a34cf0c64f57241d690ee7009afc629b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6afca945952abdd7be262d5fe5ddad77">addRetAttr</a> (Attribute::AttrKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add return value attributes to this function. <a href="#a6afca945952abdd7be262d5fe5ddad77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2732a9861a5ff74a3468a1b53d700bb">addRetAttr</a> (Attribute Attr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add return value attributes to this function. <a href="#ae2732a9861a5ff74a3468a1b53d700bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cccf168c794d734b0377a0c61a89909">addRetAttrs</a> (const AttrBuilder &amp;Attrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add return value attributes to this function. <a href="#a0cccf168c794d734b0377a0c61a89909">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5087b607af833220d9ebab0c88c83c1">addParamAttr</a> (unsigned ArgNo, Attribute::AttrKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>adds the attribute to the list of attributes for the given arg. <a href="#aa5087b607af833220d9ebab0c88c83c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eb05d774eaaab1b7ad6cee10e3713e2">addParamAttr</a> (unsigned ArgNo, Attribute Attr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>adds the attribute to the list of attributes for the given arg. <a href="#a6eb05d774eaaab1b7ad6cee10e3713e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a092beb46ecce99e6b39628ee92ccd95a">addParamAttrs</a> (unsigned ArgNo, const AttrBuilder &amp;Attrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>adds the attributes to the list of attributes for the given arg. <a href="#a092beb46ecce99e6b39628ee92ccd95a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a838fded9375bdf5078b6853449ee44f5">removeAttributeAtIndex</a> (unsigned i, Attribute::AttrKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removes the attribute from the list of attributes. <a href="#a838fded9375bdf5078b6853449ee44f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aced83766bacb03989c05422bfc341449">removeAttributeAtIndex</a> (unsigned i, StringRef Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removes the attribute from the list of attributes. <a href="#aced83766bacb03989c05422bfc341449">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8baad1df39d45576fe7a642b49f0e6dc">removeFnAttr</a> (Attribute::AttrKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove function attributes from this function. <a href="#a8baad1df39d45576fe7a642b49f0e6dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6b3606d6657d553ba9065fad0e333f0">removeFnAttr</a> (StringRef Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove function attribute from this function. <a href="#af6b3606d6657d553ba9065fad0e333f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6875de46fcb2a74ca95bce67edd215a0">removeFnAttrs</a> (const AttributeMask &amp;Attrs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09ac042b7e543197d4911a0436d46349">removeRetAttr</a> (Attribute::AttrKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removes the attribute from the return value list of attributes. <a href="#a09ac042b7e543197d4911a0436d46349">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5574f481ddb505fe7c2b90c46e22db33">removeRetAttr</a> (StringRef Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removes the attribute from the return value list of attributes. <a href="#a5574f481ddb505fe7c2b90c46e22db33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb3914db988819782f3a6317d2e2b925">removeRetAttrs</a> (const AttributeMask &amp;Attrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removes the attributes from the return value list of attributes. <a href="#acb3914db988819782f3a6317d2e2b925">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bb42b4d714a18ee81315cfb6ae1ed13">removeParamAttr</a> (unsigned ArgNo, Attribute::AttrKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removes the attribute from the list of attributes. <a href="#a1bb42b4d714a18ee81315cfb6ae1ed13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a948ae5afe80982c85442c19b2855cb35">removeParamAttr</a> (unsigned ArgNo, StringRef Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removes the attribute from the list of attributes. <a href="#a948ae5afe80982c85442c19b2855cb35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55c554858450f67ef20c4abbc7e1ed19">removeParamAttrs</a> (unsigned ArgNo, const AttributeMask &amp;Attrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removes the attribute from the list of attributes. <a href="#a55c554858450f67ef20c4abbc7e1ed19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb28a4deafe2954b0534cc6399ce518b">hasFnAttribute</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the function has the attribute. <a href="#afb28a4deafe2954b0534cc6399ce518b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abed260ec7cc3f660000905763dbb4f90">hasFnAttribute</a> (StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the function has the attribute. <a href="#abed260ec7cc3f660000905763dbb4f90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdd453734de0c5ec547939f9bb475190">hasRetAttribute</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>check if an attribute is in the list of attributes for the return value. <a href="#abdd453734de0c5ec547939f9bb475190">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c8e58da4c28ac380a697fcb2f1ddaa3">hasParamAttribute</a> (unsigned ArgNo, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>check if an attributes is in the list of attributes. <a href="#a5c8e58da4c28ac380a697fcb2f1ddaa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc02f5ba395bfe8a3a81815d37621494">hasParamAttribute</a> (unsigned ArgNo, StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if an attribute is in the list of attributes. <a href="#afc02f5ba395bfe8a3a81815d37621494">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae420319b63092fad3cff17a964ae3c90">getAttributeAtIndex</a> (unsigned i, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>gets the attribute from the list of attributes. <a href="#ae420319b63092fad3cff17a964ae3c90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e819417d324183edc1fa9d4aaa54431">getAttributeAtIndex</a> (unsigned i, StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>gets the attribute from the list of attributes. <a href="#a2e819417d324183edc1fa9d4aaa54431">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d53cff701a33669d57f1a55cb4b84cc">hasAttributeAtIndex</a> (unsigned Idx, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if attribute of the given kind is set at the given index. <a href="#a5d53cff701a33669d57f1a55cb4b84cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c319db4fe05c27cfe55bd133a87414d">getFnAttribute</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute for the given attribute kind. <a href="#a4c319db4fe05c27cfe55bd133a87414d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacaa0c150cd66194d15d1bdd389009e3">getFnAttribute</a> (StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute for the given attribute kind. <a href="#aacaa0c150cd66194d15d1bdd389009e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afff5709a997763240c888e86db09e4e2">getRetAttribute</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute for the given attribute kind for the return value. <a href="#afff5709a997763240c888e86db09e4e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c866d3504a1e0717c8152a590bd6203">getFnAttributeAsParsedInteger</a> (StringRef Kind, uint64_t Default=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a string attribute <span class="doxyComputerOutput">Kind</span>, parse attribute as an integer. <a href="#a4c866d3504a1e0717c8152a590bd6203">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28eb38953dee4718455ab384f21f638c">getParamAttribute</a> (unsigned ArgNo, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>gets the specified attribute from the list of attributes. <a href="#a28eb38953dee4718455ab384f21f638c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3494b54c5cae8ae5d9c3008238963e09">getFnStackAlign</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the stack alignment for the function. <a href="#a3494b54c5cae8ae5d9c3008238963e09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29db1a6c4a106d1720101b8d1adf9387">hasStackProtectorFnAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the function has ssp, sspstrong, or sspreq fn attrs. <a href="#a29db1a6c4a106d1720101b8d1adf9387">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af49f352a100314919e2603afe4d87cff">addDereferenceableParamAttr</a> (unsigned ArgNo, uint64_t Bytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>adds the dereferenceable attribute to the list of attributes for the given arg. <a href="#af49f352a100314919e2603afe4d87cff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f040402288effcbdffb4f7c9748f067">addDereferenceableOrNullParamAttr</a> (unsigned ArgNo, uint64_t Bytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>adds the dereferenceable_or_null attribute to the list of attributes for the given arg. <a href="#a8f040402288effcbdffb4f7c9748f067">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93469502fd939d1f842d69f813f38d33">addRangeRetAttr</a> (const ConstantRange &amp;CR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>adds the range attribute to the list of attributes for the return value. <a href="#a93469502fd939d1f842d69f813f38d33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97fb0bcc88f78900c3d4780d963540e0">getParamAlign</a> (unsigned ArgNo) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac667b0a43e49f4e4ae4e1d558f37df8c">getParamStackAlign</a> (unsigned ArgNo) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a669daedc0f098c6b21ad743df19e1d73">getParamByValType</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the byval type for a parameter. <a href="#a669daedc0f098c6b21ad743df19e1d73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb2fec27f03901fdf633971423877345">getParamStructRetType</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the sret type for a parameter. <a href="#aeb2fec27f03901fdf633971423877345">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1f37b7f4032fef91001845b5f506e66">getParamInAllocaType</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the inalloca type for a parameter. <a href="#ab1f37b7f4032fef91001845b5f506e66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80155b6dbeda6df7d2c106b89fe1027e">getParamByRefType</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the byref type for a parameter. <a href="#a80155b6dbeda6df7d2c106b89fe1027e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e292c5881887f1c1bfb54bcda262b32">getParamPreallocatedType</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the preallocated type for a parameter. <a href="#a9e292c5881887f1c1bfb54bcda262b32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a457ddc9964340847b216e105b8eb32">getParamDereferenceableBytes</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the number of dereferenceable bytes for a parameter. <a href="#a5a457ddc9964340847b216e105b8eb32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b1396e0135cc83920828f81ce53d71d">getParamDereferenceableOrNullBytes</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the number of dereferenceable_or_null bytes for a parameter. <a href="#a8b1396e0135cc83920828f81ce53d71d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67810dc8301ddb65ca4ce52d4a446af1">getParamNoFPClass</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the nofpclass attribute for a parameter. <a href="#a67810dc8301ddb65ca4ce52d4a446af1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f6ec3f2263a0ed9418c0968cf7c265e">isPresplitCoroutine</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the function is presplit coroutine. <a href="#a9f6ec3f2263a0ed9418c0968cf7c265e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95f94f1901598a30b2644932e09320ab">setPresplitCoroutine</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2c99fa1630820513c88980dd6b5661a">setSplittedCoroutine</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac02f761bf4c83638d32b8459c82116bb">isCoroOnlyDestroyWhenComplete</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a059fada19030e5930c4b511d4fe6a766">setCoroDestroyOnlyWhenComplete</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a44ad2b29af9ebe3d12a99843a7594757">MemoryEffects</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a530ec44ae594c349ccac0b065735a001">getMemoryEffects</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1867b9b6cef5ee12741f0b379ec8800">setMemoryEffects</a> (MemoryEffects ME)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa701465fb174e27e3a89695762970997">doesNotAccessMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the function does not access memory. <a href="#aa701465fb174e27e3a89695762970997">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b53b6573f46ab43c654ef9a295a652c">setDoesNotAccessMemory</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7736e14235372b75b72e119f852c280">onlyReadsMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the function does not access or only reads memory. <a href="#af7736e14235372b75b72e119f852c280">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63062a49613cb771453e2dc857343a39">setOnlyReadsMemory</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe064a7e0978b5f7705119abf53c0ca3">onlyWritesMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the function does not access or only writes memory. <a href="#abe064a7e0978b5f7705119abf53c0ca3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f930a611c74d4a00af794a57bae9d84">setOnlyWritesMemory</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9f7a2cf04e469adef7fe1aa1cf15d9a">onlyAccessesArgMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the call can access memmory only using pointers based on its arguments. <a href="#ad9f7a2cf04e469adef7fe1aa1cf15d9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d7f7a04bd6707f8b9c9c8a1f98d757f">setOnlyAccessesArgMemory</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3a2060955a1335598943ea1dcc71ac7">onlyAccessesInaccessibleMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the function may only access memory that is inaccessible from the IR. <a href="#ac3a2060955a1335598943ea1dcc71ac7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54b35f9b5f699da7de2cf9feaae4ddfc">setOnlyAccessesInaccessibleMemory</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13d92306a2df12850752a8415741b5c6">onlyAccessesInaccessibleMemOrArgMem</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the function may only access memory that is either inaccessible from the IR or pointed to by its arguments. <a href="#a13d92306a2df12850752a8415741b5c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8042a91752d4b2ca165cc35250d0f8f">setOnlyAccessesInaccessibleMemOrArgMem</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8ef748e928424955da3d1f6676b25d9">doesNotReturn</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the function cannot return. <a href="#ab8ef748e928424955da3d1f6676b25d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57d6d47f3d0fe19f5a9bc1626630d4b0">setDoesNotReturn</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58e9603fcbb784bee436392db60d93f1">doesNoCfCheck</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the function should not perform indirect branch tracking. <a href="#a58e9603fcbb784bee436392db60d93f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81f38aca859ffeda166f8c385f7d55a5">doesNotThrow</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the function cannot unwind. <a href="#a81f38aca859ffeda166f8c385f7d55a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd978c6f74e279603d47b940f60f1f24">setDoesNotThrow</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a432063a2bc02df1d1c93957c644e966c">cannotDuplicate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the call cannot be duplicated. <a href="#a432063a2bc02df1d1c93957c644e966c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dca1751288896161d502571fecf2ae3">setCannotDuplicate</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a049de2366079104e70f0c3451b09aebf">isConvergent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the call is convergent. <a href="#a049de2366079104e70f0c3451b09aebf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95f8eff531b9ed5d85cdc2f8d7c3e5c6">setConvergent</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaac428519a2771aeec63054d47800849">setNotConvergent</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cbc3ad9ede9ff8b2012e46bfb997e76">isSpeculatable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the call has sideeffects. <a href="#a5cbc3ad9ede9ff8b2012e46bfb997e76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99a24ef326b23786e0e0b7f7c02d45a4">setSpeculatable</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf2ec1eb99cc826eea1a7dd8a8ea570a">doesNotFreeMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the call might deallocate memory. <a href="#aaf2ec1eb99cc826eea1a7dd8a8ea570a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb7e3c73013c2827ccd486e888953875">setDoesNotFreeMemory</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a808de46fdb41ab44e0711fc06eda13ca">hasNoSync</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the call can synchroize with other threads. <a href="#a808de46fdb41ab44e0711fc06eda13ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac972de5ac0d70f5bd4ff3cf958911e94">setNoSync</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e5c42dc883d0deb41a668301cd5ac72">doesNotRecurse</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the function is known not to recurse, directly or indirectly. <a href="#a4e5c42dc883d0deb41a668301cd5ac72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecb901181edae6cd518104e05ccb6f78">setDoesNotRecurse</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41ebfca5fde82030f9d559dc34082ef6">mustProgress</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the function is required to make forward progress. <a href="#a41ebfca5fde82030f9d559dc34082ef6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7915406c3f283ae294f55c2c9dc49c1">setMustProgress</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48e10a01350fafd3df5828061787a97e">willReturn</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the function will return. <a href="#a48e10a01350fafd3df5828061787a97e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a460362250160f652f82d5de1fc5379d2">setWillReturn</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a6cdf47ba1fa5831d7c2897bc3aed77b8">UWTableKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e181b32a135b15eb712e81ffe52ea50">getUWTableKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get what kind of unwind table entry to generate for this function. <a href="#a7e181b32a135b15eb712e81ffe52ea50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acabf5ba443b4e5327f547ae8fc04a98c">hasUWTable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the ABI mandates (or the user requested) that this function be in a unwind table. <a href="#acabf5ba443b4e5327f547ae8fc04a98c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a383eea189e7af487299e904c0b5fcc">setUWTableKind</a> (UWTableKind K)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7332117b148c3f93c1d7e58306ee748">needsUnwindTableEntry</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this function needs an unwind table. <a href="#ad7332117b148c3f93c1d7e58306ee748">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa73c6ba4efcd37a9afc738793d50b2c9">hasStructRetAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the function returns a structure through first or second pointer argument. <a href="#aa73c6ba4efcd37a9afc738793d50b2c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a427fcc6fd56f42086a2c91c0dce5e425">returnDoesNotAlias</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the parameter or return value is marked with NoAlias attribute. <a href="#a427fcc6fd56f42086a2c91c0dce5e425">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a698b49a3ec754ef00d2c27d146daa5e2">setReturnDoesNotAlias</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c38a8cc0a38636c95bd2826de9d72d4">hasOptNone</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do not optimize this function (-O0). <a href="#a9c38a8cc0a38636c95bd2826de9d72d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a548cfb9440f36ba67fc5566b8e967fc6">hasMinSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize this function for minimum size (-Oz). <a href="#a548cfb9440f36ba67fc5566b8e967fc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c455e007178a24dfb18ac0e200ea02c">hasOptSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize this function for size (-Os) or minimum size (-Oz). <a href="#a1c455e007178a24dfb18ac0e200ea02c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf03062dde511bcc74b5d01b0a2b5736">getDenormalMode</a> (const fltSemantics &amp;FPType) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the denormal handling type for the default rounding mode of the function. <a href="#aaf03062dde511bcc74b5d01b0a2b5736">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68e9896416f00cf96b7bcde3afd54e21">getDenormalModeRaw</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the representational value of "denormal-fp-math". <a href="#a68e9896416f00cf96b7bcde3afd54e21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d0575b2a84c3f9fddb78d07721a6535">getDenormalModeF32Raw</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the representational value of "denormal-fp-math-f32". <a href="#a6d0575b2a84c3f9fddb78d07721a6535">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd7894f118b1d1636cff1b8de5f424e5">copyAttributesFrom</a> (const Function *Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>copyAttributesFrom - copy all additional attributes (those not needed to create a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>) from the <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Src to this one. <a href="#afd7894f118b1d1636cff1b8de5f424e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0020cbf9c3df714558a9b20a6267bd29">deleteBody</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>deleteBody - This method deletes the body of the function, and converts the linkage to external. <a href="#a0020cbf9c3df714558a9b20a6267bd29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29e0a562beb4b5d20eb0c426b363ceed">removeFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeFromParent - This method unlinks 'this' from the containing module, but does not delete it. <a href="#a29e0a562beb4b5d20eb0c426b363ceed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8969dec86d24dd579f8ecc963e1dc8b4">eraseFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>eraseFromParent - This method unlinks 'this' from the containing module and deletes it. <a href="#a8969dec86d24dd579f8ecc963e1dc8b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bd0472865626998cee18ae8c6cf5120">stealArgumentListFrom</a> (Function &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Steal arguments from another function. <a href="#a9bd0472865626998cee18ae8c6cf5120">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a19595c245bd2e3eefa93ce22db5ad15f">Function::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaab8110aafc070c83bc701b13d2260df">insert</a> (Function::iterator Position, BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert <span class="doxyComputerOutput">BB</span> in the basic block list at <span class="doxyComputerOutput">Position</span>. <a href="#aaab8110aafc070c83bc701b13d2260df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14b02db913559954c4d38ed70cd66f59">splice</a> (Function::iterator ToIt, Function *FromF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfer all blocks from <span class="doxyComputerOutput">FromF</span> to this function at <span class="doxyComputerOutput">ToIt</span>. <a href="#a14b02db913559954c4d38ed70cd66f59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d3f9f2b13a4a6fad661ec70bd8828ab">splice</a> (Function::iterator ToIt, Function *FromF, Function::iterator FromIt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfer one <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> from <span class="doxyComputerOutput">FromF</span> at <span class="doxyComputerOutput">FromIt</span> to this function at <span class="doxyComputerOutput">ToIt</span>. <a href="#a1d3f9f2b13a4a6fad661ec70bd8828ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a193eeb8fc9ba64befe766a35f7a5689f">splice</a> (Function::iterator ToIt, Function *FromF, Function::iterator FromBeginIt, Function::iterator FromEndIt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfer a range of basic blocks that belong to <span class="doxyComputerOutput">FromF</span> from <span class="doxyComputerOutput">FromBeginIt</span> to <span class="doxyComputerOutput">FromEndIt</span>, to this function at <span class="doxyComputerOutput">ToIt</span>. <a href="#a193eeb8fc9ba64befe766a35f7a5689f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a19595c245bd2e3eefa93ce22db5ad15f">Function::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add1b62fd0110c8c97673ed9a66603f05">erase</a> (Function::iterator FromIt, Function::iterator ToIt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erases a range of BasicBlocks from <span class="doxyComputerOutput">FromIt</span> to (not including) <span class="doxyComputerOutput">ToIt</span>. <a href="#add1b62fd0110c8c97673ed9a66603f05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a169f0c26ef46161741fdd120a806f853">getEntryBlock</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0da3ad33bda3df0fa6c10d91d3815626">getEntryBlock</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuesymboltable">ValueSymbolTable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b03fcd02236ef6a4a1e59790bdca48a">getValueSymbolTable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSymbolTable() - Return the symbol table if any, otherwise nullptr. <a href="#a9b03fcd02236ef6a4a1e59790bdca48a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuesymboltable">ValueSymbolTable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a033f8a22965054cb1a03fa98b9d61677">getValueSymbolTable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4528b445a4b11cf13675dcaf20c4f27a">getMaxBlockNumber</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a value larger than the largest block number. <a href="#a4528b445a4b11cf13675dcaf20c4f27a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a379698f9e29cc98012a7bbc55984ffda">renumberBlocks</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Renumber basic blocks into a dense value range starting from 0. <a href="#a379698f9e29cc98012a7bbc55984ffda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79ece1e904cf5819d13d081101c54f4e">getBlockNumberEpoch</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the "epoch" of current block numbers. <a href="#a79ece1e904cf5819d13d081101c54f4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a19595c245bd2e3eefa93ce22db5ad15f">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88a5e60837674780a9d812d661897ac5">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7e04cb9e3897c6b3b5ae22349695fa69">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a944c299cf8bcabbb0f81d71c182068f9">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a19595c245bd2e3eefa93ce22db5ad15f">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4ca2261b8b901e415fda7feac5051ea">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7e04cb9e3897c6b3b5ae22349695fa69">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a84e4980b5bf8e647cdd1b27ca23e6f">end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a969eb757b1e43b455d4a8d0f603e695b">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d8eb3054fd49a89ff41bc22a48f87e7">empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ec0b920bf30d0e15bace383192691da">front</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf30a45c2a2e88a614f4ff435aafceaf">front</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43b79a254fba6ce00adf5b963382a0a4">back</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa08597bdb94f7c8409da1016e4d3900e">back</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6baa801e4aea800984e760d5460662f">arg_size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ac1213bb14caae3108345d40069bfb1">arg_empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a0f6312963ee6fb0969243607174949">hasPersonalityFn</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this function has a personality function. <a href="#a6a0f6312963ee6fb0969243607174949">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f77e4e800ba4dffd63e8ddb330062aa">getPersonalityFn</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the personality function associated with this function. <a href="#a6f77e4e800ba4dffd63e8ddb330062aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f9ba62511c44dd991c6cd7485098d15">setPersonalityFn</a> (Constant *Fn)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68f94d59950d5fa55b818dca8ea59579">hasPrefixData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this function has prefix data. <a href="#a68f94d59950d5fa55b818dca8ea59579">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae24606acf52aa6444bfd2b4848a1ae27">getPrefixData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the prefix data associated with this function. <a href="#ae24606acf52aa6444bfd2b4848a1ae27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2960cc22992967e68a160de69e1ad86e">setPrefixData</a> (Constant *PrefixData)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8c01344089090a372ee86f62c07f2bb">hasPrologueData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this function has prologue data. <a href="#ae8c01344089090a372ee86f62c07f2bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dfe213825f2e052d5dd376b3ce182d0">getPrologueData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the prologue data associated with this function. <a href="#a6dfe213825f2e052d5dd376b3ce182d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac80cb4c1c131aabafef0fdd92af7cac0">setPrologueData</a> (Constant *PrologueData)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b8c4fb5c4e648b5e893b3db122bdf6c">print</a> (raw_ostream &amp;OS, AssemblyAnnotationWriter *AAW=nullptr, bool ShouldPreserveUseListOrder=false, bool IsForDebug=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the function to an output stream with an optional <a href="/web-llvm/docs/api/classes/llvm/assemblyannotationwriter">AssemblyAnnotationWriter</a>. <a href="#a5b8c4fb5c4e648b5e893b3db122bdf6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa16dbafaedca375940c39e1c7ecff2ae">viewCFG</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>viewCFG - This function is meant for use from the debugger. <a href="#aa16dbafaedca375940c39e1c7ecff2ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60db5d1a9b92efaf4f0904959e3b3648">viewCFG</a> (const char *OutputFileName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>viewCFG - This function is meant for use from the debugger. <a href="#a60db5d1a9b92efaf4f0904959e3b3648">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeac4ca2dcb29682747f7d637b47c8327">viewCFG</a> (bool ViewCFGOnly, const BlockFrequencyInfo *BFI, const BranchProbabilityInfo *BPI, const char *OutputFileName=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extended form to print edge weights. <a href="#aeac4ca2dcb29682747f7d637b47c8327">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac597af7c6f9404366ebac258d2c90223">viewCFGOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>viewCFGOnly - This function is meant for use from the debugger. <a href="#ac597af7c6f9404366ebac258d2c90223">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8220277a7e54b877e77cfb16e1958df9">viewCFGOnly</a> (const char *OutputFileName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>viewCFG - This function is meant for use from the debugger. <a href="#a8220277a7e54b877e77cfb16e1958df9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac604e42ef1bf36f1739f06cc7677398b">viewCFGOnly</a> (const BlockFrequencyInfo *BFI, const BranchProbabilityInfo *BPI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extended form to print edge weights. <a href="#ac604e42ef1bf36f1739f06cc7677398b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a768878e5a19c5ccdf0ad7f765e9fcc8a">dropAllReferences</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a768878e5a19c5ccdf0ad7f765e9fcc8a">dropAllReferences()</a> - This method causes all the subinstructions to "let
go" of all references that they are maintaining. <a href="#a768878e5a19c5ccdf0ad7f765e9fcc8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b87b14bb6dd4f14bb42c73d2085673e">hasAddressTaken</a> (const User **=nullptr, bool IgnoreCallbackUses=false, bool IgnoreAssumeLikeCalls=true, bool IngoreLLVMUsed=false, bool IgnoreARCAttachedCall=false, bool IgnoreCastedDirectCall=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasAddressTaken - returns true if there are any uses of this function other than direct calls or invokes to it, or blockaddress expressions. <a href="#a1b87b14bb6dd4f14bb42c73d2085673e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135e2cf7628956c6c2a4365fb10305cc">isDefTriviallyDead</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isDefTriviallyDead - Return true if it is trivially safe to remove this function definition from the module (because it isn't externally visible, does not have its address taken, and has no callers). <a href="#a135e2cf7628956c6c2a4365fb10305cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9f8509c58dcb05e2bc130b24618f35f">callsFunctionThatReturnsTwice</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>callsFunctionThatReturnsTwice - Return true if the function has a call to setjmp or other function that gcc recognizes as "returning twice". <a href="#ab9f8509c58dcb05e2bc130b24618f35f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05a19abc8ee11d5909275d980efa1670">setSubprogram</a> (DISubprogram *SP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the attached subprogram. <a href="#a05a19abc8ee11d5909275d980efa1670">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d834f9897d15e3a6349063b5d637cd8">getSubprogram</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the attached subprogram. <a href="#a4d834f9897d15e3a6349063b5d637cd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7345f1a973f5084e01c183cad89399d5">shouldEmitDebugInfoForProfiling</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we should emit debug info for profiling. <a href="#a7345f1a973f5084e01c183cad89399d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a212723e3aa6b6ca349b27344bc417505">nullPointerIsDefined</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if null pointer dereferencing is considered undefined behavior for the function. <a href="#a212723e3aa6b6ca349b27344bc417505">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f7bed83bd85a8047e38a36b0a6e86c3">CheckLazyArguments</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad29973081e44927d9f608d75b68798b">BuildLazyArguments</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9428610ca28f18617fcef7e711f2c7d">clearArguments</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace5127a647cfc299454c65c46b5a881e">deleteBodyImpl</a> (bool ShouldDrop)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a0e3bfa03a4f2a697d3002154c48f2c7a">BasicBlockListType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb74b1a24961c058ef44eb0eac7a5ce7">getBasicBlockList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the underlying elements of the <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>... the basic block list is empty for external functions. <a href="#abb74b1a24961c058ef44eb0eac7a5ce7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0e3bfa03a4f2a697d3002154c48f2c7a">BasicBlockListType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac94db32d5c61fac27d3f93a7f6b5a892">getBasicBlockList</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b3c4bd354de30f5d44b3c23302312ee">validateBlockNumbers</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assert that all blocks have unique numbers within 0..NextBlockNum. <a href="#a1b3c4bd354de30f5d44b3c23302312ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5029ffc19e34140155b1560345cbe04">allocHungoffUselist</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Idx&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4b475ed3b75ab7892452e4841ad4e5c1">setHungoffOperand</a> (Constant *C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cc480510ff498f9f28dcc55ed8631af">setValueSubclassData</a> (unsigned short D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Shadow <a href="/web-llvm/docs/api/classes/llvm/value/#aae37705b598ef612f698198dc33d6f65">Value::setValueSubclassData</a> with a private forwarding method so that subclasses cannot accidentally use it. <a href="#a5cc480510ff498f9f28dcc55ed8631af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe766658327dceb3eccd7c579470d245">setValueSubclassDataBit</a> (unsigned Bit, bool On)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f470380211ecb6cee767f1ef0f16ed0">IsNewDbgInfoFormat</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this function using intrinsics to record the position of debugging information, or non-intrinsic records? <a href="#a5f470380211ecb6cee767f1ef0f16ed0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0e3bfa03a4f2a697d3002154c48f2c7a">BasicBlockListType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8712cd664d67cbfe7a462e4c4d4d2b9">BasicBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The basic blocks. <a href="#af8712cd664d67cbfe7a462e4c4d4d2b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54d020431389f17e0e65211e54d09a95">NextBlockNum</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1ba400a02e7f6a2b61b239bad8e54f3">BlockNumEpoch</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Epoch of block numbers. (Could be shrinked to uint8_t if required.) <a href="#ae1ba400a02e7f6a2b61b239bad8e54f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20e97a91346642ac4f0f0e9a1c655545">Arguments</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The formal arguments. <a href="#a20e97a91346642ac4f0f0e9a1c655545">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1cea14ccbb330a3d362f4940b91f193">NumArgs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/valuesymboltable">ValueSymbolTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa056af4a606ca8d9d6da75fc448570a">SymTab</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Symbol table of args/instructions. <a href="#afa056af4a606ca8d9d6da75fc448570a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">AttributeList</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07f61561ee790f64561b2f9b5dd02aca">AttributeSets</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parameter attributes. <a href="#a07f61561ee790f64561b2f9b5dd02aca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2435e8480cd99f4cee7818121a8dee68">LibFuncCache</a> = UnknownLibFunc</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache for TLI::getLibFunc() result without prototype validation. <a href="#a2435e8480cd99f4cee7818121a8dee68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05d7aedbbdc0fd24e8bc27edfe9c603f">Create</a> (FunctionType *Ty, LinkageTypes Linkage, unsigned AddrSpace, const Twine &amp;N="", Module *M=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7321f6163cd0a3ed2c1e87c63c6c4263">Create</a> (FunctionType *Ty, LinkageTypes Linkage, const Twine &amp;N="", Module *M=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7351d0170b356c9f3487f8cc8c6cafd">Create</a> (FunctionType *Ty, LinkageTypes Linkage, const Twine &amp;N, Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new function and attaches it to a module. <a href="#ab7351d0170b356c9f3487f8cc8c6cafd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dfae571c803bc1e2cd79bf98cc1951f">createWithDefaultAttr</a> (FunctionType *Ty, LinkageTypes Linkage, unsigned AddrSpace, const Twine &amp;N="", Module *M=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a function with some attributes recorded in llvm.module.flags and the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> applied. <a href="#a5dfae571c803bc1e2cd79bf98cc1951f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b6f4f4582247421b5810172acd85432">classof</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast: <a href="#a3b6f4f4582247421b5810172acd85432">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a0e3bfa03a4f2a697d3002154c48f2c7a">BasicBlockListType</a> Function::*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f6bd8041cdf6492f78245bc2737e0be">getSublistAccess</a> (BasicBlock *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/user/hungoffoperandsallocmarker">HungOffOperandsAllocMarker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e66c8b366d630ce63cd7cdcca596a9b">AllocMarker</a> {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd2c2c6ca7ba5fb629b92d17cce912a7">UnknownLibFunc</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a>(-1)</td>
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

## Function Argument Iteration Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1c9f2f058966db1f8ca270398bda8362">arg_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bf193a781a92cae52d7f9216d0824f8">arg_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae8dcf6aa51ec5887c9c52c148535c021">const_arg_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a414f3bebd529527d4f7d8b7320b625c3">arg_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1c9f2f058966db1f8ca270398bda8362">arg_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8300ac1ef141b8a7c63c13fa9369d976">arg_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae8dcf6aa51ec5887c9c52c148535c021">const_arg_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40a13b2b2dc684c189642183fc4d81bf">arg_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecf2b6d6f052a378dd8f69fd1bb700b1">getArg</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a1c9f2f058966db1f8ca270398bda8362">arg_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49e6c89ce42a55a93ddf38d21bbd198e">args</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ae8dcf6aa51ec5887c9c52c148535c021">const_arg_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36d0e82850793ac518b317fb9ecd61ec">args</a> () const</td>
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


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### arg\_iterator {#a1c9f2f058966db1f8ca270398bda8362}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Function::arg_iterator =  Argument *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### BasicBlockListType {#a0e3bfa03a4f2a697d3002154c48f2c7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Function::BasicBlockListType =  SymbolTableList&lt;BasicBlock&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### const\_arg\_iterator {#ae8dcf6aa51ec5887c9c52c148535c021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Function::const_arg_iterator =  const Argument *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### const\_iterator {#a7e04cb9e3897c6b3b5ae22349695fa69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Function::const_iterator =  BasicBlockListType::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### iterator {#a19595c245bd2e3eefa93ce22db5ad15f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Function::iterator =  BasicBlockListType::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a410341838f0c4b80b5beddec4719782f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Bits from GlobalObject::GlobalObjectSubclassData.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsMaterializableBit<a id="a410341838f0c4b80b5beddec4719782fa703429dba638c4544dd3457f254261eb"></a></td>
<td class="doxyEnumItemDescription">Whether this function is materializable (= 0)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### ProfileCountType {#a438d2f246b76817114ade2a005a6bcab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Function::ProfileCountType </td>
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
<td class="doxyEnumItemName">PCT_Real<a id="a438d2f246b76817114ade2a005a6bcabac7dbc704eba08842e6acdde9cf6379ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCT_Synthetic<a id="a438d2f246b76817114ade2a005a6bcaba861521f9793383de9ba626e189b4b5b6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### BasicBlock::eraseFromParent {#aa8d611ee05eb26761a65e560e1481464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/iplist">iplist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt;<a href="#a19595c245bd2e3eefa93ce22db5ad15f">::iterator</a> undefined</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 789 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4c464ef563b721bcb04c8a998c30cabd">llvm::BasicBlock::Instruction::eraseFromParent</a>.</p>

</div>
</div>

### BasicBlock::removeFromParent {#a8c3fa281c85f015ea3ba20c7efc41714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend void undefined</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a3be34ea0f6bb2f1c928e200c4a8fa5ef">llvm::BasicBlock::Instruction::removeFromParent</a>.</p>

</div>
</div>

### BasicBlock::setParent {#a08f65cbf6fd290b525f04667d9a952ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend void <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### InstIterator {#abe80de7eff41fd5161782104539568c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/institerator">InstIterator</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Referenced by <a href="#a2e2ab800c636979b14ada45510861743">llvm::ilist_node_with_parent&lt; llvm::BasicBlock, llvm::Function &gt;</a>.</p>

</div>
</div>

### llvm::ilist\_node\_with\_parent&lt; llvm::BasicBlock, llvm::Function &gt; {#a2e2ab800c636979b14ada45510861743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent">llvm::ilist_node_with_parent</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">llvm::BasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> and <a href="#abe80de7eff41fd5161782104539568c1">InstIterator</a>.</p>

</div>
</div>

### llvm::SymbolTableListTraits&lt; llvm::BasicBlock &gt; {#af18ee185be80bb60b1c47f8d0ab78711}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/symboltablelisttraits">llvm::SymbolTableListTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">llvm::BasicBlock</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

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


<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### TargetLibraryInfoImpl {#a4d6fd92c5a6d2931b039e6405475322f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl">TargetLibraryInfoImpl</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="#ad93d1f4325f9ecee231d5f62adf8d74e">hasLazyArguments</a> and <a href="#a4d6fd92c5a6d2931b039e6405475322f">TargetLibraryInfoImpl</a>.</p>


<p>Referenced by <a href="#a4d6fd92c5a6d2931b039e6405475322f">TargetLibraryInfoImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Function() {#ae7e09342bb3ccc55b803067615284552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Function::Function (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### Function() {#a9a1f910efbc2a5d9a81b5bab38f0331a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function::Function (<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage, unsigned AddrSpace, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; N="", <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> ctor - If the (optional) <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> argument is specified, the function is automatically inserted into the end of the function list for the module.</p>

<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Function() {#a3b03f7cf0b75d16edebdda1dee1db6fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function::~Function ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#acc545a99211445342e8907df8f841e6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAttributeAtIndex() {#af9603b8b801fc36a29ea533b19c1baca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::addAttributeAtIndex (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Attr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>adds the attribute to the list of attributes.</p>

<p>Declaration at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### addDereferenceableOrNullParamAttr() {#a8f040402288effcbdffb4f7c9748f067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::addDereferenceableOrNullParamAttr (unsigned ArgNo, uint64_t Bytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>adds the dereferenceable_or_null attribute to the list of attributes for the given arg.</p>

<p>Declaration at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### addDereferenceableParamAttr() {#af49f352a100314919e2603afe4d87cff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::addDereferenceableParamAttr (unsigned ArgNo, uint64_t Bytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>adds the dereferenceable attribute to the list of attributes for the given arg.</p>

<p>Declaration at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 726 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### addFnAttr() {#a01875e4204852069dd4b7938cab4140b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::addFnAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add function attributes to this function.</p>

<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#afca73617f8390579ca48fa10bf1c8edb">assureFPCallStub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#a6406a80ca9230c2d3e441f6975dba745">createFPFnStub</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuctordtorlowering-cpp-/#aa82200436735a7e7831e52db45ae4580">anonymous{AMDGPUCtorDtorLowering.cpp}::createInitOrFiniKernelFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a256980e987af753b4c497757fad18000">llvm::createSanitizerCtor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a4e06ebf129ddfb3b33a64f1a456cfc24">fillOverallFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a784adc2347b72f745ff1239aef3a3c26">llvm::OpenMPIRBuilder::finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#afffa0ff2e1527ab545cef33be915c656">hostParallelCallback</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/structs/enumattr/#aad70a721379eef0de5fe32fb197d20de">EnumAttr::set</a>, <a href="/web-llvm/docs/api/structs/strboolattr/#a5a6b2087dcc3cc658ad1d9e0e321be1b">StrBoolAttr::set</a>, <a href="#a9dca1751288896161d502571fecf2ae3">setCannotDuplicate</a>, <a href="#a95f8eff531b9ed5d85cdc2f8d7c3e5c6">setConvergent</a>, <a href="#a059fada19030e5930c4b511d4fe6a766">setCoroDestroyOnlyWhenComplete</a>, <a href="#afb7e3c73013c2827ccd486e888953875">setDoesNotFreeMemory</a>, <a href="#aecb901181edae6cd518104e05ccb6f78">setDoesNotRecurse</a>, <a href="#a57d6d47f3d0fe19f5a9bc1626630d4b0">setDoesNotReturn</a>, <a href="#afd978c6f74e279603d47b940f60f1f24">setDoesNotThrow</a>, <a href="#af7915406c3f283ae294f55c2c9dc49c1">setMustProgress</a>, <a href="#ac972de5ac0d70f5bd4ff3cf958911e94">setNoSync</a>, <a href="#a95f94f1901598a30b2644932e09320ab">setPresplitCoroutine</a>, <a href="#a99a24ef326b23786e0e0b7f7c02d45a4">setSpeculatable</a>, <a href="#a7a383eea189e7af487299e904c0b5fcc">setUWTableKind</a>, <a href="#a460362250160f652f82d5de1fc5379d2">setWillReturn</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af7668ce8080668a4f0ceac24e70c9f00">targetParallelCallback</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad944e40dbc606e1494923b581c9732f3">llvm::updateMinLegalVectorWidthAttr</a>.</p>

</div>
</div>

### addFnAttr() {#ae7b919df259dce5480774e656791c079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::addFnAttr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Val=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add function attributes to this function.</p>

<p>Declaration at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### addFnAttr() {#a2902ff168f1dbd817ebf6bbb9c468e5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::addFnAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Attr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add function attributes to this function.</p>

<p>Declaration at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### addFnAttrs() {#a34cf0c64f57241d690ee7009afc629b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::addFnAttrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> AttrBuilder &amp; Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add function attributes to this function.</p>

<p>Declaration at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### addParamAttr() {#aa5087b607af833220d9ebab0c88c83c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::addParamAttr (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>adds the attribute to the list of attributes for the given arg.</p>

<p>Declaration at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-jmcinstrumenter-cpp-/#aea6556d942d972a777204187dd1600e5">anonymous{JMCInstrumenter.cpp}::createDefaultCheckFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#afffa0ff2e1527ab545cef33be915c656">hostParallelCallback</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af7668ce8080668a4f0ceac24e70c9f00">targetParallelCallback</a>.</p>

</div>
</div>

### addParamAttr() {#a6eb05d774eaaab1b7ad6cee10e3713e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::addParamAttr (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Attr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>adds the attribute to the list of attributes for the given arg.</p>

<p>Declaration at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### addParamAttrs() {#a092beb46ecce99e6b39628ee92ccd95a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::addParamAttrs (unsigned ArgNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> AttrBuilder &amp; Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>adds the attributes to the list of attributes for the given arg.</p>

<p>Declaration at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 677 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### addRangeRetAttr() {#a93469502fd939d1f842d69f813f38d33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::addRangeRetAttr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>adds the range attribute to the list of attributes for the return value.</p>

<p>Declaration at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 803 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### addRetAttr() {#a6afca945952abdd7be262d5fe5ddad77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::addRetAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add return value attributes to this function.</p>

<p>Declaration at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#a698b49a3ec754ef00d2c27d146daa5e2">setReturnDoesNotAlias</a>.</p>

</div>
</div>

### addRetAttr() {#ae2732a9861a5ff74a3468a1b53d700bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::addRetAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Attr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add return value attributes to this function.</p>

<p>Declaration at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 661 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### addRetAttrs() {#a0cccf168c794d734b0377a0c61a89909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::addRetAttrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> AttrBuilder &amp; Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add return value attributes to this function.</p>

<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 665 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### arg\_empty() {#a3ac1213bb14caae3108345d40069bfb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::arg_empty ()</td>
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



<p>Definition at line 902 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#ac6baa801e4aea800984e760d5460662f">arg_size</a>.</p>

</div>
</div>

### arg\_size() {#ac6baa801e4aea800984e760d5460662f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::Function::arg_size ()</td>
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



<p>Definition at line 901 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a50c6490cf353f064946c4e32673ac098">llvm::OpenMPIRBuilder::addAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afd992a2165073c9cea53128d5b6c4145">llvm::X86FrameLowering::adjustForHiPEPrologue</a>, <a href="#a3ac1213bb14caae3108345d40069bfb1">arg_empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a7ee234a7eddb790513041e995ed66158">CC_X86_Intr</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a8d0a2ebeeedeb0bd16a52affb7f6ed88">llvm::Attributor::checkForAllCallSites</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af0793991541abccfec5c0d8831612b7b">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::createNoAllocVariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#ae86fef7fc5831c2514bff95bdf784d09">createSwitchStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#afffd4df1bba5cd5416f615e919a8fa66">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandVAIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-erlanggcprinter-cpp-/erlanggcprinter/#a574679a34186d5db3a7b14b0ce5c5078">anonymous{ErlangGCPrinter.cpp}::ErlangGCPrinter::finishAssembly</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a265735d2c2edc0a1a03611e7aadd24cd">llvm::IRPosition::getAssociatedArgument</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#ae7547d953171225ca4aea8c69ccabb7c">llvm::IRPosition::getNumArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a78c7e7972f2cde9531b9f9d71196cfc5">hasSameArgumentList</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#afffa0ff2e1527ab545cef33be915c656">hostParallelCallback</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a273e9b97fc0dfec8df7cf4294d9b87fe">llvm::Attributor::isValidFunctionSignatureRewrite</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluefunctionparameters/#ga670f0e5258f93e51e6700309ae99dfbe">LLVMGetNextParam</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a0121eb7b984a5cf2527133cb838d5982">llvm::Attributor::registerFunctionSignatureRewrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a7e2cad7ab18db9a3c940afc609c223dc">replaceCalledFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/coroannotationelidepass/#a411202dc502ac666302ba81c40e94b10">llvm::CoroAnnotationElidePass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af7668ce8080668a4f0ceac24e70c9f00">targetParallelCallback</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerkernelarguments-cpp-/preloadkernelarginfo/#a7a5253091344c2d534f5afd16941e25d">anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::tryAllocImplicitArgPreloadSGPRs</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad37834e4f8e16e808997aef286954fd0">upgradeNVVMIntrinsicCall</a>.</p>

</div>
</div>

### back() {#a43b79a254fba6ce00adf5b963382a0a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock &amp; llvm::Function::back ()</td>
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



<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a2d071e661a02790177ba05f62c7c27d1">llvm::BasicBlock::back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#a761b3c02cd196cb5f6fb019bcd86866e">llvm::OutlinableRegion::splitCandidate</a>.</p>

</div>
</div>

### back() {#aa08597bdb94f7c8409da1016e4d3900e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock &amp; llvm::Function::back ()</td>
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



<p>Definition at line 863 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a2d071e661a02790177ba05f62c7c27d1">llvm::BasicBlock::back</a>.</p>

</div>
</div>

### begin() {#a88a5e60837674780a9d812d661897ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::Function::begin ()</td>
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



<p>Definition at line 853 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac800803b298b2e26368a3cc770279945">anonymous{ExpandVariadics.cpp}::ExpandVariadics::deriveFixedArityReplacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a0a93e5a229615932f4e2ba47f55a3ba0">FindAtExitLibFunc</a>, <a href="/web-llvm/docs/api/classes/anonymous-coveragemapping-cpp-/functioninstantiationsetcollector/#a6360983fbe338a13210556ee589ad69b">anonymous{CoverageMapping.cpp}::FunctionInstantiationSetCollector::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-55c8cb82503f51812ad190e425a6fd3d/#a62600d14a86e8b536fb61bd700ed49f6">llvm::GraphTraits&lt; DOTFuncInfo * &gt;::nodes_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-02f9563a016dafe7fbc78fcb1f76f101/#afc5cb7046c606977b01abe2914be8323">llvm::GraphTraits&lt; DOTFuncMSSAInfo * &gt;::nodes_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a6e4c46869d9d198562f7b8628814e407">raiseUserConstantDataAllocasToEntryBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a> and <a href="#a14b02db913559954c4d38ed70cd66f59">splice</a>.</p>

</div>
</div>

### begin() {#a944c299cf8bcabbb0f81d71c182068f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::Function::begin ()</td>
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



<p>Definition at line 854 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### callsFunctionThatReturnsTwice() {#ab9f8509c58dcb05e2bc130b24618f35f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::callsFunctionThatReturnsTwice ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>callsFunctionThatReturnsTwice - Return true if the function has a call to setjmp or other function that gcc recognizes as "returning twice".</p>

<p>Declaration at line 1011 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1039 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-cfguardlongjmp-cpp-/cfguardlongjmp/#a17b3d486f52582c92dec4b050aedb70a">anonymous{CFGuardLongjmp.cpp}::CFGuardLongjmp::runOnMachineFunction</a>.</p>

</div>
</div>

### cannotDuplicate() {#a432063a2bc02df1d1c93957c644e966c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::cannotDuplicate ()</td>
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

<p>Determine if the call cannot be duplicated.</p>

<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#afb28a4deafe2954b0534cc6399ce518b">hasFnAttribute</a>.</p>

</div>
</div>

### clearGC() {#ad3ba7e58bebd9bbadb647fe4691a7e6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::clearGC ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 845 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### convertFromNewDbgValues() {#a6e506a1fad2bb34972806851b52478e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::convertFromNewDbgValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a5753230c9e297fed32356ebf071074f0">BasicBlock::convertFromNewDbgValues</a>.</p></dd>
</dl>


<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### convertToNewDbgValues() {#ae7e97db06807fee808c3db2f33012556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::convertToNewDbgValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a3ead08d4d049585ee09421bcebd2ae25">BasicBlock::convertToNewDbgValues</a>.</p></dd>
</dl>


<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### copyAttributesFrom() {#afd7894f118b1d1636cff1b8de5f424e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::copyAttributesFrom (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>copyAttributesFrom - copy all additional attributes (those not needed to create a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>) from the <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Src to this one.</p>


<p>Copy all additional attributes (those not needed to create a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>) from the <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Src to this one.</p>


<p>Declaration at line 726 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 860 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#aaf2fe2b910650ab4ea0eeaca5922dce8">addVariantDeclaration</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a993ad5e82f2d59de8127cfcb38a62e0a">llvm::orc::cloneFunctionDecl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab371d6b308eb9772bdec63cf7a041407">llvm::CloneModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac800803b298b2e26368a3cc770279945">anonymous{ExpandVariadics.cpp}::ExpandVariadics::deriveFixedArityReplacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a071c6530f4d3362b846fdc1701c216e9">getTLIFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a64cd5b79789610d81be5d0b2633868ae">anonymous{ThinLTOBitcodeWriter.cpp}::simplifyExternals</a>.</p>

</div>
</div>

### DECLARE\_TRANSPARENT\_OPERAND\_ACCESSORS() {#aec04f4ee74f001679174332506c0cebc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Function::DECLARE_TRANSPARENT_OPERAND_ACCESSORS (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#af67f86066ad1891d424553b352dfa821">getInstructionCount</a>.</p>

</div>
</div>

### deleteBody() {#a0020cbf9c3df714558a9b20a6267bd29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::deleteBody ()</td>
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

<p>deleteBody - This method deletes the body of the function, and converts the linkage to external.</p>

<p>Definition at line 731 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a687973de03d041e04b50a76d19d4fd36">llvm::GlobalValue::setLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callgraphupdater/#a300122a2a53b922943eff21c4039ad73">llvm::CallGraphUpdater::removeFunction</a>.</p>

</div>
</div>

### doesNoCfCheck() {#a58e9603fcbb784bee436392db60d93f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::doesNoCfCheck ()</td>
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

<p>Determine if the function should not perform indirect branch tracking.</p>

<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#afb28a4deafe2954b0534cc6399ce518b">hasFnAttribute</a>.</p>

</div>
</div>

### doesNotAccessMemory() {#aa701465fb174e27e3a89695762970997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::doesNotAccessMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the function does not access memory.</p>

<p>Declaration at line 557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 884 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### doesNotFreeMemory() {#aaf2ec1eb99cc826eea1a7dd8a8ea570a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::doesNotFreeMemory ()</td>
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

<p>Determine if the call might deallocate memory.</p>

<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="#afb28a4deafe2954b0534cc6399ce518b">hasFnAttribute</a> and <a href="#af7736e14235372b75b72e119f852c280">onlyReadsMemory</a>.</p>

</div>
</div>

### doesNotRecurse() {#a4e5c42dc883d0deb41a668301cd5ac72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::doesNotRecurse ()</td>
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

<p>Determine if the function is known not to recurse, directly or indirectly.</p>

<p>Definition at line 647 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#afb28a4deafe2954b0534cc6399ce518b">hasFnAttribute</a>.</p>

</div>
</div>

### doesNotReturn() {#ab8ef748e928424955da3d1f6676b25d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::doesNotReturn ()</td>
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

<p>Determine if the function cannot return.</p>

<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#afb28a4deafe2954b0534cc6399ce518b">hasFnAttribute</a>.</p>

</div>
</div>

### doesNotThrow() {#a81f38aca859ffeda166f8c385f7d55a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::doesNotThrow ()</td>
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

<p>Determine if the function cannot unwind.</p>

<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#afb28a4deafe2954b0534cc6399ce518b">hasFnAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a2408a88276528d80adefefa00995705a">llvm::VPRecipeBase::mayHaveSideEffects</a>, <a href="#ad7332117b148c3f93c1d7e58306ee748">needsUnwindTableEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### dropAllReferences() {#a768878e5a19c5ccdf0ad7f765e9fcc8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::dropAllReferences ()</td>
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

<p><a href="#a768878e5a19c5ccdf0ad7f765e9fcc8a">dropAllReferences()</a> - This method causes all the subinstructions to "let
go" of all references that they are maintaining.</p>


<p>This allows one to 'delete' a whole module at a time, even though there may be circular references... first all references are dropped, and all use counts go to zero. Then everything is deleted for real. Note that no operations are valid on an object that has "dropped all references", except operator delete.</p>


<p>Since no other object in the module can have references into the body of a function, dropping all references deletes the entire body of the function, including any contained basic blocks.</p>


<p>Definition at line 986 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### empty() {#a1d8eb3054fd49a89ff41bc22a48f87e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::empty ()</td>
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



<p>Definition at line 859 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#ab3115ef36979b45874f244f374e79d98">llvm::PMDataManager::emitInstrCountChangedRemark</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a0f104a4f4a7edce928ac0aea2a3509b8">lowerFunnelShifts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyloweremscriptenehsjlj-cpp-/webassemblyloweremscriptenehsjlj/#a4e54683754f6664c17d470ae3a097486">anonymous{WebAssemblyLowerEmscriptenEHSjLj.cpp}::WebAssemblyLowerEmscriptenEHSjLj::runOnModule</a>.</p>

</div>
</div>

### end() {#ae4ca2261b8b901e415fda7feac5051ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::Function::end ()</td>
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



<p>Definition at line 855 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af97d9ff977792ae671987a9a95f942f2">llvm::CloneFunctionBodyInto</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a2ed4f37fbda15a9c05f333fde59e9fbb">fixupLineNumbers</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ae28c9f37f79168be8e13396da72d35ff">llvm::SPIRVGlobalRegistry::getFunctionByDefinition</a>, <a href="/web-llvm/docs/api/classes/anonymous-coveragemapping-cpp-/functioninstantiationsetcollector/#a6360983fbe338a13210556ee589ad69b">anonymous{CoverageMapping.cpp}::FunctionInstantiationSetCollector::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-55c8cb82503f51812ad190e425a6fd3d/#af7c73b3a82d23f5fff32e4bcf785b915">llvm::GraphTraits&lt; DOTFuncInfo * &gt;::nodes_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-02f9563a016dafe7fbc78fcb1f76f101/#afd7e457d45b1fc78888f3c5e4e4f7c4a">llvm::GraphTraits&lt; DOTFuncMSSAInfo * &gt;::nodes_end</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#a4839bb9ff9510a0c0bda1e41cabe4714">placeSplitBlockCarefully</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a6e4c46869d9d198562f7b8628814e407">raiseUserConstantDataAllocasToEntryBlock</a> and <a href="#a14b02db913559954c4d38ed70cd66f59">splice</a>.</p>

</div>
</div>

### end() {#a8a84e4980b5bf8e647cdd1b27ca23e6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::Function::end ()</td>
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



<p>Definition at line 856 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### erase() {#add1b62fd0110c8c97673ed9a66603f05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function::iterator Function::erase (<a href="#a19595c245bd2e3eefa93ce22db5ad15f">Function::iterator</a> FromIt, <a href="#a19595c245bd2e3eefa93ce22db5ad15f">Function::iterator</a> ToIt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Erases a range of BasicBlocks from <span class="doxyComputerOutput">FromIt</span> to (not including) <span class="doxyComputerOutput">ToIt</span>.</p>


<p>\Returns <span class="doxyComputerOutput">ToIt</span>.</p>


<p>Declaration at line 784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callgraph/#a10ae28b08e292f846fb954e805e533ce">llvm::CallGraph::removeFunctionFromModule</a>.</p>

</div>
</div>

### eraseFromParent() {#a8969dec86d24dd579f8ecc963e1dc8b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::eraseFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>eraseFromParent - This method unlinks 'this' from the containing module and deletes it.</p>

<p>Declaration at line 744 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/argumentpromotionpass/#afe0f49f9daec2532b14ded30ed46ff28">llvm::ArgumentPromotionPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a40b5636c9d406c277f51dcdcba06821f">anonymous{ExpandVariadics.cpp}::ExpandVariadics::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-spirvregularizer-cpp-/spirvregularizer/#ad05a40cc766968c47d80ddd0f72d3114">anonymous{SPIRVRegularizer.cpp}::SPIRVRegularizer::runOnFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a216b0f52f244182222da5b7fcbc8ca01">stripDebugDeclareImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a484621a748732e2f39e7a2a0058b3b07">llvm::stripDebugifyMetadata</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aef10fb11205c2a096e040dd6b75148eb">llvm::UpgradeARCRuntime</a>.</p>

</div>
</div>

### front() {#a3ec0b920bf30d0e15bace383192691da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock &amp; llvm::Function::front ()</td>
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



<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a63cfb2a0dae69153fd961eb335949caa">llvm::BasicBlock::front</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7a6386c071e1087512cdc8a4071a02b5">llvm::CloneAndPruneFunctionInto</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#a80ad3b35cf775718eb472f8810e73092">anonymous{CloneFunction.cpp}::PruningFunctionCloner::CloneBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af97d9ff977792ae671987a9a95f942f2">llvm::CloneFunctionBodyInto</a>, <a href="#a0da3ad33bda3df0fa6c10d91d3815626">getEntryBlock</a>, <a href="#a169f0c26ef46161741fdd120a806f853">getEntryBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp/#aeab32388541e65c42e97d2ca8c7867d1">insertCallAtFunctionEntryPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp/#a63ce604ca599913727c7c8c7fbe4ca13">runSanitizeRealtimeBlocking</a>.</p>

</div>
</div>

### front() {#abf30a45c2a2e88a614f4ff435aafceaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock &amp; llvm::Function::front ()</td>
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



<p>Definition at line 861 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a63cfb2a0dae69153fd961eb335949caa">llvm::BasicBlock::front</a>.</p>

</div>
</div>

### getAttributeAtIndex() {#ae420319b63092fad3cff17a964ae3c90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Function::getAttributeAtIndex (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>gets the attribute from the list of attributes.</p>

<p>Declaration at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 752 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### getAttributeAtIndex() {#a2e819417d324183edc1fa9d4aaa54431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Function::getAttributeAtIndex (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>gets the attribute from the list of attributes.</p>

<p>Declaration at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 757 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### getAttributes() {#a7477aafbbe989ad35b96fac186d8e9fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::Function::getAttributes ()</td>
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

<p>Return the attribute list for this <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>.</p>

<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a50c6490cf353f064946c4e32673ac098">llvm::OpenMPIRBuilder::addAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af0793991541abccfec5c0d8831612b7b">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::createNoAllocVariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a8d179b8dd229c1d46eee4c257e717e25">createThunk</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac800803b298b2e26368a3cc770279945">anonymous{ExpandVariadics.cpp}::ExpandVariadics::deriveFixedArityReplacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#afc48ca3b84128ca1b9ab1701d4f30b8c">llvm::XCoreFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a4e06ebf129ddfb3b33a64f1a456cfc24">fillOverallFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a4081fd08df96363717c46a40ea774794">llvm::IRPosition::getAttrList</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ac26dae5c257bfaab5aa15cab7255f107">llvm::AArch64RegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfregisters/#a948f65c38b613d36deb501eb8b8476c8">llvm::SystemZELFRegisters::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a2a4f0d74a9e54517b5009c2ac31503b5">llvm::AArch64RegisterInfo::getCallPreservedMask</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#abb9d03a862069b7f3c4f446e0be8b826">llvm::ARMBaseRegisterInfo::getCallPreservedMask</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfregisters/#af9a3f20abd67b17fdb105aa2fe63e08d">llvm::SystemZELFRegisters::getCallPreservedMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#acb8cf9e50c3979193572ea36f327d0a4">getCopyFromParts</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aaab57b42c1306819f384fbc8917e728b">llvm::AArch64RegisterInfo::getDarwinCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ace1d2fbafd80bd71d27a949593da97f7">llvm::AArch64RegisterInfo::getDarwinCallPreservedMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#af917fe9cdb70db029cf2ddd236fae738">getFixedObjectSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a623eef1675bd2f33cfacc50b2fec0c71">getMemmoveLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a24da6451c0e494831c85fa96cb572c9a">insertSinCosCall</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a78b9ad4b9b246aab32ff14d856f5769a">llvm::PPCInstrInfo::isSignOrZeroExtended</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a273e9b97fc0dfec8df7cf4294d9b87fe">llvm::Attributor::isValidFunctionSignatureRewrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a7f0607e63d19dd3d4fb6edcef16bc26e">optimizeDoubleFP</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a1080880d0ca078dceb9d3c8923576ae1">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::preferToKeepConstantsAttached</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a469793f0416704ca132c5c91f73adbdd">produceCompactUnwindFrame</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#a5de55400f4775802364eefb3a1fe20fd">anonymous{CloneFunction.cpp}::PruningFunctionCloner::PruningFunctionCloner</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#aaa1cdfbf8bbbb3d37466c44f0b8a403b">anonymous{ExpandVariadics.cpp}::ExpandVariadics::replaceAllUsesWithNewDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a> and <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a263f69437421410a39c26e0be576f028">llvm::PPCTargetLowering::supportsTailCallFor</a>.</p>

</div>
</div>

### getBlockNumberEpoch() {#a79ece1e904cf5819d13d081101c54f4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Function::getBlockNumberEpoch ()</td>
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

<p>Return the "epoch" of current block numbers.</p>


<p>This will return a different value after every renumbering. The intention is: if something (e.g., an analysis) uses block numbers, it also stores the number epoch and then can assert later on that the epoch didn't change (indicating that the numbering is still valid). If the epoch changed, blocks might have been assigned new numbers and previous uses of the numbers needs to be invalidated. This is solely intended as a debugging feature.</p>


<p>Definition at line 842 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### getCallingConv() {#a5f494edc0a569c7fc9ff4181243be1ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallingConv::ID llvm::Function::getCallingConv ()</td>
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

<p><a href="#a5f494edc0a569c7fc9ff4181243be1ed">getCallingConv()</a>/setCallingConv(CC) - These method get and set the calling convention of this function.</p>


<p>The enum values for the known calling conventions are defined in <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/callingconv-h">CallingConv.h</a>.</p>


<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#a05810d77360abad7ef2848184726d872">llvm::Value::getSubclassDataFromValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca2f101663d054cffa9c9956f30e7ecf7d">llvm::CallingConv::MaxID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a592045324d9ab5a208ce36932f3a7c2d">llvm::SIMachineFunctionInfo::allocateVGPRSpillToAGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a8b1432c767e3cc50f7cb6900285d003f">llvm::AMDGPUCallLowering::areCalleeOutgoingArgsTailCallable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0ca5d8ebe6f1e89b62a445fc3137bd2d">computeCalleeSaveRegisterPairs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e263b9cd2bdbbbaf3d78a2caba5cbf5">llvm::computeSignatureVTs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#aa0d499612ac66539c8daf29c8eb142a5">llvm::coro::createMustTailCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a8d179b8dd229c1d46eee4c257e717e25">createThunk</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ae513c203a406e1186d2342cbdbf95765">llvm::AMDGPUCallLowering::doCallerAndCalleePassArgsTheSameWay</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a51c3d43bee1dec655ecaec65afc94c82">llvm::ARMFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a586e88416ae37cf1579986caeb97a9fa">llvm::LoongArchFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a14e6ca2286bfbfa6952e74370a9c563b">llvm::PPCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa587d71d9d14ad035e31b99fc0c90802">llvm::RISCVFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a8aa8ef70d3b7b3f9c421b488302f563a">llvm::SystemZELFFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#af594db9b0cfd3cba7360a0f8246c0704">llvm::LoongArchFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7e24606b8fe6124decedb17e5ffa405e">llvm::X86FrameLowering::enableShrinkWrapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a8705d5d3c895b6ddc6502220cbe3a965">findScratchNonCalleeSaveRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a3681fb2c471c1278bfd939456c752f22">llvm::MCResourceInfo::gatherResourceInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ac26dae5c257bfaab5aa15cab7255f107">llvm::AArch64RegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/loongarchregisterinfo/#a443b73610fbce56b8189717a4e34b4e0">llvm::LoongArchRegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#aaeae02cd060afb658b3e1e17ad7e42c5">llvm::PPCRegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a24c02ac750fe944f0902c120ed0e773d">llvm::RISCVRegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a44684a6923b734e7d14143bf086cbb87">llvm::SIRegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfregisters/#a948f65c38b613d36deb501eb8b8476c8">llvm::SystemZELFRegisters::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/veregisterinfo/#a678b35c3a154d78fbd4a800517f2e4e6">llvm::VERegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a35e0d4e10fc033d23cb665a9f6ef4bc6">llvm::AArch64RegisterInfo::getCalleeSavedRegsViaCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#ae538c50015c12adeb2477f4ee4b6d2f8">llvm::ARMBaseRegisterInfo::getCalleeSavedRegsViaCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a175455eaa3cecc21fcd21b029b65c0a9">llvm::X86RegisterInfo::getCalleeSavedRegsViaCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aaab57b42c1306819f384fbc8917e728b">llvm::AArch64RegisterInfo::getDarwinCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a8221c74806acd5e0e133095c1bd6a3ce">llvm::SIInstrInfo::getDSShaderTypeValue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a84fbe17f451c957c67de546c98f2b79b">llvm::X86FrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a565000e767f6a2f5381abbb683853bbe">llvm::SIMachineFunctionInfo::getGITPtrLoReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kregisterinfo/#affb039caf886de8fc67678e1dfd83b83">llvm::M68kRegisterInfo::getReservedRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a277355964aa533df56cf3e0de6701b3d">llvm::RISCVRegisterInfo::getReservedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a339d32ea1f7597a13e849615446a7d26">llvm::X86RegisterInfo::getReservedRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a1021e45de682ea397f9aa6c529ac80be">GetScratchRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a135ff03665f8746c89e91d3b802a1017">llvm::AArch64RegisterInfo::getStrictlyReservedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a009e40a8d70eae94c4dc32285c717732">llvm::X86FrameLowering::has128ByteRedZone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ae01246dc7ecdd8a082730860cd3166a1">llvm::AArch64RegisterInfo::isArgumentRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a71ca38441063cb10ea3fb9d1ed7c8d25">llvm::X86RegisterInfo::isArgumentRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regusageinfocollector-cpp/#afeed5836014dfacce7a1e81ad158f1ac">isCallableFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ad8411ad3f00885b182d4dde587ccfaff">llvm::TargetRegisterInfo::isCalleeSavedPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ab499a2cf9f362a8c1f6880e27095b598">llvm::HexagonTargetLowering::IsEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#aba8fa9d02ad8b557faaf41b37b714ba4">llvm::AArch64CallLowering::isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a1c1ba0852c28df8598b5a0d2f0abb3aa">llvm::AMDGPUCallLowering::isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9330a86a613cf892ee5c7f515713f200">llvm::SITargetLowering::isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a09787033a63326e79a0d1445d3e0de13">llvm::SIInstrInfo::legalizeOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a84269093cb913d8f68ea84f72d75dee1">LowerVACOPY</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aac7a5fd4d172200a005d5e17839ba5d0">llvm::SITargetLowering::mayBeEmittedAsTailCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuattributor-cpp-/amdgpuinformationcache/#a37898eb0ae472c290fda31a00e0c1e11">anonymous{AMDGPUAttributor.cpp}::AMDGPUInformationCache::needsQueuePtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a469793f0416704ca132c5c91f73adbdd">produceCompactUnwindFrame</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a049dfdf656884a9d492cb2bc7a664dbf">reservePrivateMemoryRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ac8934ae6c8b97148ebb1db39bd978b03">llvm::AArch64FrameLowering::resolveFrameOffsetReference</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowercontrolflow-cpp-/silowercontrolflow/#a50b92c758d08d3acdda45455f661f5c5">anonymous{SILowerControlFlow.cpp}::SILowerControlFlow::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600controlflowfinalizer-cpp-/r600controlflowfinalizer/#aab0c0f47a6a686867561fa0275a393b1">anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-silatebranchlowering-cpp-/silatebranchlowering/#a2f96cc01100e6467c2b124371cf417c0">anonymous{SILateBranchLowering.cpp}::SILateBranchLowering::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86vzeroupper-cpp-/vzeroupperinserter/#aeca239d7a3896bd3e3dcd89763239609">anonymous{X86VZeroUpper.cpp}::VZeroUpperInserter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a35a105e91c800bd98c2810586f60dcc7">llvm::X86RegisterInfo::shouldRealignStack</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a049804b3fe8b5e8ddea9a1d2c15882b9">llvm::AArch64TargetLowering::supportSplitCSR</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a263f69437421410a39c26e0be576f028">llvm::PPCTargetLowering::supportsTailCallFor</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a9e53ebf2b443013c10d250085799adfc">llvm::SystemZELFFrameLowering::usePackedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a024479869943dfba001bb5701d62a243">llvm::SIMachineFunctionInfo::usesAGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a228e67ed635dc4282489be7f3fc1c2e8">llvm::R600InstrInfo::usesTextureCache</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#abbae172c51615eb52ec12f0af642de64">llvm::R600InstrInfo::usesVertexCache</a> and <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a3f77e2cab72167554d1d13c44fc9877d">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::verifyGraph</a>.</p>

</div>
</div>

### getContext() {#a9fffac2512fe651f0d5e37e27f5bd51c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext &amp; Function::getContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getContext - Return a reference to the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> associated with this function.</p>

<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aa35af336fee32786b6551e23d5b55fcf">AddAliasScopeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a50c6490cf353f064946c4e32673ac098">llvm::OpenMPIRBuilder::addAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a0faf2520b671c3cb14b4f291c873cb88">addBoundsChecking</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af1986bc1d2d700807f4c8ef167bf6fdd">AddParamAndFnBasicAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a8843a51d7d6aaf2e81c17ae86f86d3f6">AddReturnAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a8b1432c767e3cc50f7cb6900285d003f">llvm::AMDGPUCallLowering::areCalleeOutgoingArgsTailCallable</a>, <a href="/web-llvm/docs/api/classes/anonymous-armfastisel-cpp-/armfastisel/#ac8e1ee94bced949e039028f65dc5784d">anonymous{ARMFastISel.cpp}::ARMFastISel::ARMFastISel</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a6aee777d2869b23ba59b88b9ceb32cfe">llvm::SPIRVGlobalRegistry::buildConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aa28f164b227803f0fef41094366c2dca">llvm::MachineIRBuilder::buildFConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a4265ff404073d12b765bc9fee4e7f186">llvm::MachineIRBuilder::buildFConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a018820d0fb56abe52c51565fb10c19ab">llvm::AArch64CallLowering::canLowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a672b2d48b831e2db6310036e4bf711d0">llvm::RISCVCallLowering::canLowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#ade4537627ac400052f74edc475906cc6">llvm::X86CallLowering::canLowerReturn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a5fc63c934f29c38bfba9692a6a2166ee">collectCallSiteParameters</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#af77a6b87eef9b3173d765b97ceb6c5fb">llvm::SITargetLowering::computeKnownAlignForTargetInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a7b104b582108e25271c32924224a20fb">convertImplicitDefToConstZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a8120984c169f2ea17e785e7c6887702a">createAndInsertBasicBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a2bd6903bee5451ebaffd790ccf869664">llvm::MIRParserImpl::createDummyFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#a6406a80ca9230c2d3e441f6975dba745">createFPFnStub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a524d3d59c93afc0f68256056ba5bfa0b">llvm::createMemLibcall</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af0793991541abccfec5c0d8831612b7b">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::createNoAllocVariant</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6885e40448874565521daac98e11f50d">llvm::TargetInstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#a86ad8db657f0a7ace4758548f09ef59a">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::determineRegsForWWMAllocation</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a216ca57e8763ecd488951398b30386b1">anonymous{SIMemoryLegalizer.cpp}::diagnoseUnknownMMRAASName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a2c263d194af0af601f8fe37e10f1ea74">duplicateCPV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#acd3a382f7ecb233b53ad4e1b44db01e3">emitEntryMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86pretileconfig-cpp/#afe92e56d6295b035b78b03a69f64bf41">emitErrorMsg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aaee16070891b230788ad237d5ba6476d">llvm::MachineInstr::emitGenericError</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad72245681f0ae02a2d4574d434bc813d">llvm::MachineInstr::emitInlineAsmError</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinterinlineasm-cpp/#a362579106cd14231f459ca8c00af60ca">EmitInlineAsmStr</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a5e4563cae7f10b41cdff9a61f1f6aaab">llvm::ARMBaseRegisterInfo::emitLoadConstPool</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a3d3173a10a3471dbb8834bf4933607f6">emitUnsupportedError</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a2ed4f37fbda15a9c05f333fde59e9fbb">fixupLineNumbers</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a07c54e53e4d7a7ec84aa30d37f888f62">getBBAddrMapFeature</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a120dbb8d0a1ad4437456001a302a1da7">llvm::MachineIRBuilder::getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a529578790bc8de8b220cef2ca6becef1">getEntryPropAsMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a1558554539a5b133b8e361c0517e9fb1">llvm::RegAllocBase::getErrorAssignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#a97235ab99e26ebd8fe54f629666f6bd2">getFuncAddrForProfData</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a9fa574f4bc0ad6d1cd8335fdf7aba857">llvm::CSKYInstrInfo::getGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a3d6978ae20178c8f9414ff980fd4e3b2">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVBoolType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadf38ec8e97afd05668e524d9ab0e60d">llvm::getOrCreateSPIRVDeviceEventPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acdec96f14d81b2043e31f3452e440a4b">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVIntegerType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a7712aacb3f4a1a860a15ca4de83e6a9f">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8f17d3e92f855f675577a021e9bc2a35">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVTypeByName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#a4334e601f712be7fd456cd1c5b26e96e">getPointeeTypeByCallInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#a43762e6a22fd0e7b98b8115946fc87b6">getRegistersForValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ac5c4384a376959ec882f7650e427dbb5">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::initialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp/#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a1a4145a18b32a1bc1030bf789e370963">InsertCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp/#aaf5c6a95e57ae41b1bb74e87476d3dcc">insertCallBeforeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a593e32f55b5d5133887cf7feb7999792">llvm::XtensaInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a307848f42e24813c2b6a55b8d8959fa4">insertInlineAsmProcess</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a88d50bb943ed6d9b7bf0a34367d018af">interpretValues</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ad357707a4ab97832b2f9ad24490b4376">llvm::PPCTargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a04975f118b224e8cd322d1aa86f2ceb2">llvm::AMDGPULegalizerInfo::legalizeGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#aa97467a5c0d54755f0e725e9310ffaa0">llvm::RISCVLegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae0d1532576a7c6e3bda2d8966700d27a">llvm::AMDGPULegalizerInfo::legalizeSBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a01bea37475bf9a1f853b90975dbf7605">LowerFPToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1dbb219846876149646e81e84ee81a47">llvm::LegalizerHelper::lowerLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41052a5d27c665c41207f349f1a45af2">llvm::lowerObjectSizeCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a141bf09f97adbbe9f512fb1141f37090">llvm::RISCVTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a40e2e64056fc2e2dabadfb9ceae338f6">llvm::LegalizerHelper::lowerStore</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a9511578c9aa47dc8c5d7df3e9b623be3">llvm::LegalizerHelper::lowerVAArg</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a28a0f1422b780a83a9632e5d46993dfc">llvm::CombinerHelper::matchCombineExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aab86990eacd037e1c72749c3342d410e">llvm::CombinerHelper::matchHoistLogicOpWithSameOpcodeHands</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a070e7ae88917971c8b99b3bb7f3d5942">llvm::CombinerHelper::matchLoadOrCombine</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsfastisel-cpp-/mipsfastisel/#ae62d9e89cea91d950a28eee7e5a32088">anonymous{MipsFastISel.cpp}::MipsFastISel::MipsFastISel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a43d3fe2699745c950168939ee8f0d5cb">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::normalizeInfiniteLoopExit</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a48e904486c2be7b98450bc2306c10648">llvm::MachineInstr::print</a>, <a href="/web-llvm/docs/api/classes/llvm/miprinter/#ac9a4f7f4a86744121b96bfb651c60567">llvm::MIPrinter::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a933376a6efcdf3b5910c326b774eb8b3">processBlockAddr</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#aaa1cdfbf8bbbb3d37466c44f0b8a403b">anonymous{ExpandVariadics.cpp}::ExpandVariadics::replaceAllUsesWithNewDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab567bf4900296a78df5fbc74ef1aedce">reportIllegalCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkemitteranalysis/#a362fbd1b0bdfc30a7b45a625fcf582c5">llvm::MachineOptimizationRemarkEmitterAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a97bbf524ee03354bb73dce9614b0e959">llvm::ExecutionEngine::runFunctionAsMain</a>, <a href="/web-llvm/docs/api/classes/llvm/constanthoistingpass/#a778bef41059be563431e55a70168520a">llvm::ConstantHoistingPass::runImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitterwrapperpass/#a645560c675406ac4567a4cb46bbe1824">llvm::OptimizationRemarkEmitterWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/#a208684dda693662f834195df68d843f8">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-xrayinstrumentation-cpp-/xrayinstrumentation/#a4fb91ea8621a93ca73b483592ac6b061">anonymous{XRayInstrumentation.cpp}::XRayInstrumentation::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkemitterpass/#abaf47a746ff0c09836ffb448d4287287">llvm::MachineOptimizationRemarkEmitterPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>, <a href="#a7a383eea189e7af487299e904c0b5fcc">setUWTableKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a1ae624f5747718933b1dabc6a03689aa">tryToOptimizeStoreOfAllocationToGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#abbe8c4ff227aafd9e016eeb143490bcc">validateGroupWaitEventsPtr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#a5ab01ee14799ff74e4ff5e6c5ce8d50c">validateLifetimeStart</a>.</p>

</div>
</div>

### getDataLayout() {#a3275c50993afaf4fdd723640c2c3ca0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout &amp; Function::getDataLayout ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the data layout of the module this function belongs to.</p>


<p>Requires the function to have a parent module.</p>


<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4ad92667dcad9ad33a52a2e1c505a03a">buildOverlapMapAndRecordDeclares</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a16d5e17e2ce1be5012b2d00ab6d6669a">llvm::createMemCpyLoopKnownSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aeb6d0a9254bc3183046873436fc7c12e">llvm::MachineIRBuilder::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/anonymous-inferaddressspaces-cpp-/inferaddressspacesimpl/#a1687b6900e16f26e64d7fe3e463e12c3">anonymous{InferAddressSpaces.cpp}::InferAddressSpacesImpl::run</a>, <a href="/web-llvm/docs/api/classes/llvm/constanthoistingpass/#a778bef41059be563431e55a70168520a">llvm::ConstantHoistingPass::runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a53fcf95621b95aa7165074a98b5df0b3">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-winehprepare-cpp-/winehprepareimpl/#a5026a3f719e275576358dce2b6c31ca5">anonymous{WinEHPrepare.cpp}::WinEHPrepareImpl::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a874edeab85418837bb65d4d2ec4c5d0b">llvm::SITargetLowering::shouldExpandAtomicRMWInIR</a> and <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a263f69437421410a39c26e0be576f028">llvm::PPCTargetLowering::supportsTailCallFor</a>.</p>

</div>
</div>

### getDenormalMode() {#aaf03062dde511bcc74b5d01b0a2b5736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenormalMode Function::getDenormalMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; FPType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the denormal handling type for the default rounding mode of the function.</p>

<p>Declaration at line 713 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 807 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aef9fe930d99fc1baf2a6ae99a59df09e">atomicIgnoresDenormalModeOrFPModeIsFTZ</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a28ddcf99fafe235217356e423dcdd084">anonymous{ConstantFolding.cpp}::constantFoldCanonicalize</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp/#af3c8f5caa60e75e0b9aaad6e11a88722">getInstrDenormalMode</a>.</p>

</div>
</div>

### getDenormalModeF32Raw() {#a6d0575b2a84c3f9fddb78d07721a6535}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenormalMode Function::getDenormalModeF32Raw ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the representational value of "denormal-fp-math-f32".</p>


<p>Code interested in the semantics of the function should use getDenormalMode instead.</p>


<p>Declaration at line 722 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 825 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### getDenormalModeRaw() {#a68e9896416f00cf96b7bcde3afd54e21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenormalMode Function::getDenormalModeRaw ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the representational value of "denormal-fp-math".</p>


<p>Code interested in the semantics of the function should use getDenormalMode instead.</p>


<p>Declaration at line 717 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 819 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### getEntryBlock() {#a169f0c26ef46161741fdd120a806f853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock &amp; llvm::Function::getEntryBlock ()</td>
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



<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a3ec0b920bf30d0e15bace383192691da">front</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa75cdd420a3ce670e2c3b61046f2b8a7">llvm::calculateSEHStateNumbers</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/winehprepare-cpp/#a23260d8f091384125b149c89aaa00a8c">calculateStateNumbersForInvokes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4547a0e8cb23afe1f8767916fd173920">llvm::calculateWinCXXEHStateNumbers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7260773aac0c8769857f551c78b439a3">llvm::createSanitizerCtorAndInitFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a9702d30c99a5459e9565631adf1fdf1b">emitTaskDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a784adc2347b72f745ff1239aef3a3c26">llvm::OpenMPIRBuilder::finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a2295fc872f9e737d27abeffbc9016fbe">findArgParts</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af59c587eddc75748a1e201369cd3dbac">llvm::InstCombinerImpl::freezeOtherUses</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa5c238ef927795521aeb232b467a6cd1">llvm::MemoryDependenceResults::getDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa7240503037f0c0499222a41a5f22d06">llvm::MemoryDependenceResults::getNonLocalCallDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add2fcd2292dd9e51480a2f43d41acfe2">llvm::invertCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a652ede21e988a4de569cdbc7863ea234">isColdCallSite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a3d10b9d22b94edf6deb16010eb260cdc">IsEmptyAtExitFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a6d53d8df2e0ea40eee8a7349563a9df7">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::isExecutedInAlignedRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a365173e63bd73b3ee58033678429636e">isPotentiallyReachable</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainterfnreachabilityfunction/#a6c50862efd6adb69da166ddce9dc912c">anonymous{AttributorAttributes.cpp}::AAInterFnReachabilityFunction::isReachableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a78b9ad4b9b246aab32ff14d856f5769a">llvm::PPCInstrInfo::isSignOrZeroExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a7b4a95aa47d151f0db62f60bafa792d8">memoryIsNotModifiedBetween</a>, <a href="/web-llvm/docs/api/classes/llvm/insertphistrategy/#a55f9b306ebb441abea69179650c2a4ad">llvm::InsertPHIStrategy::mutate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ac89087c7d7dc7ce68b17d57237c170c8">NegateValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad7f49d3dc767d0f0789ffd9e332e7a49">llvm::PrepareToSplitEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#abbc2deb942b00a9d0d19a6613e374168">llvm::JumpThreadingPass::processBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ae1f1125c20c109a1dedb0cafbb501c22">programUndefinedIfUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a6e4c46869d9d198562f7b8628814e407">raiseUserConstantDataAllocasToEntryBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a96b5bd50d8e96b4c76ffc26508ce774d">replaceArgumentUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-constanthoisting-cpp-/constanthoistinglegacypass/#a6d8190a379520af73a22bb1f14b73f1f">anonymous{ConstantHoisting.cpp}::ConstantHoistingLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/simplifycfgopt/#a0cadca6f494db1ccdccb2256e49cb7fe">anonymous{SimplifyCFG.cpp}::SimplifyCFGOpt::simplifyOnce</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>.</p>

</div>
</div>

### getEntryBlock() {#a0da3ad33bda3df0fa6c10d91d3815626}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock &amp; llvm::Function::getEntryBlock ()</td>
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



<p>Definition at line 810 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a3ec0b920bf30d0e15bace383192691da">front</a>.</p>

</div>
</div>

### getEntryCount() {#ac154f7a85081237665c89b83bbd3d7e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ProfileCount &gt; Function::getEntryCount (bool AllowSynthetic=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the entry count for this function.</p>


<p>Entry count is the number of times the function was executed. When AllowSynthetic is false, only pgo_data will be returned.</p>


<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1133 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#a9084ce2576fad285c1c0dc1e165dd4b6">hasProfileData</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>.</p>

</div>
</div>

### getFnAttribute() {#a4c319db4fe05c27cfe55bd133a87414d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Function::getFnAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attribute for the given attribute kind.</p>

<p>Declaration at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 766 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a8f2e0d9db7a457156c4377449c2e0606">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyICallBranchFunnel</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a392f6e72d46ff14ee31481e3452f6c31">llvm::TargetLoweringBase::areJTsAllowed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aef9fe930d99fc1baf2a6ae99a59df09e">atomicIgnoresDenormalModeOrFPModeIsFTZ</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a784adc2347b72f745ff1239aef3a3c26">llvm::OpenMPIRBuilder::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a92e17e524fe1c82a26b5433b6e9715e3">llvm::X86TargetLowering::getStackProbeSymbolName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a4e108201f94f2fe89865e7868390bbf6">getVScaleForTuning</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a20e0ba2c46bef474e31cf8c2f9322db0">llvm::PPCTargetLowering::hasInlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a889bd3ec782a056c71f40ea116bad9b8">llvm::RISCVTargetLowering::hasInlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a20daff715a896d9ada2a604ab403e1f2">llvm::SystemZTargetLowering::hasInlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5cf46104ca48a9577dc4a61cf080003a">llvm::X86TargetLowering::hasInlineStackProbe</a>, <a href="/web-llvm/docs/api/structs/strboolattr/#a420cb13c54df38ffb136df870bf72299">StrBoolAttr::isSet</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abae2fc34bf7e289e53e0abf82feea144">llvm::RISCVTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a141bf09f97adbbe9f512fb1141f37090">llvm::RISCVTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ac8dc1642db124c4da34fbec06040a0c4">llvm::SPIRVCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a68ff609e7f9151e0c2c6a6b1445c9134">llvm::ARMBaseInstrInfo::mergeOutliningCandidateAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a4253df7a10e437a01d42c223e196c0b8">llvm::TargetInstrInfo::mergeOutliningCandidateAttributes</a>, <a href="/web-llvm/docs/api/structs/anonymous-fentryinserter-cpp-/fentryinserter/#ae3c9ad9123c1338bda3254b781eb08fc">anonymous{FEntryInserter.cpp}::FEntryInserter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-patchablefunction-cpp-/patchablefunction/#a11d99203cc91bbd49c59f32943541747">anonymous{PatchableFunction.cpp}::PatchableFunction::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad944e40dbc606e1494923b581c9732f3">llvm::updateMinLegalVectorWidthAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2a5120238e6845643a37d5a4675a5342">llvm::InstCombinerImpl::visitSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a43a1d060dacb05eb645cf91ea86d7bd3">llvm::InstCombinerImpl::visitTrunc</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a>.</p>

</div>
</div>

### getFnAttribute() {#aacaa0c150cd66194d15d1bdd389009e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Function::getFnAttribute (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attribute for the given attribute kind.</p>

<p>Declaration at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 770 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### getFnAttributeAsParsedInteger() {#a4c866d3504a1e0717c8152a590bd6203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t Function::getFnAttributeAsParsedInteger (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind, uint64_t Default=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For a string attribute <span class="doxyComputerOutput">Kind</span>, parse attribute as an integer.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">Default</span> if attribute is not present.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">Default</span> if there is an error parsing the attribute integer, and error is emitted to the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a></p></dd>
</dl>


<p>Declaration at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 778 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a86673715704dada21e3529d93a5376e8">llvm::GCNSubtarget::getNSAThreshold</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ac4e23bdb97cbb1eebd9ddd6606a1006f">llvm::PPCTargetLowering::getStackProbeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#afdb244cc3da7d9ac6bc08afcbc4e3633">llvm::RISCVTargetLowering::getStackProbeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aeff1b472fa1faee625f22113994af4f8">llvm::SystemZTargetLowering::getStackProbeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af64132885aa4151887699b689283e850">llvm::X86TargetLowering::getStackProbeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/stackprotector/#ad6088af9690051701647680fd467ed97">llvm::StackProtector::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-siformmemoryclauses-cpp-/siformmemoryclauses/#a3b412b093194b8e66d1d42d1cc79d692">anonymous{SIFormMemoryClauses.cpp}::SIFormMemoryClauses::runOnMachineFunction</a>.</p>

</div>
</div>

### getFnStackAlign() {#a3494b54c5cae8ae5d9c3008238963e09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign llvm::Function::getFnStackAlign ()</td>
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

<p>Return the stack alignment for the function.</p>

<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### getFunction() {#a8743c58384e11cb6228f6f871304ad35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function &amp; llvm::Function::getFunction ()</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#a8bde7bea5a6d6a50fd5b6d03d746e05b">addMappingsFromTLI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#afca73617f8390579ca48fa10bf1c8edb">assureFPCallStub</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer/#a7c9e3a3c2e449cbc1dfebc37503af252">llvm::orc::ReOptimizeLayer::createReoptimizeCall</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa9a2aed0d26a4fca41f8fc0986a3f12b">llvm::AsmPrinter::doFinalization</a>, <a href="/web-llvm/docs/api/structs/anonymous-preiselintrinsiclowering-cpp-/preiselintrinsiclowering/#a6399ae03a799911dd8f5adcdff15dc8f">anonymous{PreISelIntrinsicLowering.cpp}::PreISelIntrinsicLowering::expandMemIntrinsicUses</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a784adc2347b72f745ff1239aef3a3c26">llvm::OpenMPIRBuilder::finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a0a93e5a229615932f4e2ba47f55a3ba0">FindAtExitLibFunc</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a7dcc7e60c55b76d16688ee3b04f804e4">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::forallInterferingAccesses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aa1731508126b77035ab3ba9d71d5374b">llvm::Intrinsic::getDeclarationIfExists</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo/#a1e347b3d4af60ff4752900497cb60fbb">llvm::BlockFrequencyInfo::getFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a717a199ea9514d956fa87fd23c13a228">llvm::getOrCreateSanitizerCtorAndInitFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a7aeb9c73ff9505a01d6bef9d1f6f6c6e">llvm::AArch64TargetLowering::getSSPStackGuardCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3a6814018ec7443c7df966784ad69064">llvm::ARMTargetLowering::getSSPStackGuardCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a071c6530f4d3362b846fdc1701c216e9">getTLIFunction</a>, <a href="/web-llvm/docs/api/groups/vfdatabase/#ga27014498d4eea7c1e7455cc33538ca2b">llvm::VFDatabase::getVectorizedFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a5640521ba3a9873a718e79f0bc49eadb">hasReturnsTwiceAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyloweremscriptenehsjlj-cpp/#a1e5a795e237da6e01636980c98b645ab">nullifySetjmp</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraph/#a1a066faade450399db380381c68e8b32">llvm::CallGraph::print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a6b42b6fca05063155c689008d30a2751">llvm::AMDGPU::removeFnAttrFromReachable</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyloweremscriptenehsjlj-cpp-/webassemblyloweremscriptenehsjlj/#a4e54683754f6664c17d470ae3a097486">anonymous{WebAssemblyLowerEmscriptenEHSjLj.cpp}::WebAssemblyLowerEmscriptenEHSjLj::runOnModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a484621a748732e2f39e7a2a0058b3b07">llvm::stripDebugifyMetadata</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aef10fb11205c2a096e040dd6b75148eb">llvm::UpgradeARCRuntime</a>.</p>

</div>
</div>

### getFunctionType() {#a21075305f0e463b24aafc2fb99514ace}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType * llvm::Function::getFunctionType ()</td>
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

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> for me.</p>

<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9df55d50aee24118cfdc34ecb32db484">getValueType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#ae5881267e88ebfd0527460a92b61f960">llvm::MatrixBuilder::CreateColumnMajorLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#a69138108d0e5888e6cafcdd27d082fc8">llvm::MatrixBuilder::CreateColumnMajorStore</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ad399adefaffab058aa56567aa1b59df9">llvm::DbgVariableRecord::createDebugIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#afc83c1972006a05871f65fdf15ade10f">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::createHvxIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a0fb8bf2cae796307f012fc621678642f">llvm::IRBuilderBase::CreateLaunderInvariantGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#ac4d302983f7d34c7555b016c5901341a">llvm::MatrixBuilder::CreateMatrixMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#a5342cc18cecbb68eff164826df1476e0">llvm::MatrixBuilder::CreateMatrixTranspose</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#aa0d499612ac66539c8daf29c8eb142a5">llvm::coro::createMustTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#af9f3d0f2901feeff9d52b95e58fbb49b">llvm::IRBuilderBase::CreateStripInvariantGroup</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a8d179b8dd229c1d46eee4c257e717e25">createThunk</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6245f16ff5b8230d2ed89127bf27efa8">llvm::AArch64TargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a68bc08431f00987920ce19e9a458e86d">llvm::ARMTargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a925bbfb44898a7e8da7d6170278aaf71">emitTPIDR2Save</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab05ba39ce6e678149dabd939c9ad4c3e">llvm::InstCombinerImpl::EvaluateInDifferentType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a7b91ad1b09dab040d3519c054e473efb">llvm::TargetLibraryInfoImpl::getLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a>, <a href="#acdd05db170cbfee8a0fcbc047b8504e5">getReturnType</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a5abced3ab870d7abf57f2b35a02cd041">llvm::LoopVectorizationCostModel::getVectorIntrinsicCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiccostattributes/#a6760a5137f8e0ec21dbd7b99e61b52ed">llvm::IntrinsicCostAttributes::IntrinsicCostAttributes</a>, <a href="#af457a58a84b500d44feb7b699aa43ec1">isVarArg</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a41f0cd699a3f8d909d1864c270081883">llvm::HexagonTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae819b62ec706cb229654ea5fb6553501">llvm::lowerGlobalIFuncUsersAsGlobalCtor</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfounsupported/#a12864403c3efdae1dac8ca322dedf9ba">llvm::DiagnosticInfoUnsupported::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#a1e38dc7f1aecace87c3977df3d96e680">processCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a3ce5fd3a8d74ecd38fdb5e27f85d2d61">llvm::Intrinsic::remangleIntrinsicFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a7e2cad7ab18db9a3c940afc609c223dc">replaceCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a97bbf524ee03354bb73dce9614b0e959">llvm::ExecutionEngine::runFunctionAsMain</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a40b5636c9d406c277f51dcdcba06821f">anonymous{ExpandVariadics.cpp}::ExpandVariadics::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyloweremscriptenehsjlj-cpp-/webassemblyloweremscriptenehsjlj/#a4e54683754f6664c17d470ae3a097486">anonymous{WebAssemblyLowerEmscriptenEHSjLj.cpp}::WebAssemblyLowerEmscriptenEHSjLj::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aee56a5257c4899bf97c5957d87a732e3">llvm::CallBase::setCalledFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef10fb11205c2a096e040dd6b75148eb">llvm::UpgradeARCRuntime</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>.</p>

</div>
</div>

### getGC() {#aa180549a789e99a98e599e8e183c4773}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; Function::getGC ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 835 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>.</p>

</div>
</div>

### getImportGUIDs() {#a786802ed087c3a22a667532d2930087a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt; GlobalValue::GUID &gt; Function::getImportGUIDs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the set of GUIDs that needs to be imported to the function for sample PGO, to enable the same inlines as the profiled optimized binary.</p>

<p>Declaration at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1155 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### getInstructionCount() {#af67f86066ad1891d424553b352dfa821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Function::getInstructionCount ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of non-debug IR instructions in this function.</p>


<p>This is equivalent to the sum of the sizes of each basic block contained within this function.</p>


<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#aec04f4ee74f001679174332506c0cebc">DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a>.</p>

</div>
</div>

### getIntrinsicID() {#a4d0a7baab8d078065b2de10e3460892a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Intrinsic::ID llvm::Function::getIntrinsicID ()</td>
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

<p>getIntrinsicID - This method returns the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> number of the specified function, or <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a35fedf4db6d756bd82501607f93c1e79aab5fb650050f184fa7c19c26abde5226">Intrinsic::not_intrinsic</a> if the function is not an intrinsic, or if the pointer is null.</p>


<p>This value is always defined to be zero to allow easy checking for whether a function is intrinsic or not. The particular intrinsic functions which correspond to this value are defined in llvm/Intrinsics.h.</p>


<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a4fb893b6154100a981579b7b5cb3e638">llvm::GlobalValue::IntID</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ab8e0eab61769d9974aeed9345ce11baf">LLVM_READONLY</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#ae52dc32e051ded6356e4065b75d19935">addIntrinsicToSummary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bf41f2408094f54097744991c82336a">llvm::calculateCXXStateForAsynchEH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b49442c1c01ddc388c51d7599c0f876">llvm::calculateSEHStateForAsynchEH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8148654fcf3528ef06d7a0e28b57b952">llvm::findDevirtualizableCallsForTypeCheckedLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af88f364cd09c715e8853a1027c7180ef">llvm::findDevirtualizableCallsForTypeTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a41caa0b8eaefb07b7f8fcf19b05bb249">FindPreallocatedCall</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#a7ff64b3625b6f9020556ed05a5f72af4">llvm::IntrinsicInst::getIntrinsicID</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#a6ac9067dc7c125cd83855df3e480e04c">handleBrSelExpect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#aea5dd05a61257355d99f96d8d6dc9f94">handlePhiDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#ab61a60817533b84f369d2623e0593ec7">handleSwitchExpect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a23cf1bbd780f1998b4c61acbf5a35a78">hasOnlyColdCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp/#a71bb9fbc36358e29483641f8cab80003">isIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab5b261757331e18b934bba9c3d3e6b69">lowerAwaitSuspend</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#ad2fd6546e0f1cc42311962f4ad4b29cd">lowerExpectIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a7f0607e63d19dd3d4fb6edcef16bc26e">optimizeDoubleFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptximageoptimizer-cpp-/nvptximageoptimizer/#a70631a00c85109b54d2e816daae4f03a">anonymous{NVPTXImageOptimizer.cpp}::NVPTXImageOptimizer::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a021e32e2bf67f331d9384a162dc402c2">anonymous{WholeProgramDevirt.cpp}::DevirtModule::scanTypeCheckedLoadUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a463056de56ab82cc6e2c50e5ccf17626">shouldCheckArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a> and <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a4abe522bf135a7628b059cf5fc0be127">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::VisitCallInst</a>.</p>

</div>
</div>

### getMaxBlockNumber() {#a4528b445a4b11cf13675dcaf20c4f27a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Function::getMaxBlockNumber ()</td>
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

<p>Return a value larger than the largest block number.</p>


<p>Intended to allocate a vector that is sufficiently large to hold all blocks indexed by their number.</p>


<p>Definition at line 828 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### getMemoryEffects() {#a530ec44ae594c349ccac0b065735a001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffects Function::getMemoryEffects ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 876 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### getParamAlign() {#a97fb0bcc88f78900c3d4780d963540e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign llvm::Function::getParamAlign (unsigned ArgNo)</td>
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



<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroelide-cpp/#ab84f45c90b0a077dc816716b915367f6">getFrameLayout</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a> and <a href="/web-llvm/docs/api/structs/llvm/coroannotationelidepass/#a411202dc502ac666302ba81c40e94b10">llvm::CoroAnnotationElidePass::run</a>.</p>

</div>
</div>

### getParamAttribute() {#a28eb38953dee4718455ab384f21f638c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Function::getParamAttribute (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>gets the specified attribute from the list of attributes.</p>

<p>Declaration at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 792 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### getParamByRefType() {#a80155b6dbeda6df7d2c106b89fe1027e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::Function::getParamByRefType (unsigned ArgNo)</td>
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

<p>Extract the byref type for a parameter.</p>

<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### getParamByValType() {#a669daedc0f098c6b21ad743df19e1d73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::Function::getParamByValType (unsigned ArgNo)</td>
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

<p>Extract the byval type for a parameter.</p>

<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### getParamDereferenceableBytes() {#a5a457ddc9964340847b216e105b8eb32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::Function::getParamDereferenceableBytes (unsigned ArgNo)</td>
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

<p>Extract the number of dereferenceable bytes for a parameter.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ArgNo</td>
<td class="doxyParamItemDescription"><p>Index of an argument, with 0 being the first function arg.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroelide-cpp/#ab84f45c90b0a077dc816716b915367f6">getFrameLayout</a> and <a href="/web-llvm/docs/api/structs/llvm/coroannotationelidepass/#a411202dc502ac666302ba81c40e94b10">llvm::CoroAnnotationElidePass::run</a>.</p>

</div>
</div>

### getParamDereferenceableOrNullBytes() {#a8b1396e0135cc83920828f81ce53d71d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::Function::getParamDereferenceableOrNullBytes (unsigned ArgNo)</td>
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

<p>Extract the number of dereferenceable_or_null bytes for a parameter.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ArgNo</td>
<td class="doxyParamItemDescription"><p>AttributeList ArgNo, referring to an argument.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### getParamInAllocaType() {#ab1f37b7f4032fef91001845b5f506e66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::Function::getParamInAllocaType (unsigned ArgNo)</td>
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

<p>Extract the inalloca type for a parameter.</p>

<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### getParamNoFPClass() {#a67810dc8301ddb65ca4ce52d4a446af1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FPClassTest llvm::Function::getParamNoFPClass (unsigned ArgNo)</td>
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

<p>Extract the nofpclass attribute for a parameter.</p>

<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### getParamPreallocatedType() {#a9e292c5881887f1c1bfb54bcda262b32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::Function::getParamPreallocatedType (unsigned ArgNo)</td>
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

<p>Extract the preallocated type for a parameter.</p>

<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### getParamStackAlign() {#ac667b0a43e49f4e4ae4e1d558f37df8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign llvm::Function::getParamStackAlign (unsigned ArgNo)</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### getParamStructRetType() {#aeb2fec27f03901fdf633971423877345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::Function::getParamStructRetType (unsigned ArgNo)</td>
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

<p>Extract the sret type for a parameter.</p>

<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### getPersonalityFn() {#a6f77e4e800ba4dffd63e8ddb330062aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * Function::getPersonalityFn ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the personality function associated with this function.</p>

<p>Declaration at line 910 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1048 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo/#a183e3a3a68925c5689cd2149c940f59e">llvm::LoopSafetyInfo::computeBlockColors</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#a756acce5a5adef291dc50593ce6d56a4">llvm::XCoreFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a87a3c3fc7fc8bc05db24005a6d38b5b2">llvm::AArch64TargetLowering::EmitLoweredCatchRet</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#afc48ca3b84128ca1b9ab1701d4f30b8c">llvm::XCoreFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afa141935f9c9a1ad9c785d7b6200b119">llvm::getEHScopeMembership</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3638f5716ead3f20d8d8e348c10d8619">getSEHRegistrationNodeSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa13f60350a3e19e1791fd628b694da36">llvm::MachineBasicBlock::liveout_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a7b0d8ca3c0557ce032023f8b3c525329">needFuncLabels</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a6a8d1523f211998978b3fa0bfe8818a1">llvm::X86FrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afc0900cd962cd955b2b6de25731710f5">llvm::X86FrameLowering::restoreWinEHStackPointersInParent</a>, <a href="/web-llvm/docs/api/classes/anonymous-winehprepare-cpp-/winehprepareimpl/#a5026a3f719e275576358dce2b6c31ca5">anonymous{WinEHPrepare.cpp}::WinEHPrepareImpl::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/stackprotector/#ad6088af9690051701647680fd467ed97">llvm::StackProtector::runOnFunction</a>.</p>

</div>
</div>

### getPrefixData() {#ae24606acf52aa6444bfd2b4848a1ae27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * Function::getPrefixData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the prefix data associated with this function.</p>

<p>Declaration at line 919 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1058 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>.</p>

</div>
</div>

### getPrologueData() {#a6dfe213825f2e052d5dd376b3ce182d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * Function::getPrologueData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the prologue data associated with this function.</p>

<p>Declaration at line 928 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1068 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>.</p>

</div>
</div>

### getRetAttribute() {#afff5709a997763240c888e86db09e4e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Function::getRetAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attribute for the given attribute kind for the return value.</p>

<p>Declaration at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 774 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### getReturnType() {#acdd05db170cbfee8a0fcbc047b8504e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::Function::getReturnType ()</td>
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

<p>Returns the type of the ret val.</p>

<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a21075305f0e463b24aafc2fb99514ace">getFunctionType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#afca73617f8390579ca48fa10bf1c8edb">assureFPCallStub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a1548d6cc07c1c5595817e73713d58a23">copyMustTailReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7e0a0c76340ba1fc52863f538f3e703d">llvm::IRBuilderBase::CreateBinaryIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a0fb8bf2cae796307f012fc621678642f">llvm::IRBuilderBase::CreateLaunderInvariantGroup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8829536a23c01dcd3a6017dccb148c90">llvm::createLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#af9f3d0f2901feeff9d52b95e58fbb49b">llvm::IRBuilderBase::CreateStripInvariantGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a784adc2347b72f745ff1239aef3a3c26">llvm::OpenMPIRBuilder::finalize</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a6a0e4ff765ad5ab3c9a53c917f3cf1cd">llvm::IRPosition::getAssociatedType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a78b9ad4b9b246aab32ff14d856f5769a">llvm::PPCInstrInfo::isSignOrZeroExtended</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a273e9b97fc0dfec8df7cf4294d9b87fe">llvm::Attributor::isValidFunctionSignatureRewrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a0f104a4f4a7edce928ac0aea2a3509b8">lowerFunnelShifts</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a5f7819dcae52567c11033d63e3d6421a">llvm::NVPTXTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27aee52717271be9e79135bfaab890ce">llvm::makeGuardControlFlowExplicit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#a039c5bd63f390c0b66e2548b69a372c5">llvm::VPWidenCallRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a263f69437421410a39c26e0be576f028">llvm::PPCTargetLowering::supportsTailCallFor</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>.</p>

</div>
</div>

### getSectionPrefix() {#a11ab3c8bd6ff4445d7cb45a62806353b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; StringRef &gt; Function::getSectionPrefix ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the section prefix for this function.</p>

<p>Declaration at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1173 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae0b0cbf92a3dd0f5cab9d5d3067c2003">llvm::TargetInstrInfo::isFunctionSafeToSplit</a>.</p>

</div>
</div>

### getSubprogram() {#a4d834f9897d15e3a6349063b5d637cd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DISubprogram * Function::getSubprogram ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the attached subprogram.</p>


<p>Calls <em><a href="/web-llvm/docs/api/classes/llvm/globalobject/#aef569d822dbf572ae71954d6831ce8a9">getMetadata()</a></em> with <em>LLVMContext::MD_dbg</em> and casts the result to <em><a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a></em>.</p>


<p>Declaration at line 1022 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1874 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a> and <a href="/web-llvm/docs/api/classes/llvm/globalobject/#aef569d822dbf572ae71954d6831ce8a9">llvm::GlobalObject::getMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/#a6e46a83de20d6656e5c4605b775da75b">llvm::LiveDebugVariables::analyze</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a19cc77dc725d4cbbf994e5db311e3c97">applyFirstDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#af5b3d468d882817a49ac012840023d10">llvm::BTFDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#af89d6d0bd3c47fc34cb897ea7131f9ac">llvm::DwarfDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a6ae5e1ec2093c40fa0e3211bd043057b">llvm::DwarfDebug::beginInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4576d69ed1543b06e5c41eb43b630bf1">llvm::Instruction::dropLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#ab0627dac3e2666638fa514a2d98299ef">llvm::DwarfDebug::emitInitialLocDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#a95c1eb0bb9394b39e6edb45ae6a57bfe">llvm::CodeViewDebug::endFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a8f0353f65281b2b560d4421d439ed836">llvm::DwarfDebug::endFunctionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a94b383e649f60242503ff47c799fd22e">HandleByValArgumentInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp/#a9810fe86e30b35178c82eeb9d29811d8">hasDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/lexicalscopes/#a3134ce614dc1b5fc41522648d24ff7cb">llvm::LexicalScopes::initialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa730b58924baf8f35394c2e5a0bb3714">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctions</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#ae0bf03df2431c543590180658ce4709d">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctionsWithPriority</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-removeredundantdebugvalues-cpp-/removeredundantdebugvalues/#af87a39c456cb631fbfe819b58d183598">anonymous{RemoveRedundantDebugValues.cpp}::RemoveRedundantDebugValues::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-shrinkwrap-cpp-/shrinkwrap/#a0b77b3bd867840460e8de5e83245240e">anonymous{ShrinkWrap.cpp}::ShrinkWrap::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/#a208684dda693662f834195df68d843f8">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a356f9de405c2904f7ad73659a2f378a0">llvm::Legalizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a07f4133008c7c11a0154735071ffcc19">llvm::InstructionSelect::selectMachineFunction</a> and <a href="#a7345f1a973f5084e01c183cad89399d5">shouldEmitDebugInfoForProfiling</a>.</p>

</div>
</div>

### getUWTableKind() {#a7e181b32a135b15eb712e81ffe52ea50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UWTableKind llvm::Function::getUWTableKind ()</td>
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

<p>Get what kind of unwind table entry to generate for this function.</p>

<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Referenced by <a href="#acabf5ba443b4e5327f547ae8fc04a98c">hasUWTable</a>.</p>

</div>
</div>

### getValueSymbolTable() {#a9b03fcd02236ef6a4a1e59790bdca48a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueSymbolTable * llvm::Function::getValueSymbolTable ()</td>
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

<p>getSymbolTable() - Return the symbol table if any, otherwise nullptr.</p>

<p>Definition at line 817 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a35017776f5e9dd9dbc7f71d56a77135a">parseIRValue</a>.</p>

</div>
</div>

### getValueSymbolTable() {#a033f8a22965054cb1a03fa98b9d61677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ValueSymbolTable * llvm::Function::getValueSymbolTable ()</td>
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



<p>Definition at line 818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### hasAddressTaken() {#a1b87b14bb6dd4f14bb42c73d2085673e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::hasAddressTaken (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> ** PutOffender=nullptr, bool IgnoreCallbackUses=false, bool IgnoreAssumeLikeCalls=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool IgnoreLLVMUsed=false, bool IgnoreARCAttachedCall=false, bool IgnoreCastedDirectCall=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>hasAddressTaken - returns true if there are any uses of this function other than direct calls or invokes to it, or blockaddress expressions.</p>


<p>hasAddressTaken - returns true if there are any uses of this function other than direct calls or invokes to it.</p>


<p>Optionally passes back an offending user for diagnostic purposes, ignores callback uses, assume like pointer annotation calls, references in llvm.used and llvm.compiler.used variables, operand bundle "clang.arc.attachedcall", and direct calls with a different call site signature (the function is implicitly casted).</p>


<p>Optionally ignores callback uses, assume like pointer annotation calls, and references in llvm.used and llvm.compiler.used variables.</p>


<p>Declaration at line 997 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 955 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### hasAttributeAtIndex() {#a5d53cff701a33669d57f1a55cb4b84cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::hasAttributeAtIndex (unsigned Idx, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if attribute of the given kind is set at the given index.</p>

<p>Declaration at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### hasFnAttribute() {#afb28a4deafe2954b0534cc6399ce518b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::hasFnAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the function has the attribute.</p>

<p>Declaration at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a40bdcac44bd6d189cc6b65984baf3303">llvm::AArch64TargetLowering::canMergeStoresTo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a66a0f33d36e31ddfbd254a77524f9192">llvm::X86TargetLowering::canMergeStoresTo</a>, <a href="#a432063a2bc02df1d1c93957c644e966c">cannotDuplicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a24ff4e69025be7564b19025b93cac8d9">canTransformToMemCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a12d8c4c294b19351dbee6ab588676012">checkNumAlignedDPRCS2Regs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a57f2ddafb29f40fe83f17e93300e1a71">combineVectorSizedSetCCEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a058c4d3a1147ae3ec1098c3031fe32cb">llvm::CSKYFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a2f26766f4dcfa6457ba405584a34d5c3">llvm::TargetFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ac2efa5f4dacdde70f912da43c1f8ffcf">llvm::PPCFrameLowering::determineFrameLayout</a>, <a href="#a58e9603fcbb784bee436392db60d93f1">doesNoCfCheck</a>, <a href="#aaf2ec1eb99cc826eea1a7dd8a8ea570a">doesNotFreeMemory</a>, <a href="#a4e5c42dc883d0deb41a668301cd5ac72">doesNotRecurse</a>, <a href="#ab8ef748e928424955da3d1f6676b25d9">doesNotReturn</a>, <a href="#a81f38aca859ffeda166f8c385f7d55a5">doesNotThrow</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a91da910cd583aea849621cbf8147fe28">llvm::PPCRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a212384cdd746eaffedb7edc7a16a1cef">llvm::PPCTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#aeb6b320000ce736d5ac68e606fcc3519">llvm::MipsSEFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a80326c86cd0c224fcea6c5b654870747">llvm::CSKYFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#ae528e90e0e85a0d0597982913065596c">llvm::MipsSEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#adcff3487a7ab24e32ed892aedf767cf1">emitSCSEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#acf179a5b6cfdcd80b458b93d503e0ed0">emitSCSPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#af8af2c60dc7e78f9efb7eee80b31a183">llvm::ARMFrameLowering::enableCalleeSaveSkip</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a37c34f0aa56d8aafa1238290de1fecc9">llvm::TargetFrameLowering::enableCalleeSaveSkip</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7e24606b8fe6124decedb17e5ffa405e">llvm::X86FrameLowering::enableShrinkWrapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa59c4ae8c95bb222039942e9ba995c3e">llvm::expandAtomicRMWToCmpXchg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a2ed4f37fbda15a9c05f333fde59e9fbb">fixupLineNumbers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a7134dae528abf2cf2ef1bd1d92f9ce39">foldLogOpOfMaskedICmps_NotAllZeros_BMask_Mixed</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#af11871b65a6cfc7ce8fc20403e18ab40">llvm::AArch64Subtarget::getAuthenticatedLRCheckMethod</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyregisterinfo/#aed7852ec76ac1a562fc80faf5d228cf5">llvm::CSKYRegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a24c02ac750fe944f0902c120ed0e773d">llvm::RISCVRegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#af9d07c5d74dcf9baf1693e4c7a98074b">llvm::X86RegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a2a4f0d74a9e54517b5009c2ac31503b5">llvm::AArch64RegisterInfo::getCallPreservedMask</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab860729e618e5a2dd9e7e0feccdbe7e3">llvm::AArch64FrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a5ecc0bb5ee3eac043a66ce779ad05747">llvm::AArch64Subtarget::getPtrAuthBlockAddressDiscriminatorIfEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#ab03f0084e766f3636a1eb7832061fd94">llvm::MipsRegisterInfo::getReservedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a92e17e524fe1c82a26b5433b6e9715e3">llvm::X86TargetLowering::getStackProbeSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a135ff03665f8746c89e91d3b802a1017">llvm::AArch64RegisterInfo::getStrictlyReservedRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a4e108201f94f2fe89865e7868390bbf6">getVScaleForTuning</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a009e40a8d70eae94c4dc32285c717732">llvm::X86FrameLowering::has128ByteRedZone</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a20e0ba2c46bef474e31cf8c2f9322db0">llvm::PPCTargetLowering::hasInlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a889bd3ec782a056c71f40ea116bad9b8">llvm::RISCVTargetLowering::hasInlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a20daff715a896d9ada2a604ab403e1f2">llvm::SystemZTargetLowering::hasInlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5cf46104ca48a9577dc4a61cf080003a">llvm::X86TargetLowering::hasInlineStackProbe</a>, <a href="#a548cfb9440f36ba67fc5566b8e967fc6">hasMinSize</a>, <a href="#a808de46fdb41ab44e0711fc06eda13ca">hasNoSync</a>, <a href="#a9c38a8cc0a38636c95bd2826de9d72d4">hasOptNone</a>, <a href="#a1c455e007178a24dfb18ac0e200ea02c">hasOptSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a5640521ba3a9873a718e79f0bc49eadb">hasReturnsTwiceAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aaaed10441dd729ce9fdc91120f2a77f0">llvm::AArch64RegisterInfo::isAsmClobberable</a>, <a href="#a049de2366079104e70f0c3451b09aebf">isConvergent</a>, <a href="#ac02f761bf4c83638d32b8459c82116bb">isCoroOnlyDestroyWhenComplete</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp/#ac0001ca0e66f6badb71cca036c24cab0">isNoReturnDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#adbaec5588449adc75116f4cad3997a03">llvm::omp::isOpenMPKernel</a>, <a href="#a9f6ec3f2263a0ed9418c0968cf7c265e">isPresplitCoroutine</a>, <a href="/web-llvm/docs/api/structs/enumattr/#af1137cf8ba90e0439a0d3c3dab98eff0">EnumAttr::isSet</a>, <a href="#a5cbc3ad9ede9ff8b2012e46bfb997e76">isSpeculatable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a62712c499928ed783ba6329269bbc8f9">LowerATOMIC_STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac963dddf8453fc717992d3ce36a27d8b">llvm::lowerAtomicRMWInst</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a68ff609e7f9151e0c2c6a6b1445c9134">llvm::ARMBaseInstrInfo::mergeOutliningCandidateAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a4253df7a10e437a01d42c223e196c0b8">llvm::TargetInstrInfo::mergeOutliningCandidateAttributes</a>, <a href="#a41ebfca5fde82030f9d559dc34082ef6">mustProgress</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a11b74a0fb5ceb4340d1d7a6f809e0a28">llvm::PPCFrameLowering::needsFP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a0a6cffdcc5341dcc150620c684528de6">llvm::AArch64FunctionInfo::needsShadowCallStackPrologueEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2a5ac33b69bb7d7687d12dc0dffe9f08">performBRCONDCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aae5bad356a0c0583ebad92fbe899230c">llvm::PPCFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipreallocatewwmregs-cpp-/sipreallocatewwmregs/#a76023b4bfaa1fd397186a736b537be99">anonymous{SIPreAllocateWWMRegs.cpp}::SIPreAllocateWWMRegs::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a53fcf95621b95aa7165074a98b5df0b3">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64speculationhardening-cpp-/aarch64speculationhardening/#af74e0cf10108e72a325bb16d56926dec">anonymous{AArch64SpeculationHardening.cpp}::AArch64SpeculationHardening::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-patchablefunction-cpp-/patchablefunction/#a11d99203cc91bbd49c59f32943541747">anonymous{PatchableFunction.cpp}::PatchableFunction::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86dynallocaexpander-cpp-/x86dynallocaexpander/#a8216d146c993c13133c29a28efdded4c">anonymous{X86DynAllocaExpander.cpp}::X86DynAllocaExpander::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86insertwait-cpp-/waitinsert/#acddf9e1c3a065fa8960fee98505de360">anonymous{X86InsertWait.cpp}::WaitInsert::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86returnthunks-cpp-/x86returnthunks/#ab4a10d58e295ec66ff8c9c1d3eeb0529">anonymous{X86ReturnThunks.cpp}::X86ReturnThunks::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86speculativeloadhardening-cpp-/x86speculativeloadhardeningpass/#a862b3b4b5ed250fcfb2d6f9a130f4a0c">anonymous{X86SpeculativeLoadHardening.cpp}::X86SpeculativeLoadHardeningPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#ae2b97aec15d3a340e6d2eab0f467aa0a">llvm::Attributor::shouldInitialize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab499fb31e894a900402d0871eee39b75">llvm::MachineFunction::shouldSplitStack</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/simplifycfgopt/#a0cadca6f494db1ccdccb2256e49cb7fe">anonymous{SimplifyCFG.cpp}::SimplifyCFGOpt::simplifyOnce</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a42ba26b731da85ec85d9f4ebb7d27e02">llvm::PPCFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a049804b3fe8b5e8ddea9a1d2c15882b9">llvm::AArch64TargetLowering::supportSplitCSR</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#af1fb897c419e6a5080ecf54baf13f169">llvm::JumpThreadingPass::tryToUnfoldSelectInCurrBB</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a9e53ebf2b443013c10d250085799adfc">llvm::SystemZELFFrameLowering::usePackedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmachinefunctioninfo/#a96dd72f1aba111c3927d4c600a643618">llvm::RISCVMachineFunctionInfo::useSaveRestoreLibCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2a5120238e6845643a37d5a4675a5342">llvm::InstCombinerImpl::visitSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a43a1d060dacb05eb645cf91ea86d7bd3">llvm::InstCombinerImpl::visitTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a> and <a href="#a48e10a01350fafd3df5828061787a97e">willReturn</a>.</p>

</div>
</div>

### hasFnAttribute() {#abed260ec7cc3f660000905763dbb4f90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::hasFnAttribute (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the function has the attribute.</p>

<p>Declaration at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 735 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### hasGC() {#a5e63b88c979e47ac7da57890a45bd2c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::hasGC ()</td>
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

<p>hasGC/getGC/setGC/clearGC - The name of the garbage collection algorithm to use during code generation.</p>

<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#a05810d77360abad7ef2848184726d872">llvm::Value::getSubclassDataFromValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a12c711c62171c14dcedca2db5874d33e">llvm::SelectionDAGISel::initializeAnalysisResults</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#aafadfc35831cdb7ef3dd321cc28f1208">llvm::SelectionDAGISel::initializeAnalysisResults</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/gcmachinecodeanalysis/#a82b0862f6017d073489a4971d43ecf3a">anonymous{GCRootLowering.cpp}::GCMachineCodeAnalysis::runOnMachineFunction</a>.</p>

</div>
</div>

### hasLazyArguments() {#ad93d1f4325f9ecee231d5f62adf8d74e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::hasLazyArguments ()</td>
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

<p>hasLazyArguments/CheckLazyArguments - The argument list of a function is built on demand, so that the list isn't allocated until the first client needs it.</p>


<p>The hasLazyArguments predicate returns true if the arg list hasn't been set up yet.</p>


<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#a05810d77360abad7ef2848184726d872">llvm::Value::getSubclassDataFromValue</a>.</p>


<p>Referenced by <a href="#a4d6fd92c5a6d2931b039e6405475322f">TargetLibraryInfoImpl</a>.</p>

</div>
</div>

### hasMinSize() {#a548cfb9440f36ba67fc5566b8e967fc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::hasMinSize ()</td>
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

<p>Optimize this function for minimum size (-Oz).</p>

<p>Definition at line 704 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#afb28a4deafe2954b0534cc6399ce518b">hasFnAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a76ff59dafad74689cfe1966b0ed9fa3c">analyzeLoopUnrollCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba1e500fbed9b5849bfd76724ccf3825">combineFMinNumFMaxNum</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adc36484c228b0ce9652f549d04ae4e6e">combineMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa4a1701790033b3d84938d44c913da11">EmitCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-cpp/#a6d50362e845dcbafcf632cb5b98b240f">emitConstantSizeRepmov</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-cpp/#ac6a86b853c0a0262731e7e8b084c0980">emitConstantSizeRepstos</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-expandmemcmp-cpp-/#aa507b512719f5e8d2b31c99f5534541b">anonymous{ExpandMemCmp.cpp}::expandMemCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a38a4767fc581ef400cbef34ac25d9f6c">expandMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad600d9077d7e1eadff1334ee14f7f25a">llvm::foldBranchToCommonDest</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aec4538d6aec6f79de5c3b56115fd2c78">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a20228b431bb0e2852055ea7815a46743">llvm::ARMSubtarget::getGPRAllocationOrder</a>, <a href="#a1c455e007178a24dfb18ac0e200ea02c">hasOptSize</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a6a5ef234051f5fe582e5fa53d655d3d9">llvm::ARMSubtarget::ignoreCSRForAllocationOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonframelowering-cpp/#abd143f89188f4df2b31eaf5f03badd92">isMinSize</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6667df004a39c249e82595e8c06841ca">llvm::AArch64TargetLowering::preferredShiftLegalizationStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d4b243bcdfea88060ffa51fa30683fb">llvm::RISCVTargetLowering::preferredShiftLegalizationStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a3bcf75579cf117a1b83a27dbe4d775d6">llvm::X86TargetLowering::preferredShiftLegalizationStrategy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab81263b19a504166d5c027a21cc15740">reduceVMULWidth</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionalcompares-cpp-/aarch64conditionalcompares/#af7b7982c58340c2b9b066e30a4fd558f">anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvmakecompressible-cpp-/riscvmakecompressibleopt/#a76561cc6613d04a06e24640760923da2">anonymous{RISCVMakeCompressible.cpp}::RISCVMakeCompressibleOpt::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a755eb2d2f25e8da3b2d904146e61b1a5">shouldLowerMemFuncForSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a071d371524d9b324ba9c5cc489ee3da6">shouldLowerMemFuncForSize</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a773d4ec5eecb09f98e46019e6bf0194e">llvm::ARMBaseInstrInfo::shouldOutlineFromFunctionByDefault</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ac1326b52721d728a3551b1433ded0f9a">llvm::RISCVInstrInfo::shouldOutlineFromFunctionByDefault</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bbdb7f279f14b5f7ff6d7d9a2a97765">splitStores</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a0b4c48d53ab1ddc5bf009cd4ddffdc5a">validateAndCostRequiredSelects</a>.</p>

</div>
</div>

### hasNoSync() {#a808de46fdb41ab44e0711fc06eda13ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::hasNoSync ()</td>
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

<p>Determine if the call can synchroize with other threads.</p>

<p>Definition at line 638 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#afb28a4deafe2954b0534cc6399ce518b">hasFnAttribute</a>.</p>

</div>
</div>

### hasOptNone() {#a9c38a8cc0a38636c95bd2826de9d72d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::hasOptNone ()</td>
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

<p>Do not optimize this function (-O0).</p>

<p>Definition at line 701 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#afb28a4deafe2954b0534cc6399ce518b">hasFnAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#aae3dc5c42dd9f35a3cbf188a5de118bf">llvm::LoongArchFrameLowering::enableShrinkWrapping</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a1fdd175ee23fc8aaf606ccbb71ce040c">llvm::RISCVFrameLowering::enableShrinkWrapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonframelowering-cpp/#a18a4e42f7e87c45cc17df255466262db">isOptNone</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndppcombinepass/#a91369071e0136a16498790096d679182">llvm::GCNDPPCombinePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagiselpass/#afbe031a5b54a7910faf25270aeeac0dc">llvm::SelectionDAGISelPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/siloadstoreoptimizerpass/#a73bd665c6e03c1dc196c107a450e228a">llvm::SILoadStoreOptimizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sipeepholesdwapass/#af333339d4156056152073cbe27eb1887">llvm::SIPeepholeSDWAPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sishrinkinstructionspass/#aef43f9ae6fbd079affe6f0f2a07d034e">llvm::SIShrinkInstructionsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/twoaddressinstructionpass/#ab9a6f420b6121320d58d159773b8d92a">llvm::TwoAddressInstructionPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a98e4a98a0db786235d78fce93ad4a72f">llvm::InstructionSelect::runOnMachineFunction</a>.</p>

</div>
</div>

### hasOptSize() {#a1c455e007178a24dfb18ac0e200ea02c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::hasOptSize ()</td>
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

<p>Optimize this function for size (-Os) or minimum size (-Oz).</p>

<p>Definition at line 707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="#afb28a4deafe2954b0534cc6399ce518b">hasFnAttribute</a> and <a href="#a548cfb9440f36ba67fc5566b8e967fc6">hasMinSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp/#aa71d343a68eaa436458cd76f349f399a">AlignBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa9430ae4ad548095743aa0a26b235d82">llvm::AArch64InstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8dae5a29dc37de048a59e5bab5e30af2">combineFMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0f13d1cf96cb32fba6d7ed4bd50ba5f">combineFMADDSUB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7a388b8e71542c8223c73a0d99691c71">combineFneg</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a625caa931f0d8ef201041febbfe42cca">llvm::InnerLoopVectorizer::emitMemRuntimeChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a30c4bcea7beb42c7eb075a578bc3bc3e">llvm::InnerLoopVectorizer::emitSCEVChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a7cfc0ecfec922ebf19bd023f3b675604">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aec4538d6aec6f79de5c3b56115fd2c78">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a3b717a7e33b86028f34e9d31aca68abb">llvm::HexagonTargetLowering::LowerFDIV</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64storepairsuppress-cpp-/aarch64storepairsuppress/#ab876191f2b64955413fe0423a672c3b2">anonymous{AArch64StorePairSuppress.cpp}::AArch64StorePairSuppress::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-thumb2sizereduction-cpp-/thumb2sizereduce/#a0c70c731d0c61ed9a18b61ea303aa44c">anonymous{Thumb2SizeReduction.cpp}::Thumb2SizeReduce::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fixupleas-cpp-/fixupleapass/#a12fbadb122d7381f6222cab24d3150e5">anonymous{X86FixupLEAs.cpp}::FixupLEAPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86padshortfunction-cpp-/padshortfunc/#a396d8bcf59a3557450bf806512b47e3d">anonymous{X86PadShortFunction.cpp}::PadShortFunc::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a755eb2d2f25e8da3b2d904146e61b1a5">shouldLowerMemFuncForSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a994d8b93d52a786748213d2cb98f1000">llvm::shouldOptimizeForSize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3af72f14ea20f2c762c751d2d49e5ea3">llvm::shouldOptimizeForSize</a>.</p>

</div>
</div>

### hasParamAttribute() {#a5c8e58da4c28ac380a697fcb2f1ddaa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::hasParamAttribute (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>check if an attributes is in the list of attributes.</p>

<p>Declaration at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 743 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### hasParamAttribute() {#afc02f5ba395bfe8a3a81815d37621494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::hasParamAttribute (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if an attribute is in the list of attributes.</p>

<p>Declaration at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 748 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### hasPersonalityFn() {#a6a0f6312963ee6fb0969243607174949}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::hasPersonalityFn ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this function has a personality function.</p>

<p>Definition at line 905 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#a05810d77360abad7ef2848184726d872">llvm::Value::getSubclassDataFromValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo/#a183e3a3a68925c5689cd2149c940f59e">llvm::LoopSafetyInfo::computeBlockColors</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#a756acce5a5adef291dc50593ce6d56a4">llvm::XCoreFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#afc48ca3b84128ca1b9ab1701d4f30b8c">llvm::XCoreFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3638f5716ead3f20d8d8e348c10d8619">getSEHRegistrationNodeSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa13f60350a3e19e1791fd628b694da36">llvm::MachineBasicBlock::liveout_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a7b0d8ca3c0557ce032023f8b3c525329">needFuncLabels</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#a3b2bec8faee9b97ef8c297fb0cedabdb">llvm::WebAssemblyFrameLowering::needsPrologForEH</a>, <a href="#ad7332117b148c3f93c1d7e58306ee748">needsUnwindTableEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adfeaf9db4445cbd2d43f260218036006">recoverFramePointer</a>, <a href="/web-llvm/docs/api/classes/anonymous-winehprepare-cpp-/winehprepareimpl/#a5026a3f719e275576358dce2b6c31ca5">anonymous{WinEHPrepare.cpp}::WinEHPrepareImpl::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/stackprotector/#ad6088af9690051701647680fd467ed97">llvm::StackProtector::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/runtimecallinserter/#a5290d0349e696ca38a092b3c61a0f1f8">anonymous{AddressSanitizer.cpp}::RuntimeCallInserter::RuntimeCallInserter</a>.</p>

</div>
</div>

### hasPrefixData() {#a68f94d59950d5fa55b818dca8ea59579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::hasPrefixData ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this function has prefix data.</p>

<p>Definition at line 914 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#a05810d77360abad7ef2848184726d872">llvm::Value::getSubclassDataFromValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>.</p>

</div>
</div>

### hasProfileData() {#a9084ce2576fad285c1c0dc1e165dd4b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::hasProfileData (bool IncludeSynthetic=false)</td>
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

<p>Return true if the function is annotated with profile data.</p>


<p>Presence of entry counts from a profile run implies the function has profile annotations. If IncludeSynthetic is false, only return true when the profile data is real.</p>


<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#ac154f7a85081237665c89b83bbd3d7e2">getEntryCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a3d135a8abf70dc93455708cc087cc0b0">getLayoutSuccessorProbThreshold</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#aa873cdb66e593236e466fd0d452a0a82">llvm::ProfileSummaryInfo::isColdCallSite</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinelicm-cpp-/machinelicmimpl/#a91e4daed2453931a75ea961f1dce12ad">anonymous{MachineLICM.cpp}::MachineLICMImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinefunctionsplitter-cpp-/machinefunctionsplitter/#a9f05c8e7366bb0f541cdc6c03b929ddd">anonymous{MachineFunctionSplitter.cpp}::MachineFunctionSplitter::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a925d8eaf1d93c7d13870ae5948c48140">sinkLoopInvariantInstructions</a>.</p>

</div>
</div>

### hasPrologueData() {#ae8c01344089090a372ee86f62c07f2bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::hasPrologueData ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this function has prologue data.</p>

<p>Definition at line 923 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#a05810d77360abad7ef2848184726d872">llvm::Value::getSubclassDataFromValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>.</p>

</div>
</div>

### hasRetAttribute() {#abdd453734de0c5ec547939f9bb475190}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::hasRetAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>check if an attribute is in the list of attributes for the return value.</p>

<p>Declaration at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 739 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### hasStackProtectorFnAttr() {#a29db1a6c4a106d1720101b8d1adf9387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::hasStackProtectorFnAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the function has ssp, sspstrong, or sspreq fn attrs.</p>

<p>Declaration at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 852 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>.</p>

</div>
</div>

### hasStructRetAttr() {#aa73c6ba4efcd37a9afc738793d50b2c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::hasStructRetAttr ()</td>
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

<p>Determine if the function returns a structure through first or second pointer argument.</p>

<p>Definition at line 688 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a405578f0decf5610edec9f350a54e81f">llvm::SparcTargetLowering::LowerFormalArguments_32</a> and <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a97357df4054a9551eb9a07b609cea109">llvm::SparcTargetLowering::LowerReturn_32</a>.</p>

</div>
</div>

### hasUWTable() {#acabf5ba443b4e5327f547ae8fc04a98c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::hasUWTable ()</td>
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

<p>True if the ABI mandates (or the user requested) that this function be in a unwind table.</p>

<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="#a7e181b32a135b15eb712e81ffe52ea50">getUWTableKind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6cdf47ba1fa5831d7c2897bc3aed77b8a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>


<p>Referenced by <a href="#ad7332117b148c3f93c1d7e58306ee748">needsUnwindTableEntry</a>.</p>

</div>
</div>

### insert() {#aaab8110aafc070c83bc701b13d2260df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function::iterator llvm::Function::insert (<a href="#a19595c245bd2e3eefa93ce22db5ad15f">Function::iterator</a> Position, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Insert <span class="doxyComputerOutput">BB</span> in the basic block list at <span class="doxyComputerOutput">Position</span>.</p>


<p>\Returns an iterator to the newly inserted BB.</p>


<p>Definition at line 754 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="#a5f470380211ecb6cee767f1ef0f16ed0">IsNewDbgInfoFormat</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4425b120dc5e5600864748818fb1d923">llvm::BasicBlock::setIsNewDbgInfoFormat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a> and <a href="/web-llvm/docs/api/groups/llvmccorevaluebasicblock/#ga685b3eca9432cb6b80cc96dd54d025a3">LLVMInsertExistingBasicBlockAfterInsertBlock</a>.</p>

</div>
</div>

### isConstrainedFPIntrinsic() {#a4d7c400bd90654692d8137528c0ef52f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::isConstrainedFPIntrinsic ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the function is one of the "Constrained Floating-Point
Intrinsics".</p>


<p>Returns false if not, and returns false when <a href="#a4d0a7baab8d078065b2de10e3460892a">getIntrinsicID()</a> returns <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a35fedf4db6d756bd82501607f93c1e79aab5fb650050f184fa7c19c26abde5226">Intrinsic::not_intrinsic</a>.</p>


<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### isConvergent() {#a049de2366079104e70f0c3451b09aebf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::isConvergent ()</td>
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

<p>Determine if the call is convergent.</p>

<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#afb28a4deafe2954b0534cc6399ce518b">hasFnAttribute</a>.</p>

</div>
</div>

### isCoroOnlyDestroyWhenComplete() {#ac02f761bf4c83638d32b8459c82116bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::isCoroOnlyDestroyWhenComplete ()</td>
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



<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#afb28a4deafe2954b0534cc6399ce518b">hasFnAttribute</a>.</p>

</div>
</div>

### isDefTriviallyDead() {#a135e2cf7628956c6c2a4365fb10305cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::isDefTriviallyDead ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isDefTriviallyDead - Return true if it is trivially safe to remove this function definition from the module (because it isn't externally visible, does not have its address taken, and has no callers).</p>


<p>To make this more accurate, call removeDeadConstantUsers first.</p>


<p>Declaration at line 1007 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1023 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### isIntrinsic() {#a900a32da3983469187b1848189681705}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::isIntrinsic ()</td>
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

<p>isIntrinsic - Returns true if the function's name starts with "llvm.".</p>


<p>It's possible for this function to return true while <a href="#a4d0a7baab8d078065b2de10e3460892a">getIntrinsicID()</a> returns <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a35fedf4db6d756bd82501607f93c1e79aab5fb650050f184fa7c19c26abde5226">Intrinsic::not_intrinsic</a>!</p>


<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a53750bb517b7bfc28013f16cdbe2de4d">llvm::GlobalValue::HasLLVMReservedName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9bf41f2408094f54097744991c82336a">llvm::calculateCXXStateForAsynchEH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b49442c1c01ddc388c51d7599c0f876">llvm::calculateSEHStateForAsynchEH</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcallsite/#ad13669e41527f0cb36a0f5c93cff4a21">llvm::InstrProfCallsite::canInstrumentCallsite</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a7b91ad1b09dab040d3519c054e473efb">llvm::TargetLibraryInfoImpl::getLibFunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp/#a71bb9fbc36358e29483641f8cab80003">isIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a7f0607e63d19dd3d4fb6edcef16bc26e">optimizeDoubleFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#aff18d7e34536cf38b7a43d7c42fa743c">restoreMutatedType</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/amdgpulowerbufferfatpointers/#a00d87849a4eb6524d910ab07f0fd968f">anonymous{AMDGPULowerBufferFatPointers.cpp}::AMDGPULowerBufferFatPointers::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptximageoptimizer-cpp-/nvptximageoptimizer/#a70631a00c85109b54d2e816daae4f03a">anonymous{NVPTXImageOptimizer.cpp}::NVPTXImageOptimizer::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a4abe522bf135a7628b059cf5fc0be127">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::VisitCallInst</a>.</p>

</div>
</div>

### isMaterializable() {#a2d8ab5e89ddab6695d95b3857f9b8c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::isMaterializable ()</td>
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



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/globalobject/#ad9662340b952dc803605bf33a28cada6">llvm::GlobalObject::getGlobalObjectSubClassData</a>.</p>

</div>
</div>

### isPresplitCoroutine() {#a9f6ec3f2263a0ed9418c0968cf7c265e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::isPresplitCoroutine ()</td>
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

<p>Determine if the function is presplit coroutine.</p>

<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#afb28a4deafe2954b0534cc6399ce518b">hasFnAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/callvalue/#abf2170fc4c00058df8ef27562be3fb39">anonymous{EarlyCSE.cpp}::CallValue::canHandle</a>.</p>

</div>
</div>

### isSpeculatable() {#a5cbc3ad9ede9ff8b2012e46bfb997e76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::isSpeculatable ()</td>
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

<p>Determine if the call has sideeffects.</p>

<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#afb28a4deafe2954b0534cc6399ce518b">hasFnAttribute</a>.</p>

</div>
</div>

### isTargetIntrinsic() {#a6367bc9050fb76e2d686108abcf5a212}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::isTargetIntrinsic ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isTargetIntrinsic - Returns true if this function is an intrinsic and the intrinsic is specific to a certain target.</p>


<p>If this is not an intrinsic or a generic intrinsic, false is returned.</p>


<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 935 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### isVarArg() {#af457a58a84b500d44feb7b699aa43ec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::isVarArg ()</td>
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

<p>isVarArg - Return true if this function takes a variable number of arguments.</p>

<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a21075305f0e463b24aafc2fb99514ace">getFunctionType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#ac8faf9a625064bfefafb7ace646815ff">llvm::X86FrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a4554341b316dd0b06a915ec883f4f74a">llvm::SystemZELFFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/xcorefunctioninfo/#a75dfee78519833f2ad7e210c5e471f5d">llvm::XCoreFunctionInfo::createLRSpillSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a9eb6f3247260b906218068229b8d5b67">llvm::SystemZELFFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#aaabcdae312538836cccf2ed4e8069999">llvm::XCoreFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aac8f5d5c66c21056b3144508e8142639">llvm::ARCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aa1bd5939c1fd11c05038c583ada0110d">llvm::ARCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a58cebd1e96489b04d18f2a7c39c250f8">llvm::SystemZXPLINKFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#afffd4df1bba5cd5416f615e919a8fa66">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandVAIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ad7d8710804e26a041e428fb0bae67559">llvm::SystemZELFFrameLowering::getRegSpillOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ae01246dc7ecdd8a082730860cd3166a1">llvm::AArch64RegisterInfo::isArgumentRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a273e9b97fc0dfec8df7cf4294d9b87fe">llvm::Attributor::isValidFunctionSignatureRewrite</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ac8934ae6c8b97148ebb1db39bd978b03">llvm::AArch64FrameLowering::resolveFrameOffsetReference</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ac0e549bf3d7f691714f73696c1df480c">llvm::SystemZELFFrameLowering::spillCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a263f69437421410a39c26e0be576f028">llvm::PPCTargetLowering::supportsTailCallFor</a>.</p>

</div>
</div>

### mustProgress() {#a41ebfca5fde82030f9d559dc34082ef6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::mustProgress ()</td>
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

<p>Determine if the function is required to make forward progress.</p>

<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#afb28a4deafe2954b0534cc6399ce518b">hasFnAttribute</a>.</p>

</div>
</div>

### needsUnwindTableEntry() {#ad7332117b148c3f93c1d7e58306ee748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::needsUnwindTableEntry ()</td>
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

<p>True if this function needs an unwind table.</p>

<p>Definition at line 682 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="#a81f38aca859ffeda166f8c385f7d55a5">doesNotThrow</a>, <a href="#a6a0f6312963ee6fb0969243607174949">hasPersonalityFn</a> and <a href="#acabf5ba443b4e5327f547ae8fc04a98c">hasUWTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a33a9bde0ee9fe5d047f5c84642436bb8">needsWinCFI</a> and <a href="/web-llvm/docs/api/classes/anonymous-thumb2sizereduction-cpp-/thumb2sizereduce/#a0c70c731d0c61ed9a18b61ea303aa44c">anonymous{Thumb2SizeReduction.cpp}::Thumb2SizeReduce::runOnMachineFunction</a>.</p>

</div>
</div>

### nullPointerIsDefined() {#a212723e3aa6b6ca349b27344bc417505}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::nullPointerIsDefined ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if null pointer dereferencing is considered undefined behavior for the function.</p>


<p>Return value: false =&gt; null pointer dereference is undefined. Return value: true =&gt; null pointer dereference is not undefined.</p>


<p>Declaration at line 1031 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1183 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### onlyAccessesArgMemory() {#ad9f7a2cf04e469adef7fe1aa1cf15d9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::onlyAccessesArgMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the call can access memmory only using pointers based on its arguments.</p>

<p>Declaration at line 570 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 909 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### onlyAccessesInaccessibleMemOrArgMem() {#a13d92306a2df12850752a8415741b5c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::onlyAccessesInaccessibleMemOrArgMem ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the function may only access memory that is either inaccessible from the IR or pointed to by its arguments.</p>

<p>Declaration at line 580 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 927 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### onlyAccessesInaccessibleMemory() {#ac3a2060955a1335598943ea1dcc71ac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::onlyAccessesInaccessibleMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the function may only access memory that is inaccessible from the IR.</p>

<p>Declaration at line 575 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 918 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### onlyReadsMemory() {#af7736e14235372b75b72e119f852c280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::onlyReadsMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the function does not access or only reads memory.</p>

<p>Declaration at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 892 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#aaf2ec1eb99cc826eea1a7dd8a8ea570a">doesNotFreeMemory</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ae2ebbbbc990e3d932da5d0d0ea255f42">HandleByValArgument</a>.</p>

</div>
</div>

### onlyWritesMemory() {#abe064a7e0978b5f7705119abf53c0ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::onlyWritesMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the function does not access or only writes memory.</p>

<p>Declaration at line 565 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 900 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### print() {#a5b8c4fb5c4e648b5e893b3db122bdf6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/assemblyannotationwriter">AssemblyAnnotationWriter</a> * AAW=nullptr, bool ShouldPreserveUseListOrder=false, bool IsForDebug=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the function to an output stream with an optional <a href="/web-llvm/docs/api/classes/llvm/assemblyannotationwriter">AssemblyAnnotationWriter</a>.</p>

<p>Declaration at line 933 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 4890 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/#a1fa6fb3707c37fd9468795bc04580f5d">anonymous{PartialInlining.cpp}::PartialInlinerImpl::unswitchFunction</a>.</p>

</div>
</div>

### removeAttributeAtIndex() {#a838fded9375bdf5078b6853449ee44f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::removeAttributeAtIndex (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removes the attribute from the list of attributes.</p>

<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### removeAttributeAtIndex() {#aced83766bacb03989c05422bfc341449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::removeAttributeAtIndex (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removes the attribute from the list of attributes.</p>

<p>Declaration at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### removeFnAttr() {#a8baad1df39d45576fe7a642b49f0e6dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::removeFnAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove function attributes from this function.</p>

<p>Declaration at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a6b42b6fca05063155c689008d30a2751">llvm::AMDGPU::removeFnAttrFromReachable</a>, <a href="/web-llvm/docs/api/structs/enumattr/#aad70a721379eef0de5fe32fb197d20de">EnumAttr::set</a>, <a href="#aaac428519a2771aeec63054d47800849">setNotConvergent</a>, <a href="#ac2c99fa1630820513c88980dd6b5661a">setSplittedCoroutine</a> and <a href="#a7a383eea189e7af487299e904c0b5fcc">setUWTableKind</a>.</p>

</div>
</div>

### removeFnAttr() {#af6b3606d6657d553ba9065fad0e333f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::removeFnAttr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove function attribute from this function.</p>

<p>Declaration at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 693 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### removeFnAttrs() {#a6875de46fcb2a74ca95bce67edd215a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::removeFnAttrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp; Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 697 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>.</p>

</div>
</div>

### removeFromParent() {#a29e0a562beb4b5d20eb0c426b363ceed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::removeFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removeFromParent - This method unlinks 'this' from the containing module, but does not delete it.</p>

<p>Declaration at line 739 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a784adc2347b72f745ff1239aef3a3c26">llvm::OpenMPIRBuilder::finalize</a>.</p>

</div>
</div>

### removeParamAttr() {#a1bb42b4d714a18ee81315cfb6ae1ed13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::removeParamAttr (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removes the attribute from the list of attributes.</p>

<p>Declaration at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 713 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### removeParamAttr() {#a948ae5afe80982c85442c19b2855cb35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::removeParamAttr (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removes the attribute from the list of attributes.</p>

<p>Declaration at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 717 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### removeParamAttrs() {#a55c554858450f67ef20c4abbc7e1ed19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::removeParamAttrs (unsigned ArgNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp; Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removes the attribute from the list of attributes.</p>

<p>Declaration at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 721 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### removeRetAttr() {#a09ac042b7e543197d4911a0436d46349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::removeRetAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removes the attribute from the return value list of attributes.</p>

<p>Declaration at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 701 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### removeRetAttr() {#a5574f481ddb505fe7c2b90c46e22db33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::removeRetAttr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removes the attribute from the return value list of attributes.</p>

<p>Declaration at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 705 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### removeRetAttrs() {#acb3914db988819782f3a6317d2e2b925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::removeRetAttrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp; Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removes the attributes from the return value list of attributes.</p>

<p>Declaration at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>.</p>

</div>
</div>

### renumberBlocks() {#a379698f9e29cc98012a7bbc55984ffda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::renumberBlocks ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Renumber basic blocks into a dense value range starting from 0.</p>


<p>Be aware that other data structures and analyses (e.g., <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a>) may depend on the value numbers and need to be updated or invalidated.</p>


<p>Declaration at line 833 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### returnDoesNotAlias() {#a427fcc6fd56f42086a2c91c0dce5e425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::returnDoesNotAlias ()</td>
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

<p>Determine if the parameter or return value is marked with NoAlias attribute.</p>

<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### setAttributes() {#a9e4c6c67f4b2528b5648299db4a86926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setAttributes (AttributeList Attrs)</td>
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

<p>Set the attribute list for this <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>.</p>

<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af0793991541abccfec5c0d8831612b7b">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::createNoAllocVariant</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac800803b298b2e26368a3cc770279945">anonymous{ExpandVariadics.cpp}::ExpandVariadics::deriveFixedArityReplacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#aaa1cdfbf8bbbb3d37466c44f0b8a403b">anonymous{ExpandVariadics.cpp}::ExpandVariadics::replaceAllUsesWithNewDeclaration</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a167c9f2ddb243187bdd2313de8586458">llvm::IRPosition::setAttrList</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a64cd5b79789610d81be5d0b2633868ae">anonymous{ThinLTOBitcodeWriter.cpp}::simplifyExternals</a>.</p>

</div>
</div>

### setCallingConv() {#ae6db8746934e6feae3649a8709fce3cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setCallingConv (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC)</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a05810d77360abad7ef2848184726d872">llvm::Value::getSubclassDataFromValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca2f101663d054cffa9c9956f30e7ecf7d">llvm::CallingConv::MaxID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuctordtorlowering-cpp-/#aa82200436735a7e7831e52db45ae4580">anonymous{AMDGPUCtorDtorLowering.cpp}::createInitOrFiniKernelFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a61f3d93434dc9f576826799df553ed1b">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::doMultiRegionFunctionOutlining</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#afb5c7d9f47f77651e28e14b6e715badf">getOrCreateFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a3ce5fd3a8d74ecd38fdb5e27f85d2d61">llvm::Intrinsic::remangleIntrinsicFunction</a>.</p>

</div>
</div>

### setCannotDuplicate() {#a9dca1751288896161d502571fecf2ae3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setCannotDuplicate ()</td>
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



<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a01875e4204852069dd4b7938cab4140b">addFnAttr</a>.</p>

</div>
</div>

### setConvergent() {#a95f8eff531b9ed5d85cdc2f8d7c3e5c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setConvergent ()</td>
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



<p>Definition at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a01875e4204852069dd4b7938cab4140b">addFnAttr</a>.</p>

</div>
</div>

### setCoroDestroyOnlyWhenComplete() {#a059fada19030e5930c4b511d4fe6a766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setCoroDestroyOnlyWhenComplete ()</td>
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



<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a01875e4204852069dd4b7938cab4140b">addFnAttr</a>.</p>

</div>
</div>

### setDoesNotAccessMemory() {#a3b53b6573f46ab43c654ef9a295a652c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setDoesNotAccessMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 558 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 887 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### setDoesNotFreeMemory() {#afb7e3c73013c2827ccd486e888953875}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setDoesNotFreeMemory ()</td>
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



<p>Definition at line 633 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a01875e4204852069dd4b7938cab4140b">addFnAttr</a>.</p>

</div>
</div>

### setDoesNotRecurse() {#aecb901181edae6cd518104e05ccb6f78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setDoesNotRecurse ()</td>
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



<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a01875e4204852069dd4b7938cab4140b">addFnAttr</a>.</p>

</div>
</div>

### setDoesNotReturn() {#a57d6d47f3d0fe19f5a9bc1626630d4b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setDoesNotReturn ()</td>
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



<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a01875e4204852069dd4b7938cab4140b">addFnAttr</a>.</p>

</div>
</div>

### setDoesNotThrow() {#afd978c6f74e279603d47b940f60f1f24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setDoesNotThrow ()</td>
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



<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a01875e4204852069dd4b7938cab4140b">addFnAttr</a>.</p>

</div>
</div>

### setEntryCount() {#aefb3254278b224f10e5b966cea653e01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setEntryCount (<a href="/web-llvm/docs/api/classes/llvm/function/profilecount">ProfileCount</a> Count, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; * Imports=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the entry count for this function.</p>


<p>Entry count is the number of times this function was executed based on pgo data. <span class="doxyComputerOutput">Imports</span> points to a set of GUIDs that needs to be imported by the function for sample PGO, to enable the same inlines as the profiled optimized binary.</p>


<p>Declaration at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1111 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#abdc4c98f065999f51c3871a59e5c1de2">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::finalizeWeightPropagation</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#ab399a6466f9c56febc239c000eee5406">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::initWeightPropagation</a>.</p>

</div>
</div>

### setEntryCount() {#a758c8ee1f227a4958e0e6820ccff5ff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setEntryCount (uint64_t Count, <a href="#a438d2f246b76817114ade2a005a6bcab">ProfileCountType</a> Type=<a href="#a438d2f246b76817114ade2a005a6bcabac7dbc704eba08842e6acdde9cf6379ba">PCT_Real</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; * Imports=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A convenience wrapper for setting entry count.</p>

<p>Declaration at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1128 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### setGC() {#a455032eb7bfb230b908159d9b1c1fbf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setGC (std::string Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 840 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### setIsMaterializable() {#a59f288adc3400b81160f04f674b7f6bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setIsMaterializable (bool V)</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalobject/#ad9662340b952dc803605bf33a28cada6">llvm::GlobalObject::getGlobalObjectSubClassData</a> and <a href="/web-llvm/docs/api/classes/llvm/globalobject/#ad10eefb0fa57d440583a1dc2abbd4e1e">llvm::GlobalObject::setGlobalObjectSubClassData</a>.</p>

</div>
</div>

### setIsNewDbgInfoFormat() {#acd4e7f960071723676ea5cc199a49df6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setIsNewDbgInfoFormat (bool NewVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aedeb89fa4ceb608d9d49bcd53ddcd2c1">llvm::CloneFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac1b2be839460bb277d4f07f4aa5225ac">llvm::CloneFunctionInto</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>.</p>

</div>
</div>

### setMemoryEffects() {#ae1867b9b6cef5ee12741f0b379ec8800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setMemoryEffects (<a href="/web-llvm/docs/api/namespaces/llvm/#a44ad2b29af9ebe3d12a99843a7594757">MemoryEffects</a> ME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 879 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### setMustProgress() {#af7915406c3f283ae294f55c2c9dc49c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setMustProgress ()</td>
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



<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a01875e4204852069dd4b7938cab4140b">addFnAttr</a>.</p>

</div>
</div>

### setNewDbgInfoFormatFlag() {#a9f1ae275a74d61d2b50c7be97490ec4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setNewDbgInfoFormatFlag (bool NewVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### setNoSync() {#ac972de5ac0d70f5bd4ff3cf958911e94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setNoSync ()</td>
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



<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a01875e4204852069dd4b7938cab4140b">addFnAttr</a>.</p>

</div>
</div>

### setNotConvergent() {#aaac428519a2771aeec63054d47800849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setNotConvergent ()</td>
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



<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a8baad1df39d45576fe7a642b49f0e6dc">removeFnAttr</a>.</p>

</div>
</div>

### setOnlyAccessesArgMemory() {#a4d7f7a04bd6707f8b9c9c8a1f98d757f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setOnlyAccessesArgMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 571 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 912 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### setOnlyAccessesInaccessibleMemOrArgMem() {#ae8042a91752d4b2ca165cc35250d0f8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setOnlyAccessesInaccessibleMemOrArgMem ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 930 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### setOnlyAccessesInaccessibleMemory() {#a54b35f9b5f699da7de2cf9feaae4ddfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setOnlyAccessesInaccessibleMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 576 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 921 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### setOnlyReadsMemory() {#a63062a49613cb771453e2dc857343a39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setOnlyReadsMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 895 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### setOnlyWritesMemory() {#a6f930a611c74d4a00af794a57bae9d84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setOnlyWritesMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 566 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 903 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### setPersonalityFn() {#a6f9ba62511c44dd991c6cd7485098d15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setPersonalityFn (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 911 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1053 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>.</p>

</div>
</div>

### setPrefixData() {#a2960cc22992967e68a160de69e1ad86e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setPrefixData (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * PrefixData)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 920 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1063 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>.</p>

</div>
</div>

### setPresplitCoroutine() {#a95f94f1901598a30b2644932e09320ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setPresplitCoroutine ()</td>
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



<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a01875e4204852069dd4b7938cab4140b">addFnAttr</a>.</p>

</div>
</div>

### setPrologueData() {#ac80cb4c1c131aabafef0fdd92af7cac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setPrologueData (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * PrologueData)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 929 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1073 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>.</p>

</div>
</div>

### setReturnDoesNotAlias() {#a698b49a3ec754ef00d2c27d146daa5e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setReturnDoesNotAlias ()</td>
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



<p>Definition at line 698 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a6afca945952abdd7be262d5fe5ddad77">addRetAttr</a>.</p>

</div>
</div>

### setSectionPrefix() {#a60c157d9fa21a214f5ce40cab0514b85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setSectionPrefix (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the section prefix for this function.</p>

<p>Declaration at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1167 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### setSpeculatable() {#a99a24ef326b23786e0e0b7f7c02d45a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setSpeculatable ()</td>
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



<p>Definition at line 625 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a01875e4204852069dd4b7938cab4140b">addFnAttr</a>.</p>

</div>
</div>

### setSplittedCoroutine() {#ac2c99fa1630820513c88980dd6b5661a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setSplittedCoroutine ()</td>
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



<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a8baad1df39d45576fe7a642b49f0e6dc">removeFnAttr</a>.</p>

</div>
</div>

### setSubprogram() {#a05a19abc8ee11d5909275d980efa1670}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setSubprogram (<a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the attached subprogram.</p>


<p>Calls <em><a href="/web-llvm/docs/api/classes/llvm/globalobject/#a338590123630c357df6340c38d066572">setMetadata()</a></em> with <em>LLVMContext::MD_dbg</em>.</p>


<p>Declaration at line 1016 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1870 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a338590123630c357df6340c38d066572">llvm::GlobalObject::setMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroearly-cpp/#afbc0cbc36e72c326f3df01f017015786">buildDebugInfoForNoopResumeDestroyFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>.</p>

</div>
</div>

### setUWTableKind() {#a7a383eea189e7af487299e904c0b5fcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setUWTableKind (<a href="/web-llvm/docs/api/namespaces/llvm/#a6cdf47ba1fa5831d7c2897bc3aed77b8">UWTableKind</a> K)</td>
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



<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="#a01875e4204852069dd4b7938cab4140b">addFnAttr</a>, <a href="#a9fffac2512fe651f0d5e37e27f5bd51c">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a600a01b826220fa1896bcecb198184e1">llvm::Attribute::getWithUWTableKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6cdf47ba1fa5831d7c2897bc3aed77b8a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="#a8baad1df39d45576fe7a642b49f0e6dc">removeFnAttr</a>.</p>

</div>
</div>

### setWillReturn() {#a460362250160f652f82d5de1fc5379d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setWillReturn ()</td>
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



<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a01875e4204852069dd4b7938cab4140b">addFnAttr</a>.</p>

</div>
</div>

### shouldEmitDebugInfoForProfiling() {#a7345f1a973f5084e01c183cad89399d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Function::shouldEmitDebugInfoForProfiling ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if we should emit debug info for profiling.</p>

<p>Declaration at line 1025 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1878 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>Reference <a href="#a4d834f9897d15e3a6349063b5d637cd8">getSubprogram</a>.</p>

</div>
</div>

### size() {#a969eb757b1e43b455d4a8d0f603e695b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::Function::size ()</td>
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



<p>Definition at line 858 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#aaf2fe2b910650ab4ea0eeaca5922dce8">addVariantDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#ae86fef7fc5831c2514bff95bdf784d09">createSwitchStatement</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp/#a41f57bfb86c16aafc498999912a00614">findMainViewFileID</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp/#a33ee200fee7c9d35203bd921c606fc26">gatherFileIDs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#ac2547f0adabfca4600d7c16947b20ed4">InsertTrap</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-55c8cb82503f51812ad190e425a6fd3d/#a786bf81e71569fbb4a959698bc1fd2b2">llvm::GraphTraits&lt; DOTFuncInfo * &gt;::size</a> and <a href="/web-llvm/docs/api/structs/llvm/graphtraits-02f9563a016dafe7fbc78fcb1f76f101/#a8e36b2fa578fdab4bef52c01f3e171c5">llvm::GraphTraits&lt; DOTFuncMSSAInfo * &gt;::size</a>.</p>

</div>
</div>

### splice() {#a14b02db913559954c4d38ed70cd66f59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::splice (<a href="#a19595c245bd2e3eefa93ce22db5ad15f">Function::iterator</a> ToIt, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * FromF)</td>
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

<p>Transfer all blocks from <span class="doxyComputerOutput">FromF</span> to this function at <span class="doxyComputerOutput">ToIt</span>.</p>

<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="#a88a5e60837674780a9d812d661897ac5">begin</a>, <a href="#ae4ca2261b8b901e415fda7feac5051ea">end</a> and <a href="#a14b02db913559954c4d38ed70cd66f59">splice</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac800803b298b2e26368a3cc770279945">anonymous{ExpandVariadics.cpp}::ExpandVariadics::deriveFixedArityReplacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>, <a href="#a14b02db913559954c4d38ed70cd66f59">splice</a> and <a href="#a1d3f9f2b13a4a6fad661ec70bd8828ab">splice</a>.</p>

</div>
</div>

### splice() {#a1d3f9f2b13a4a6fad661ec70bd8828ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::splice (<a href="#a19595c245bd2e3eefa93ce22db5ad15f">Function::iterator</a> ToIt, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * FromF, <a href="#a19595c245bd2e3eefa93ce22db5ad15f">Function::iterator</a> FromIt)</td>
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

<p>Transfer one <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> from <span class="doxyComputerOutput">FromF</span> at <span class="doxyComputerOutput">FromIt</span> to this function at <span class="doxyComputerOutput">ToIt</span>.</p>

<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#a14b02db913559954c4d38ed70cd66f59">splice</a>.</p>

</div>
</div>

### splice() {#a193eeb8fc9ba64befe766a35f7a5689f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::splice (<a href="#a19595c245bd2e3eefa93ce22db5ad15f">Function::iterator</a> ToIt, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * FromF, <a href="#a19595c245bd2e3eefa93ce22db5ad15f">Function::iterator</a> FromBeginIt, <a href="#a19595c245bd2e3eefa93ce22db5ad15f">Function::iterator</a> FromEndIt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transfer a range of basic blocks that belong to <span class="doxyComputerOutput">FromF</span> from <span class="doxyComputerOutput">FromBeginIt</span> to <span class="doxyComputerOutput">FromEndIt</span>, to this function at <span class="doxyComputerOutput">ToIt</span>.</p>

<p>Declaration at line 778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### stealArgumentListFrom() {#a9bd0472865626998cee18ae8c6cf5120}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::stealArgumentListFrom (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Steal arguments from another function.</p>


<p>Drop this function's arguments and splice in the ones from <span class="doxyComputerOutput">Src</span>. Requires that this has no function body.</p>


<p>Declaration at line 750 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>.</p>

</div>
</div>

### updateAfterNameChange() {#ab38fb46aad998f695de33966a62b4f66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::updateAfterNameChange ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update internal caches that depend on the function name (such as the intrinsic <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> and libcall cache).</p>


<p>Note, this method does not need to be called directly, as it is called from <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">Value::setName()</a> whenever the name of this function changes.</p>


<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 939 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>.</p>

</div>
</div>

### viewCFG() {#aa16dbafaedca375940c39e1c7ecff2ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::viewCFG ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>viewCFG - This function is meant for use from the debugger.</p>


<p>You can just say 'call F-&gt;<a href="#aa16dbafaedca375940c39e1c7ecff2ae">viewCFG()</a>' and a ghostview window should pop up from the program, displaying the CFG of the current function with the code for each basic block inside. This depends on there being a 'dot' and 'gv' program in your path.</p>


<p>You can just say 'call F-&gt;<a href="#aa16dbafaedca375940c39e1c7ecff2ae">viewCFG()</a>' and a ghostview window should pop up from the program, displaying the CFG of the current function. This depends on there being a 'dot' and 'gv' program in your path.</p>


<p>Declaration at line 943 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfgprinter-cpp">CFGPrinter.cpp</a>.</p>


<p>Reference <a href="#aa16dbafaedca375940c39e1c7ecff2ae">viewCFG</a>.</p>


<p>Referenced by <a href="#aa16dbafaedca375940c39e1c7ecff2ae">viewCFG</a>, <a href="#a60db5d1a9b92efaf4f0904959e3b3648">viewCFG</a>, <a href="#ac604e42ef1bf36f1739f06cc7677398b">viewCFGOnly</a> and <a href="#a8220277a7e54b877e77cfb16e1958df9">viewCFGOnly</a>.</p>

</div>
</div>

### viewCFG() {#a60db5d1a9b92efaf4f0904959e3b3648}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::viewCFG (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * OutputFileName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>viewCFG - This function is meant for use from the debugger.</p>


<p>It works just like <a href="#aa16dbafaedca375940c39e1c7ecff2ae">viewCFG()</a>, but generates the dot file with the given file name.</p>


<p>Declaration at line 947 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfgprinter-cpp">CFGPrinter.cpp</a>.</p>


<p>Reference <a href="#aa16dbafaedca375940c39e1c7ecff2ae">viewCFG</a>.</p>

</div>
</div>

### viewCFG() {#aeac4ca2dcb29682747f7d637b47c8327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::viewCFG (bool ViewCFGOnly, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> * BPI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * OutputFileName=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extended form to print edge weights.</p>

<p>Declaration at line 950 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfgprinter-cpp">CFGPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfgprinter-cpp/#af39e0fda9ba4a4f0c817817e2c540b66">CFGFuncName</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af566713617705f23279ab7a214fee469">llvm::getMaxFreq</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab8635363d4287c93f64c55ad5567fcf0">llvm::ViewGraph</a>.</p>

</div>
</div>

### viewCFGOnly() {#ac597af7c6f9404366ebac258d2c90223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::viewCFGOnly ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>viewCFGOnly - This function is meant for use from the debugger.</p>


<p>It works just like viewCFG, but it does not include the contents of basic blocks into the nodes, just the label. If you are only interested in the CFG this can make the graph smaller.</p>


<p>Declaration at line 959 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfgprinter-cpp">CFGPrinter.cpp</a>.</p>


<p>Reference <a href="#ac597af7c6f9404366ebac258d2c90223">viewCFGOnly</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-linkallpasses-h-/forcepasslinking/#aca44adfcab3498802a1f54c6c5e42086">anonymous{LinkAllPasses.h}::ForcePassLinking::ForcePassLinking</a> and <a href="#ac597af7c6f9404366ebac258d2c90223">viewCFGOnly</a>.</p>

</div>
</div>

### viewCFGOnly() {#a8220277a7e54b877e77cfb16e1958df9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::viewCFGOnly (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * OutputFileName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>viewCFG - This function is meant for use from the debugger.</p>


<p>It works just like <a href="#ac597af7c6f9404366ebac258d2c90223">viewCFGOnly()</a>, but generates the dot file with the given file name.</p>


<p>Declaration at line 963 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfgprinter-cpp">CFGPrinter.cpp</a>.</p>


<p>Reference <a href="#aa16dbafaedca375940c39e1c7ecff2ae">viewCFG</a>.</p>

</div>
</div>

### viewCFGOnly() {#ac604e42ef1bf36f1739f06cc7677398b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::viewCFGOnly (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> * BPI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extended form to print edge weights.</p>

<p>Declaration at line 966 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfgprinter-cpp">CFGPrinter.cpp</a>.</p>


<p>Reference <a href="#aa16dbafaedca375940c39e1c7ecff2ae">viewCFG</a>.</p>

</div>
</div>

### willReturn() {#a48e10a01350fafd3df5828061787a97e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::willReturn ()</td>
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

<p>Determine if the function will return.</p>

<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="#afb28a4deafe2954b0534cc6399ce518b">hasFnAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a2408a88276528d80adefefa00995705a">llvm::VPRecipeBase::mayHaveSideEffects</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### allocHungoffUselist() {#ac5029ffc19e34140155b1560345cbe04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::allocHungoffUselist ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1034 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1078 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### BuildLazyArguments() {#aad29973081e44927d9f608d75b68798b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::BuildLazyArguments ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### CheckLazyArguments() {#a9f7bed83bd85a8047e38a36b0a6e86c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::CheckLazyArguments ()</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### clearArguments() {#af9428610ca28f18617fcef7e711f2c7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::clearArguments ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### deleteBodyImpl() {#ace5127a647cfc299454c65c46b5a881e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::deleteBodyImpl (bool ShouldDrop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 607 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### getBasicBlockList() {#abb74b1a24961c058ef44eb0eac7a5ce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlockListType &amp; llvm::Function::getBasicBlockList ()</td>
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

<p>Get the underlying elements of the <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>... the basic block list is empty for external functions.</p>


<p>This is deliberately private because we have implemented an adequate set of functions to modify the list, including <a href="#a14b02db913559954c4d38ed70cd66f59">Function::splice()</a>, <a href="#add1b62fd0110c8c97673ed9a66603f05">Function::erase()</a>, <a href="#aaab8110aafc070c83bc701b13d2260df">Function::insert()</a> etc.</p>


<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### getBasicBlockList() {#ac94db32d5c61fac27d3f93a7f6b5a892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlockListType &amp; llvm::Function::getBasicBlockList ()</td>
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



<p>Definition at line 802 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### setHungoffOperand() {#a4b475ed3b75ab7892452e4841ad4e5c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Idx&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setHungoffOperand (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1035 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1094 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### setValueSubclassData() {#a5cc480510ff498f9f28dcc55ed8631af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Function::setValueSubclassData (unsigned short D)</td>
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

<p>Shadow <a href="/web-llvm/docs/api/classes/llvm/value/#aae37705b598ef612f698198dc33d6f65">Value::setValueSubclassData</a> with a private forwarding method so that subclasses cannot accidentally use it.</p>

<p>Definition at line 1039 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### setValueSubclassDataBit() {#abe766658327dceb3eccd7c579470d245}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::setValueSubclassDataBit (unsigned Bit, bool On)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1042 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 1103 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### validateBlockNumbers() {#a1b3c4bd354de30f5d44b3c23302312ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Function::validateBlockNumbers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assert that all blocks have unique numbers within 0..NextBlockNum.</p>


<p>This has O(n) runtime complexity.</p>


<p>Declaration at line 847 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IsNewDbgInfoFormat {#a5f470380211ecb6cee767f1ef0f16ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::IsNewDbgInfoFormat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is this function using intrinsics to record the position of debugging information, or non-intrinsic records?</p>


<p>See IsNewDbgInfoFormat in <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>.</p>


<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac1b2be839460bb277d4f07f4aa5225ac">llvm::CloneFunctionInto</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac800803b298b2e26368a3cc770279945">anonymous{ExpandVariadics.cpp}::ExpandVariadics::deriveFixedArityReplacement</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#ac0645a37d60eb4946b1b73c517a96544">llvm::CodeExtractor::extractCodeRegion</a>, <a href="#aaab8110aafc070c83bc701b13d2260df">insert</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#af85fe4610a8ddd0d57149e73008f32fb">llvm::Attributor::internalizeFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a> and <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#aaa1cdfbf8bbbb3d37466c44f0b8a403b">anonymous{ExpandVariadics.cpp}::ExpandVariadics::replaceAllUsesWithNewDeclaration</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Arguments {#a20e97a91346642ac4f0f0e9a1c655545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Argument* llvm::Function::Arguments = nullptr</td>
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

<p>The formal arguments.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### AttributeSets {#a07f61561ee790f64561b2f9b5dd02aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::Function::AttributeSets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parameter attributes.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### BasicBlocks {#af8712cd664d67cbfe7a462e4c4d4d2b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlockListType llvm::Function::BasicBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The basic blocks.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### BlockNumEpoch {#ae1ba400a02e7f6a2b61b239bad8e54f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Function::BlockNumEpoch = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Epoch of block numbers. (Could be shrinked to uint8_t if required.)</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### LibFuncCache {#a2435e8480cd99f4cee7818121a8dee68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LibFunc llvm::Function::LibFuncCache = UnknownLibFunc</td>
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

<p>Cache for TLI::getLibFunc() result without prototype validation.</p>


<p>UnknownLibFunc if uninitialized. NotLibFunc if definitely not lib func. Otherwise may be libfunc if prototype validation passes.</p>


<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### NextBlockNum {#a54d020431389f17e0e65211e54d09a95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Function::NextBlockNum = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### NumArgs {#ab1cea14ccbb330a3d362f4940b91f193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::Function::NumArgs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### SymTab {#afa056af4a606ca8d9d6da75fc448570a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ValueSymbolTable&gt; llvm::Function::SymTab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Symbol table of args/instructions.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a3b6f4f4582247421b5810172acd85432}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Function::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Methods for support type inquiry through isa, cast, and dyn_cast:</p>

<p>Definition at line 970 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### Create() {#a05d7aedbbdc0fd24e8bc27edfe9c603f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::Function::Create (<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage, unsigned AddrSpace, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; N="", <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M=nullptr)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ad61abcbd08169ff119e819ef0482744d">llvm::GlobalValue::Linkage</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-lljit-cpp-/#a02c5eacc8cf66436f8d0f722263b9494">anonymous{LLJIT.cpp}::addHelperAndWrapper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#aaf2fe2b910650ab4ea0eeaca5922dce8">addVariantDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#afca73617f8390579ca48fa10bf1c8edb">assureFPCallStub</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a101a4250b1fd5a230a766de2a14cb271">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildEntryThunk</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#ac134215053dd186eca7bdd553eabc68c">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildExitThunk</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7990af2ca325a18286d49b694c835c98">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildGuestExitThunk</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a3f27dda1e68a24fab4b3ed4a9cfc0e7c">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildPatchableThunk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aedeb89fa4ceb608d9d49bcd53ddcd2c1">llvm::CloneFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a993ad5e82f2d59de8127cfcb38a62e0a">llvm::orc::cloneFunctionDecl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab371d6b308eb9772bdec63cf7a041407">llvm::CloneModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e9604d679f4806943544dceaeb68149">llvm::convertToDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/elimavailextern-cpp/#a0dff0e83176712b3e57686c7164eb7c0">convertToLocalCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a452dcc29fd5e19bda874218e10a8945c">createCloneDeclaration</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-jmcinstrumenter-cpp-/#aea6556d942d972a777204187dd1600e5">anonymous{JMCInstrumenter.cpp}::createDefaultCheckFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a2bd6903bee5451ebaffd790ccf869664">llvm::MIRParserImpl::createDummyFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#a6406a80ca9230c2d3e441f6975dba745">createFPFnStub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#acb76fa37c3f506da974ee1932b37eeaa">createFrameHelperMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a272d004d22ae2326fa35628cff91dd69">llvm::RandomIRBuilder::createFunctionDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af0793991541abccfec5c0d8831612b7b">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::createNoAllocVariant</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a274467e5dc615c3f67e96d645c6b9cd3">anonymous{OffloadWrapper.cpp}::createRegisterFatbinFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#afb5a26693a2aa4ccb54923bf6a6e86d6">anonymous{OffloadWrapper.cpp}::createRegisterFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#aa95d3be8182edf7e68419d38f31dc9de">anonymous{OffloadWrapper.cpp}::createRegisterGlobalsFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer/#a7c9e3a3c2e449cbc1dfebc37503af252">llvm::orc::ReOptimizeLayer::createReoptimizeCall</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a45f6cbf770c1d990014838ceb300e936">llvm::Attributor::createShallowWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/thunkinserter/#a1a95b72d4c28ba76251171967da03b01">llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::createThunkFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a483af07ad9cee019751803fda2e04d1e">anonymous{OffloadWrapper.cpp}::createUnregisterFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixfunctionbitcasts-cpp/#a96fb322d124e55de8f0fa2fe7e19e175">createWrapper</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac800803b298b2e26368a3cc770279945">anonymous{ExpandVariadics.cpp}::ExpandVariadics::deriveFixedArityReplacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irspeculationlayer/#ac443c17bb572b2276321acc44b417ec7">llvm::orc::IRSpeculationLayer::emit</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3fb4884285f5bcb9a37d9378d1e33cd5">emitTargetTaskProxyFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/sanitizerstatreport/#a0c8e1730578d5e4181a2bd1502328802">llvm::SanitizerStatReport::finish</a>, <a href="/web-llvm/docs/api/structs/anonymous-linkallpasses-h-/forcepasslinking/#aca44adfcab3498802a1f54c6c5e42086">anonymous{LinkAllPasses.h}::ForcePassLinking::ForcePassLinking</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a7ea4fb4d6b0198f2b6eac325a8d93031">generateReproducer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyloweremscriptenehsjlj-cpp/#ad3ef075dd9dce61e81b354102b4fe107">getEmscriptenFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a669fae0a15d7219ef3ca3f3b16e3f5a0">getFreshReductionFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#afb5c7d9f47f77651e28e14b6e715badf">getOrCreateFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a071c6530f4d3362b846fdc1701c216e9">getTLIFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-typesanitizer-cpp-/typesanitizer/#aa8094f0b4dd7316f56198f0e4760b9b4">anonymous{TypeSanitizer.cpp}::TypeSanitizer::instrumentGlobals</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#af85fe4610a8ddd0d57149e73008f32fb">llvm::Attributor::internalizeFunctions</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga12f35adec814eb1d3e9a2090b14f74f5">LLVMAddFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae819b62ec706cb229654ea5fb6553501">llvm::lowerGlobalIFuncUsersAsGlobalCtor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/globalctordtorscraper/#a5f8ea04329212b479fa473a5b324153c">anonymous{LLJIT.cpp}::GlobalCtorDtorScraper::operator()</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#aaa1cdfbf8bbbb3d37466c44f0b8a403b">anonymous{ExpandVariadics.cpp}::ExpandVariadics::replaceAllUsesWithNewDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/extractgvpass/#aa8ccdb19bbe28d226592a236b93311e8">llvm::ExtractGVPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyloweremscriptenehsjlj-cpp-/webassemblyloweremscriptenehsjlj/#a4e54683754f6664c17d470ae3a097486">anonymous{WebAssemblyLowerEmscriptenEHSjLj.cpp}::WebAssemblyLowerEmscriptenEHSjLj::runOnModule</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a64cd5b79789610d81be5d0b2633868ae">anonymous{ThinLTOBitcodeWriter.cpp}::simplifyExternals</a> and <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#ad722656aa63d87c356ec659228865f65">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryICallBranchFunnel</a>.</p>

</div>
</div>

### Create() {#a7321f6163cd0a3ed2c1e87c63c6c4263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::Function::Create (<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; N="", <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M=nullptr)</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ad61abcbd08169ff119e819ef0482744d">llvm::GlobalValue::Linkage</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### Create() {#ab7351d0170b356c9f3487f8cc8c6cafd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * Function::Create (<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; N, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a new function and attaches it to a module.</p>


<p>Places the function in the program address space as specified by the module's data layout.</p>


<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### createWithDefaultAttr() {#a5dfae571c803bc1e2cd79bf98cc1951f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * Function::createWithDefaultAttr (<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage, unsigned AddrSpace, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; N="", <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a function with some attributes recorded in llvm.module.flags and the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> applied.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> this when synthesizing new functions that need attributes that would have been set by command line options.</p>


<p>This function should not be called from backends or the LTO pipeline. If it is called from one of those places, some default attributes will not be applied to the function.</p>


<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>, definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuctordtorlowering-cpp-/#aa82200436735a7e7831e52db45ae4580">anonymous{AMDGPUCtorDtorLowering.cpp}::createInitOrFiniKernelFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#a4f767db6edfa57ac38c654668e19b385">anonymous{NVPTXCtorDtorLowering.cpp}::createInitOrFiniKernelFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a256980e987af753b4c497757fad18000">llvm::createSanitizerCtor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getSublistAccess() {#a1f6bd8041cdf6492f78245bc2737e0be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlockListType Function::* llvm::Function::getSublistAccess (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *)</td>
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



<p>Definition at line 804 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### AllocMarker {#a7e66c8b366d630ce63cd7cdcca596a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HungOffOperandsAllocMarker llvm::Function::AllocMarker {}</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### UnknownLibFunc {#afd2c2c6ca7ba5fb629b92d17cce912a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LibFunc llvm::Function::UnknownLibFunc = <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a>(-1)</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Function Argument Iteration

### arg\_begin {#a8bf193a781a92cae52d7f9216d0824f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">arg_iterator llvm::Function::arg_begin ()</td>
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



<p>Definition at line 868 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Referenced by <a href="#a49e6c89ce42a55a93ddf38d21bbd198e">args</a>, <a href="#a36d0e82850793ac518b317fb9ecd61ec">args</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aedeb89fa4ceb608d9d49bcd53ddcd2c1">llvm::CloneFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a993ad5e82f2d59de8127cfcb38a62e0a">llvm::orc::cloneFunctionDecl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac800803b298b2e26368a3cc770279945">anonymous{ExpandVariadics.cpp}::ExpandVariadics::deriveFixedArityReplacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#acddb0d15dc6d53316188968e5acbefc7">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getNonKernelsWithLDSArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a78c7e7972f2cde9531b9f9d71196cfc5">hasSameArgumentList</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#afffa0ff2e1527ab545cef33be915c656">hostParallelCallback</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#af85fe4610a8ddd0d57149e73008f32fb">llvm::Attributor::internalizeFunctions</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluefunctionparameters/#ga670f0e5258f93e51e6700309ae99dfbe">LLVMGetNextParam</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluefunctionparameters/#ga9bd2822b01bf496c297a3daeeea63d52">LLVMGetParam</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af7668ce8080668a4f0ceac24e70c9f00">targetParallelCallback</a>.</p>

</div>
</div>

### arg\_begin {#a414f3bebd529527d4f7d8b7320b625c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_arg_iterator llvm::Function::arg_begin ()</td>
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



<p>Definition at line 872 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### arg\_end {#a8300ac1ef141b8a7c63c13fa9369d976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">arg_iterator llvm::Function::arg_end ()</td>
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



<p>Definition at line 877 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Referenced by <a href="#a49e6c89ce42a55a93ddf38d21bbd198e">args</a>, <a href="#a36d0e82850793ac518b317fb9ecd61ec">args</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#acddb0d15dc6d53316188968e5acbefc7">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getNonKernelsWithLDSArguments</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>.</p>

</div>
</div>

### arg\_end {#a40a13b2b2dc684c189642183fc4d81bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_arg_iterator llvm::Function::arg_end ()</td>
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



<p>Definition at line 881 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>

</div>
</div>

### args {#a49e6c89ce42a55a93ddf38d21bbd198e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; arg_iterator &gt; llvm::Function::args ()</td>
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



<p>Definition at line 892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="#a8bf193a781a92cae52d7f9216d0824f8">arg_begin</a>, <a href="#a8300ac1ef141b8a7c63c13fa9369d976">arg_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aa35af336fee32786b6551e23d5b55fcf">AddAliasScopeMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ae54a643a9f9d83374bb4d7d22d4662d7">AddAlignmentAssumptions</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac1b2be839460bb277d4f07f4aa5225ac">llvm::CloneFunctionInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e263b9cd2bdbbbaf3d78a2caba5cbf5">llvm::computeSignatureVTs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a7cc70f4d5f07cada554efd4e2c8386c4">dontUseFastISelFor</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifycallsitereturned/#a249035cbf55468e38187c74bfcd1204b">anonymous{AttributorAttributes.cpp}::AAValueSimplifyCallSiteReturned::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#aba8fa9d02ad8b557faaf41b37b714ba4">llvm::AArch64CallLowering::isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a1c1ba0852c28df8598b5a0d2f0abb3aa">llvm::AMDGPUCallLowering::isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9330a86a613cf892ee5c7f515713f200">llvm::SITargetLowering::isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluefunctionparameters/#gaebe00246fb8c2af071d3eb2c27882242">LLVMGetParams</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a>.</p>

</div>
</div>

### args {#a36d0e82850793ac518b317fb9ecd61ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_arg_iterator &gt; llvm::Function::args ()</td>
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



<p>Definition at line 895 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>References <a href="#a8bf193a781a92cae52d7f9216d0824f8">arg_begin</a>, <a href="#a8300ac1ef141b8a7c63c13fa9369d976">arg_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### getArg {#aecf2b6d6f052a378dd8f69fd1bb700b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Argument * llvm::Function::getArg (unsigned i)</td>
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



<p>Definition at line 886 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a8d0a2ebeeedeb0bd16a52affb7f6ed88">llvm::Attributor::checkForAllCallSites</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af0793991541abccfec5c0d8831612b7b">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::createNoAllocVariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#ae86fef7fc5831c2514bff95bdf784d09">createSwitchStatement</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#afffd4df1bba5cd5416f615e919a8fa66">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandVAIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a556a77d9b9acf322358b2c4131986b13">findOrCreatePHIInBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a9854202d54cc31542b08f1822ceee85d">llvm::IRPosition::getArg</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a265735d2c2edc0a1a03611e7aadd24cd">llvm::IRPosition::getAssociatedArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a0f104a4f4a7edce928ac0aea2a3509b8">lowerFunnelShifts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a96b5bd50d8e96b4c76ffc26508ce774d">replaceArgumentUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a7e2cad7ab18db9a3c940afc609c223dc">replaceCalledFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#ace02ac07a3f704ffd345301bff92e5a8">replaceConstants</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerkernelarguments-cpp-/preloadkernelarginfo/#a7a5253091344c2d534f5afd16941e25d">anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::tryAllocImplicitArgPreloadSGPRs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ad96e48f13961854d2242e9462a920394">unpackFromRegLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a448318fedd7b77f12f1163c8d5a5b10a">unpackFromRegLoc</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad37834e4f8e16e808997aef286954fd0">upgradeNVVMIntrinsicCall</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">Function.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/cfgprinter-cpp">CFGPrinter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
