---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/globalvariable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GlobalVariable` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::GlobalVariable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
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

## Friends Index

<table class="doxyMembersIndex">

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

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ea64c7dae47dcfa2c9f5775fb5915d">GlobalVariable</a> (Type *Ty, bool isConstant, LinkageTypes Linkage, Constant *Initializer=nullptr, const Twine &amp;Name="", ThreadLocalMode=NotThreadLocal, unsigned AddressSpace=0, bool isExternallyInitialized=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> ctor - If a parent module is specified, the global is automatically inserted into the end of the specified modules global list. <a href="#af9ea64c7dae47dcfa2c9f5775fb5915d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9f31014b7b244d627f6bd18109c5987">GlobalVariable</a> (Module &amp;M, Type *Ty, bool isConstant, LinkageTypes Linkage, Constant *Initializer, const Twine &amp;Name="", GlobalVariable *InsertBefore=nullptr, ThreadLocalMode=NotThreadLocal, std::optional&lt; unsigned &gt; AddressSpace=std::nullopt, bool isExternallyInitialized=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> ctor - This creates a global and inserts it before the specified other global. <a href="#af9f31014b7b244d627f6bd18109c5987">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e3454f4bf8557aaa318e62c4b173622">GlobalVariable</a> (const GlobalVariable &amp;)=delete</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae738ec4a00d3e140634ad5ff8da1252d">~GlobalVariable</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4824112678b4304314abf4b358750b9b">operator=</a> (const GlobalVariable &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2c8efc829b793c13bc67f6ee0861889">operator new</a> (size_t s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3ff3bb824d1daa30abeb7e2217ce860">operator delete</a> (void *ptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30a5542d525647ee50cfec3fb04bc208">DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a> (Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide fast operand accessors. <a href="#a30a5542d525647ee50cfec3fb04bc208">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c66d4eff947253e7610a66379974d63">hasInitializer</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Definitions have initializers, declarations don't. <a href="#a1c66d4eff947253e7610a66379974d63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec2d700d8b1e57f830a673c39a1f30dc">hasDefinitiveInitializer</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasDefinitiveInitializer - Whether the global variable has an initializer, and any other instances of the global (this can happen due to weak linkage) are guaranteed to have the same initializer. <a href="#aec2d700d8b1e57f830a673c39a1f30dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9379319a0f19f0c42b5ee18d9f02373">hasUniqueInitializer</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasUniqueInitializer - Whether the global variable has an initializer, and any changes made to the initializer will turn up in the final executable. <a href="#ad9379319a0f19f0c42b5ee18d9f02373">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0698d5bcabbfbca4f56a9d7a81cecb25">getInitializer</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getInitializer - Return the initializer for this global variable. <a href="#a0698d5bcabbfbca4f56a9d7a81cecb25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73141a4cd752f32b33c52e8189cff2ec">getInitializer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a095f8f031d99ce3c0b25478713293dea">setInitializer</a> (Constant *InitVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setInitializer - Sets the initializer for this global variable, removing any existing initializer if InitVal==NULL. <a href="#a095f8f031d99ce3c0b25478713293dea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36da270a9d55e053ba96b61f7f09a914">replaceInitializer</a> (Constant *InitVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>replaceInitializer - Sets the initializer for this global variable, and sets the value type of the global to the type of the initializer. <a href="#a36da270a9d55e053ba96b61f7f09a914">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa859e108741fa64681b63f0c0c672512">isConstant</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the value is a global constant, its value is immutable throughout the runtime execution of the program. <a href="#aa859e108741fa64681b63f0c0c672512">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40ae67d31da67ca17ed016839faf3390">setConstant</a> (bool Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f6dab3350ff78735031a6a62f344f18">isExternallyInitialized</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb67848f8b455ce9c5224a1f50b6c6e8">setExternallyInitialized</a> (bool Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53f47ebcc1a7ac4553ba2a2eeca596e5">copyAttributesFrom</a> (const GlobalVariable *Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>copyAttributesFrom - copy all additional attributes (those not needed to create a <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a>) from the <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> Src to this one. <a href="#a53f47ebcc1a7ac4553ba2a2eeca596e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22e076c4cf000eba885dd00048641c6f">removeFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeFromParent - This method unlinks 'this' from the containing module, but does not delete it. <a href="#a22e076c4cf000eba885dd00048641c6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0cf03d5de37330b1eb69dd22a1d5057">eraseFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>eraseFromParent - This method unlinks 'this' from the containing module and deletes it. <a href="#ae0cf03d5de37330b1eb69dd22a1d5057">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af99541657316d3a761845dc5b8d845d9">dropAllReferences</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop all references in preparation to destroy the <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a>. <a href="#af99541657316d3a761845dc5b8d845d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebcc339b418cae92442b394b33359705">addDebugInfo</a> (DIGlobalVariableExpression *GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attach a <a href="/web-llvm/docs/api/classes/llvm/diglobalvariableexpression">DIGlobalVariableExpression</a>. <a href="#aebcc339b418cae92442b394b33359705">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bd3c333fa06c8fae17d52a78db3fde2">getDebugInfo</a> (SmallVectorImpl&lt; DIGlobalVariableExpression * &gt; &amp;GVs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fill the vector with all debug info attachements. <a href="#a7bd3c333fa06c8fae17d52a78db3fde2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af763d890b27bbeacc1b06636740de9a1">addAttribute</a> (Attribute::AttrKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add attribute to this global. <a href="#af763d890b27bbeacc1b06636740de9a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cee3c634aa5de8c51e6eaa4e41898bc">addAttribute</a> (StringRef Kind, StringRef Val=StringRef())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add attribute to this global. <a href="#a6cee3c634aa5de8c51e6eaa4e41898bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d18aef18dd1ef1e35f038d830fed316">hasAttribute</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute exists. <a href="#a0d18aef18dd1ef1e35f038d830fed316">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aaddc169871aa709fcdc41adf9b9e1f">hasAttribute</a> (StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute exists. <a href="#a9aaddc169871aa709fcdc41adf9b9e1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a42a0e1c35c9b83aaae9e6cbd367d2">hasAttributes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if any attributes exist. <a href="#a24a42a0e1c35c9b83aaae9e6cbd367d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2125b82490a82e9baae432db222668d7">getAttribute</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute object. <a href="#a2125b82490a82e9baae432db222668d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fe127548d8e01ddb7f30b78d951ca77">getAttribute</a> (StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute object. <a href="#a7fe127548d8e01ddb7f30b78d951ca77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e5805d3565801dc32ec696d17624c6e">getAttributes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute set for this global. <a href="#a2e5805d3565801dc32ec696d17624c6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f97c03389898566620894f7ba674df7">getAttributesAsList</a> (unsigned index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return attribute set as list with index. <a href="#a7f97c03389898566620894f7ba674df7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a354e3a068c327a26d861d0d6851c90f0">setAttributes</a> (AttributeSet A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set attribute list for this global. <a href="#a354e3a068c327a26d861d0d6851c90f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a794d6b65a466293b4ce971189b2e9ab1">hasImplicitSection</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if section name is present. <a href="#a794d6b65a466293b4ce971189b2e9ab1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a1244217eda4d01f9891f6c2dca7a9f">getCodeModelRaw</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the custom code model raw value of this global. <a href="#a0a1244217eda4d01f9891f6c2dca7a9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a339c8e24dbf600ae50b1aac2be2c1dbf">getCodeModel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the custom code model of this global if it has one. <a href="#a339c8e24dbf600ae50b1aac2be2c1dbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2b82881a2653d3ec234491e0c84ea71">setCodeModel</a> (CodeModel::Model CM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the code model for this global. <a href="#ac2b82881a2653d3ec234491e0c84ea71">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a209682ffdccb028dce7843c0bc639fe2">setGlobalVariableNumOperands</a> (unsigned NumOps)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the number of operands on a <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a>. <a href="#a209682ffdccb028dce7843c0bc639fe2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac88e1d3b61a6fa53a1f08d4f1846e81b">Attrs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaccefc19ade155690d250f5e9247e096">isConstantGlobal</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c21a6de0097c9986426ef37b54378f4">isExternallyInitializedConstant</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8999cd0f7babf4c2b9158b16e2d1decb">classof</a> (const Value *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/user/intrusiveoperandsallocmarker">IntrusiveOperandsAllocMarker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb812898ea1801a6d25fbc63c7360b4d">AllocMarker</a> {1}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac00aa73e86debb93935ca11705437c3d">CodeModelBits</a> = <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a456d28b8615245df4184bbeabdad0849a8b031f08caa89705d0671b902342ab09">LastCodeModelBit</a> - <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a456d28b8615245df4184bbeabdad0849a3506f6011beaf16702d54a98bb702c0c">LastAlignmentBit</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3dd20ecaece728843cc2b3adf8a11dd">CodeModelMask</a> = (1 &lt;&lt; CodeModelBits) - 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6a34eff9dc39ff2c4a610c44b66ed32">CodeModelShift</a> = <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a456d28b8615245df4184bbeabdad0849a3506f6011beaf16702d54a98bb702c0c">LastAlignmentBit</a> + 1</td>
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


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<div class="doxySectionDef">

## Friends

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


<p>Definition at line 1 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GlobalVariable() {#af9ea64c7dae47dcfa2c9f5775fb5915d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable::GlobalVariable (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, bool isConstant, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Initializer=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62">ThreadLocalMode</a> TLMode=<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">NotThreadLocal</a>, unsigned AddressSpace=0, bool isExternallyInitialized=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> ctor - If a parent module is specified, the global is automatically inserted into the end of the specified modules global list.</p>

<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>, definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a5b53de0b76d2880fb3e4b487cb4fee75">llvm::GlobalObject::GlobalObject</a>, <a href="#a0f6dab3350ff78735031a6a62f344f18">isExternallyInitialized</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#aac306fd31390128f9c2557c889a19146">llvm::PointerType::isValidElementType</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a472652f9e89e006426f371fcbfa6f619">llvm::GlobalValue::setThreadLocalMode</a>.</p>


<p>Referenced by <a href="#a53f47ebcc1a7ac4553ba2a2eeca596e5">copyAttributesFrom</a>, <a href="#a5e3454f4bf8557aaa318e62c4b173622">GlobalVariable</a>, <a href="#af9f31014b7b244d627f6bd18109c5987">GlobalVariable</a> and <a href="#a4824112678b4304314abf4b358750b9b">operator=</a>.</p>

</div>
</div>

### GlobalVariable() {#af9f31014b7b244d627f6bd18109c5987}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable::GlobalVariable (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, bool isConstant, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Initializer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * InsertBefore=nullptr, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62">ThreadLocalMode</a> TLMode=<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">NotThreadLocal</a>, std::optional&lt; unsigned &gt; AddressSpace=std::nullopt, bool isExternallyInitialized=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> ctor - This creates a global and inserts it before the specified other global.</p>

<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>, definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa5d2c67dadc073dac78224224ee89350">llvm::GlobalValue::getDataLayout</a>, <a href="#af9ea64c7dae47dcfa2c9f5775fb5915d">GlobalVariable</a> and <a href="#a0f6dab3350ff78735031a6a62f344f18">isExternallyInitialized</a>.</p>

</div>
</div>

### GlobalVariable() {#a5e3454f4bf8557aaa318e62c4b173622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GlobalVariable::GlobalVariable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp;)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>Reference <a href="#af9ea64c7dae47dcfa2c9f5775fb5915d">GlobalVariable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~GlobalVariable() {#ae738ec4a00d3e140634ad5ff8da1252d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GlobalVariable::~GlobalVariable ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>Reference <a href="#af99541657316d3a761845dc5b8d845d9">dropAllReferences</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator delete() {#ad3ff3bb824d1daa30abeb7e2217ce860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalVariable::operator delete (void * ptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>

</div>
</div>

### operator new() {#af2c8efc829b793c13bc67f6ee0861889}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::GlobalVariable::operator new (size_t s)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>

</div>
</div>

### operator=() {#a4824112678b4304314abf4b358750b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable &amp; llvm::GlobalVariable::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp;)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af9ea64c7dae47dcfa2c9f5775fb5915d">GlobalVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab9ef1cd0d25962bbb4785ae14258ed5d">llvm::Value::NumUserOperands</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAttribute() {#af763d890b27bbeacc1b06636740de9a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalVariable::addAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add attribute to this global.</p>

<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-bpfpreserveditype-cpp-/#a72adf7d117af6ebe1a3aee68b6e3e782">anonymous{BPFPreserveDIType.cpp}::BPFPreserveDITypeImpl</a>.</p>

</div>
</div>

### addAttribute() {#a6cee3c634aa5de8c51e6eaa4e41898bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalVariable::addAttribute (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Val=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>())</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add attribute to this global.</p>

<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>

</div>
</div>

### addDebugInfo() {#aebcc339b418cae92442b394b33359705}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalVariable::addDebugInfo (<a href="/web-llvm/docs/api/classes/llvm/diglobalvariableexpression">DIGlobalVariableExpression</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attach a <a href="/web-llvm/docs/api/classes/llvm/diglobalvariableexpression">DIGlobalVariableExpression</a>.</p>

<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>, definition at line 1887 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/globalobject/#aa1b0638c63ba711320b3bb9c69367ed6">llvm::GlobalObject::addMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#a5ef5715d34861beabf2977f6df2b5131">copyDebugLocMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a6989fb54b0ff045520a716621e13067d">transferSRADebugInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>.</p>

</div>
</div>

### copyAttributesFrom() {#a53f47ebcc1a7ac4553ba2a2eeca596e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalVariable::copyAttributesFrom (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>copyAttributesFrom - copy all additional attributes (those not needed to create a <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a>) from the <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> Src to this one.</p>


<p>Copy all additional attributes (those not needed to create a <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a>) from the <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> Src to this one.</p>


<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>, definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a92be15c3c916aa2e05b5485075882947">llvm::GlobalObject::copyAttributesFrom</a>, <a href="#af9ea64c7dae47dcfa2c9f5775fb5915d">GlobalVariable</a>, <a href="#a354e3a068c327a26d861d0d6851c90f0">setAttributes</a>, <a href="#ac2b82881a2653d3ec234491e0c84ea71">setCodeModel</a> and <a href="#adb67848f8b455ce9c5224a1f50b6c6e8">setExternallyInitialized</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a88db5656a6723001ab395e9db68094c2">llvm::orc::cloneGlobalVariableDecl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab371d6b308eb9772bdec63cf7a041407">llvm::CloneModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxgenerictonvvm-cpp-/generictonvvm/#ad0fae911d15e72e7f72b040a655dc081">anonymous{NVPTXGenericToNVVM.cpp}::GenericToNVVM::runOnModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#af376f4f0e0b55e40407912678b736863">SRAGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a9a13dab9647bddbb0cce81565a8249a1">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::uniquifyGVPerKernel</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a2b81e19b3ddf7ec786c5105ba5470153">widenGlobalVariable</a>.</p>

</div>
</div>

### DECLARE\_TRANSPARENT\_OPERAND\_ACCESSORS() {#a30a5542d525647ee50cfec3fb04bc208}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GlobalVariable::DECLARE_TRANSPARENT_OPERAND_ACCESSORS (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provide fast operand accessors.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>

</div>
</div>

### dropAllReferences() {#af99541657316d3a761845dc5b8d845d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalVariable::dropAllReferences ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Drop all references in preparation to destroy the <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a>.</p>


<p>This drops not only the reference to the initializer but also to any metadata.</p>


<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>, definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalobject/#ad151fceb9a0e77a8a8017d4f68791811">llvm::GlobalObject::clearMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a48ec5fcee6d2c17c723e8e67f169f948">llvm::User::dropAllReferences</a>.</p>


<p>Referenced by <a href="#ae738ec4a00d3e140634ad5ff8da1252d">~GlobalVariable</a>.</p>

</div>
</div>

### eraseFromParent() {#ae0cf03d5de37330b1eb69dd22a1d5057}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalVariable::eraseFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>eraseFromParent - This method unlinks 'this' from the containing module and deletes it.</p>

<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>, definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/module/#a9b8e4e706dbd7c8fadfd8593bb17979d">llvm::Module::eraseGlobalVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a24f2551aaa1c96b279e792995deddd7f">appendToUsedList</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#a96bb7d07114f84d88a58245118c5a1e2">anonymous{NVPTXCtorDtorLowering.cpp}::createInitOrFiniKernel</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcorelowerthreadlocal-cpp-/xcorelowerthreadlocal/#adb1323a587666f6b6a98e4d7c2ba24af">anonymous{XCoreLowerThreadLocal.cpp}::XCoreLowerThreadLocal::lowerGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/globalctordtorscraper/#a5f8ea04329212b479fa473a5b324153c">anonymous{LLJIT.cpp}::GlobalCtorDtorScraper::operator()</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ab7fe47fe1b533f4c9bdd23baf28f3c8c">OptimizeAwayTrappingUsesOfLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a56b5a0fa4891dca73946affd4e6e3ffd">removeFromUsedList</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#acf172e841018fd16e65771f5ade0b297">replace</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxgenerictonvvm-cpp-/generictonvvm/#ad0fae911d15e72e7f72b040a655dc081">anonymous{NVPTXGenericToNVVM.cpp}::GenericToNVVM::runOnModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#af376f4f0e0b55e40407912678b736863">SRAGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a44ca78ca7013578c50cdd38647811346">transformGlobalArray</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>.</p>

</div>
</div>

### getAttribute() {#a2125b82490a82e9baae432db222668d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute llvm::GlobalVariable::getAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attribute object.</p>

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>

</div>
</div>

### getAttribute() {#a7fe127548d8e01ddb7f30b78d951ca77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute llvm::GlobalVariable::getAttribute (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attribute object.</p>

<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>

</div>
</div>

### getAttributes() {#a2e5805d3565801dc32ec696d17624c6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet llvm::GlobalVariable::getAttributes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attribute set for this global.</p>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a53445d1abe416390025be3ba8262a719">handlePragmaClangSection</a>, <a href="#a794d6b65a466293b4ce971189b2e9ab1">hasImplicitSection</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>.</p>

</div>
</div>

### getAttributesAsList() {#a7f97c03389898566620894f7ba674df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::GlobalVariable::getAttributesAsList (unsigned index)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return attribute set as list with index.</p>


<p>FIXME: This may not be required once ValueEnumerators in bitcode-writer can enumerate attribute-set.</p>


<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a4ac0d01bf5ca24e679de53067c8f6a44">llvm::AttributeList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a> and <a href="#a24a42a0e1c35c9b83aaae9e6cbd367d2">hasAttributes</a>.</p>

</div>
</div>

### getCodeModel() {#a339c8e24dbf600ae50b1aac2be2c1dbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CodeModel::Model &gt; llvm::GlobalVariable::getCodeModel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the custom code model of this global if it has one.</p>


<p>If this global does not have a custom code model, the empty instance will be returned.</p>


<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>Reference <a href="#a0a1244217eda4d01f9891f6c2dca7a9f">getCodeModelRaw</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#af5ca20f498adaec1f940475984ad7050">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::doInitialization</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a> and <a href="#ac2b82881a2653d3ec234491e0c84ea71">setCodeModel</a>.</p>

</div>
</div>

### getCodeModelRaw() {#a0a1244217eda4d01f9891f6c2dca7a9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalVariable::getCodeModelRaw ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the custom code model raw value of this global.</p>

<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aaf6a02ecb2b904406b783da5bfd6564e">llvm::GlobalValue::getGlobalValueSubClassData</a>.</p>


<p>Referenced by <a href="#a339c8e24dbf600ae50b1aac2be2c1dbf">getCodeModel</a>.</p>

</div>
</div>

### getDebugInfo() {#a7bd3c333fa06c8fae17d52a78db3fde2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalVariable::getDebugInfo (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diglobalvariableexpression">DIGlobalVariableExpression</a> * &gt; &amp; GVs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fill the vector with all debug info attachements.</p>

<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>, definition at line 1891 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#aef569d822dbf572ae71954d6831ce8a9">llvm::GlobalObject::getMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#a5ef5715d34861beabf2977f6df2b5131">copyDebugLocMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a6989fb54b0ff045520a716621e13067d">transferSRADebugInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>.</p>

</div>
</div>

### getInitializer() {#a0698d5bcabbfbca4f56a9d7a81cecb25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Constant * llvm::GlobalVariable::getInitializer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getInitializer - Return the initializer for this global variable.</p>


<p>It is illegal to call this method if the global is external, because we cannot tell what the value is initialized to!</p>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a1c66d4eff947253e7610a66379974d63">hasInitializer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/loweremutls-cpp/#aeddd04f458fd6e9db5a892543636e240">addEmuTlsVar</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a3a5262b6225fdc05cfea242647c56db6">anonymous{WholeProgramDevirt.cpp}::DevirtModule::buildTypeIdentifierMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/directxirpasses/pointertypeanalysis-cpp/#ac6745cfa7af2beebe88a7d3609c7875d">classifyGlobalCtorPointerType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ac3cf098d54027ac28278b060376bdcbd">CleanupConstantGlobalUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a4062c17e282cb2667cf0d52150c67fea">collectSRATypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a3aaaacc4c370cf25d48e3ef4f25885c4">collectUsedGlobals</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#aab0bb9923065afc9aca06aec133ff91e">anonymous{NVPTXCtorDtorLowering.cpp}::createInitOrFiniGlobals</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuctordtorlowering-cpp-/#a0d730fa8562179d7bcfc965fe37dfbd7">anonymous{AMDGPUCtorDtorLowering.cpp}::createInitOrFiniKernel</a>, <a href="/web-llvm/docs/api/classes/anonymous-directxasmprinter-cpp-/dxilasmprinter/#a48b15639730822b6cab292e69f1a93a7">anonymous{DirectXAsmPrinter.cpp}::DXILAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#ab7906bdf774a35b56cb2e908d012472c">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a673ca077823c034cab2b172947847f19">llvm::AMDGPUAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#ab98a836a506bb90245c243f8e4da3162">llvm::ExecutionEngine::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4cc8d8a6afc7262b599109c2029fc311">llvm::AsmPrinter::emitSpecialLLVMGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ab2790230883e599a288a12ded77463bc">llvm::HexagonInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a0f076ea04eda5249d0527c704881cdf1">anonymous{OffloadBinary.cpp}::extractFromBitcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acae633d6254bf68b6ad97699f786b3b0">llvm::ExtractTypeInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a221bfefa2a7606c89cb5a8635375f891">findFuncPointers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#aac8ef9c8745bf77faa38eb1cd16fb4a7">findGlobalCtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#a8c82bb68e32af4477888125c41741a7f">FindUsedValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a348eede5b05a57edfafe7f8595cced8b">findUsedValues</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36b03d4697c30b32e8762cb0dfd66761">llvm::getConstantDataArrayInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afc0a5ead9186ecbdc82f6ebe331c25ee">llvm::getFunctionAtVTableOffset</a>, <a href="/web-llvm/docs/api/namespaces/kernelinfo/#afc35ca85aef2e06a527c9edfe484eb56">KernelInfo::getKernelEnvironementFromKernelInitCB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a847a04fa34e6ed7f199e9f7704ab706f">llvm::getPGOFuncNameVarInitializer</a>, <a href="/web-llvm/docs/api/classes/anonymous-structuralhash-cpp-/structuralhashimpl/#ac9720fa4fb8bcc62c98a125f0b09fe9e">anonymous{StructuralHash.cpp}::StructuralHashImpl::hashGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd9e1dd09e624812bf964cba3ae3a34d">llvm::hasInitializer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxasmprinter-cpp/#a044419a3533ccf34b2d18b641dc053d2">isEmptyXXStructor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb5dc4f19ccfe906a67745d10a39b4c6">llvm::isIRPGOFlagSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a9a6f055381f5a946e37ab4d9e4a221d8">llvm::AMDGPU::isLDSVariableToLower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/targetloweringobjectfile-cpp/#a9b9e767ff08744d8a078b672e57fb24f">isSuitableForBSS</a>, <a href="/web-llvm/docs/api/groups/llvmcorevalueconstantglobalvariable/#ga9b1abdccb3c2450804dc654d6865106d">LLVMGetInitializer</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcorelowerthreadlocal-cpp-/xcorelowerthreadlocal/#adb1323a587666f6b6a98e4d7c2ba24af">anonymous{XCoreLowerThreadLocal.cpp}::XCoreLowerThreadLocal::lowerGlobal</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#adc155013f4c88522a318f0f19a29cbb2">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a8d20a7c0aa0ef76c738e2ca9e21d35d5">OptimizeGlobalVars</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a13c72931678c2da267fc265c7a2afdfb">optimizeOnceStoredGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a30e49f13bd17ed097579ddf598241386">parseGlobalCtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ad7593156486a0b9a2c48cfd1ab7b29a5">parseJumpTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3002d96da0f9030af718fbe2961b913f">llvm::ReadByteArrayFromGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-objcarcapelim-cpp-/#a9bc5959a169d48b207404d44b7867477">anonymous{ObjCARCAPElim.cpp}::runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a60823e6b4ff77b319b51c9eb634241e2">llvm::ExecutionEngine::runStaticConstructorsDestructors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a004b3a18ad13375ad40e88cd41a0fe97">shouldConvertToRelLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#a74dbf3215dd56f387425123cbff44a36">llvm::SCCPInstVisitor::trackValueOfGlobalVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a44ca78ca7013578c50cdd38647811346">transformGlobalArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a6594a7d514d3847ccbe52b66a49d8ee5">tryToRecognizeTableBasedCttz</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a4f18aa17f81c88c8fa89c76563a6d510">tryWidenGlobalArraysUsedByMemcpy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a9a13dab9647bddbb0cce81565a8249a1">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::uniquifyGVPerKernel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab02a4d4ecc962ea09ed6c79ebc699a54">updateAsyncFuncPointerContextSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95b7e7311ec52352ada27699c3c9c470">llvm::UpgradeGlobalVariable</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a2b81e19b3ddf7ec786c5105ba5470153">widenGlobalVariable</a>.</p>

</div>
</div>

### getInitializer() {#a73141a4cd752f32b33c52e8189cff2ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::GlobalVariable::getInitializer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a1c66d4eff947253e7610a66379974d63">hasInitializer</a>.</p>

</div>
</div>

### hasAttribute() {#a0d18aef18dd1ef1e35f038d830fed316}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalVariable::hasAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the attribute exists.</p>

<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a1592f31751bef2ac04349cb6be511d18">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a29ca9a2c296f3f458f12419d0fad2cc5">hasTocDataAttr</a> and <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a3b244792bc2277f0800d9e15c2eb935b">llvm::BTFDebug::InstLower</a>.</p>

</div>
</div>

### hasAttribute() {#a9aaddc169871aa709fcdc41adf9b9e1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalVariable::hasAttribute (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the attribute exists.</p>

<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>

</div>
</div>

### hasAttributes() {#a24a42a0e1c35c9b83aaae9e6cbd367d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalVariable::hasAttributes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if any attributes exist.</p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>Referenced by <a href="#a7f97c03389898566620894f7ba674df7">getAttributesAsList</a>.</p>

</div>
</div>

### hasDefinitiveInitializer() {#aec2d700d8b1e57f830a673c39a1f30dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalVariable::hasDefinitiveInitializer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>hasDefinitiveInitializer - Whether the global variable has an initializer, and any other instances of the global (this can happen due to weak linkage) are guaranteed to have the same initializer.</p>


<p>Note that if you want to transform a global, you must use <a href="#ad9379319a0f19f0c42b5ee18d9f02373">hasUniqueInitializer()</a> instead, because of the *_odr linkage type.</p>


<p>Example:</p>


<p><em>=</em> global SomeType* null - Initializer is both definitive and unique.</p>


<p><b>=</b> global weak SomeType* null - Initializer is neither definitive nor unique.</p>


<p><span class="doxyComputerOutput">=</span> global weak_odr SomeType* null - Initializer is definitive, but not unique.</p>


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>References <a href="#a1c66d4eff947253e7610a66379974d63">hasInitializer</a>, <a href="#a0f6dab3350ff78735031a6a62f344f18">isExternallyInitialized</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa1558e13ceef68db8ea9f4e3b5a64cbd">llvm::GlobalValue::isInterposable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#ab7c3af18d8706c2d91fd7e2f88424336">llvm::VNCoercion::analyzeLoadFromClobberingMemInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7414a7c636bc5a30b0e8478019a1bcd4">llvm::canTrackGlobalVariableInterprocedurally</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36b03d4697c30b32e8762cb0dfd66761">llvm::getConstantDataArrayInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#a6ebdfd799686fe407798a4d503a41cd9">isUnmergeableGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ad7593156486a0b9a2c48cfd1ab7b29a5">parseJumpTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3002d96da0f9030af718fbe2961b913f">llvm::ReadByteArrayFromGlobal</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-objcarcapelim-cpp-/#a9bc5959a169d48b207404d44b7867477">anonymous{ObjCARCAPElim.cpp}::runImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad3219f7b717320ae52f53ccb09ad5a84">llvm::tryPromoteCall</a>.</p>

</div>
</div>

### hasImplicitSection() {#a794d6b65a466293b4ce971189b2e9ab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalVariable::hasImplicitSection ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if section name is present.</p>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>References <a href="#a2e5805d3565801dc32ec696d17624c6e">getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a51fc96070af1597981c3000171e1a5ab">llvm::AttributeSet::hasAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-directxasmprinter-cpp-/dxilasmprinter/#a48b15639730822b6cab292e69f1a93a7">anonymous{DirectXAsmPrinter.cpp}::DXILAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a53445d1abe416390025be3ba8262a719">handlePragmaClangSection</a> and <a href="/web-llvm/docs/api/classes/anonymous-globalmerge-cpp-/globalmergeimpl/#a9fbe2dcb11cb3bb78be4d97f388b0c5d">anonymous{GlobalMerge.cpp}::GlobalMergeImpl::run</a>.</p>

</div>
</div>

### hasInitializer() {#a1c66d4eff947253e7610a66379974d63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalVariable::hasInitializer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Definitions have initializers, declarations don't.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a32e606ac4c88f71f14212e42b808e7f4">llvm::GlobalValue::isDeclaration</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/loweremutls-cpp/#aeddd04f458fd6e9db5a892543636e240">addEmuTlsVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a3aaaacc4c370cf25d48e3ef4f25885c4">collectUsedGlobals</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuctordtorlowering-cpp-/#a0d730fa8562179d7bcfc965fe37dfbd7">anonymous{AMDGPUCtorDtorLowering.cpp}::createInitOrFiniKernel</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#a96bb7d07114f84d88a58245118c5a1e2">anonymous{NVPTXCtorDtorLowering.cpp}::createInitOrFiniKernel</a>, <a href="/web-llvm/docs/api/classes/anonymous-directxasmprinter-cpp-/dxilasmprinter/#a48b15639730822b6cab292e69f1a93a7">anonymous{DirectXAsmPrinter.cpp}::DXILAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#ab7906bdf774a35b56cb2e908d012472c">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a673ca077823c034cab2b172947847f19">llvm::AMDGPUAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a0202522d1384c2ad88417c496ae62068">llvm::WebAssemblyAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4cc8d8a6afc7262b599109c2029fc311">llvm::AsmPrinter::emitSpecialLLVMGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acae633d6254bf68b6ad97699f786b3b0">llvm::ExtractTypeInfo</a>, <a href="#a73141a4cd752f32b33c52e8189cff2ec">getInitializer</a>, <a href="#a0698d5bcabbfbca4f56a9d7a81cecb25">getInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#abc7937248226859bf5a5d64a28c8269f">llvm::DataLayout::getPreferredAlign</a>, <a href="#aec2d700d8b1e57f830a673c39a1f30dc">hasDefinitiveInitializer</a>, <a href="/web-llvm/docs/api/classes/anonymous-structuralhash-cpp-/structuralhashimpl/#ac9720fa4fb8bcc62c98a125f0b09fe9e">anonymous{StructuralHash.cpp}::StructuralHashImpl::hashGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd9e1dd09e624812bf964cba3ae3a34d">llvm::hasInitializer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a1db077f1815950aa2f419be901c429c6">isGOTEquivalentCandidate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb5dc4f19ccfe906a67745d10a39b4c6">llvm::isIRPGOFlagSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a9a6f055381f5a946e37ab4d9e4a221d8">llvm::AMDGPU::isLDSVariableToLower</a>, <a href="/web-llvm/docs/api/groups/llvmcorevalueconstantglobalvariable/#ga9b1abdccb3c2450804dc654d6865106d">LLVMGetInitializer</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcorelowerthreadlocal-cpp-/xcorelowerthreadlocal/#adb1323a587666f6b6a98e4d7c2ba24af">anonymous{XCoreLowerThreadLocal.cpp}::XCoreLowerThreadLocal::lowerGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a8d20a7c0aa0ef76c738e2ca9e21d35d5">OptimizeGlobalVars</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="#a095f8f031d99ce3c0b25478713293dea">setInitializer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a004b3a18ad13375ad40e88cd41a0fe97">shouldConvertToRelLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a6594a7d514d3847ccbe52b66a49d8ee5">tryToRecognizeTableBasedCttz</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a4f18aa17f81c88c8fa89c76563a6d510">tryWidenGlobalArraysUsedByMemcpy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95b7e7311ec52352ada27699c3c9c470">llvm::UpgradeGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a29d90faf3dd7128f83eca30377481bfe">llvm::ObjectSizeOffsetVisitor::visitGlobalVariable</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a2b81e19b3ddf7ec786c5105ba5470153">widenGlobalVariable</a>.</p>

</div>
</div>

### hasUniqueInitializer() {#ad9379319a0f19f0c42b5ee18d9f02373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalVariable::hasUniqueInitializer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>hasUniqueInitializer - Whether the global variable has an initializer, and any changes made to the initializer will turn up in the final executable.</p>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>References <a href="#a0f6dab3350ff78735031a6a62f344f18">isExternallyInitialized</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a904b8b68c7e4e888158b03f0eae0e4d5">llvm::GlobalValue::isStrongDefinitionForLinker</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#aac8ef9c8745bf77faa38eb1cd16fb4a7">findGlobalCtors</a>.</p>

</div>
</div>

### isConstant() {#aa859e108741fa64681b63f0c0c672512}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalVariable::isConstant ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the value is a global constant, its value is immutable throughout the runtime execution of the program.</p>


<p>Assigning a value into the constant leads to undefined behavior.</p>


<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#ab7c3af18d8706c2d91fd7e2f88424336">llvm::VNCoercion::analyzeLoadFromClobberingMemInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7414a7c636bc5a30b0e8478019a1bcd4">llvm::canTrackGlobalVariableInterprocedurally</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adc803f628b45e58e3de84b46dd0b7d83">CleanupPointerRootUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a88db5656a6723001ab395e9db68094c2">llvm::orc::cloneGlobalVariableDecl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36b03d4697c30b32e8762cb0dfd66761">llvm::getConstantDataArrayInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#aab3a49dcff02cbc78628deef02c53296">llvm::HexagonTargetObjectFile::isGlobalInSmallSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a1db077f1815950aa2f419be901c429c6">isGOTEquivalentCandidate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a9a6f055381f5a946e37ab4d9e4a221d8">llvm::AMDGPU::isLDSVariableToLower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/targetloweringobjectfile-cpp/#a9b9e767ff08744d8a078b672e57fb24f">isSuitableForBSS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#a6ebdfd799686fe407798a4d503a41cd9">isUnmergeableGlobal</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcorelowerthreadlocal-cpp-/xcorelowerthreadlocal/#adb1323a587666f6b6a98e4d7c2ba24af">anonymous{XCoreLowerThreadLocal.cpp}::XCoreLowerThreadLocal::lowerGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ad7593156486a0b9a2c48cfd1ab7b29a5">parseJumpTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3002d96da0f9030af718fbe2961b913f">llvm::ReadByteArrayFromGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmerge-cpp-/globalmergeimpl/#a9fbe2dcb11cb3bb78be4d97f388b0c5d">anonymous{GlobalMerge.cpp}::GlobalMergeImpl::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a004b3a18ad13375ad40e88cd41a0fe97">shouldConvertToRelLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3219f7b717320ae52f53ccb09ad5a84">llvm::tryPromoteCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a6594a7d514d3847ccbe52b66a49d8ee5">tryToRecognizeTableBasedCttz</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a4f18aa17f81c88c8fa89c76563a6d510">tryWidenGlobalArraysUsedByMemcpy</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a9a13dab9647bddbb0cce81565a8249a1">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::uniquifyGVPerKernel</a>.</p>

</div>
</div>

### isExternallyInitialized() {#a0f6dab3350ff78735031a6a62f344f18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalVariable::isExternallyInitialized ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>Referenced by <a href="#af9f31014b7b244d627f6bd18109c5987">GlobalVariable</a>, <a href="#af9ea64c7dae47dcfa2c9f5775fb5915d">GlobalVariable</a>, <a href="#aec2d700d8b1e57f830a673c39a1f30dc">hasDefinitiveInitializer</a>, <a href="#ad9379319a0f19f0c42b5ee18d9f02373">hasUniqueInitializer</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcorelowerthreadlocal-cpp-/xcorelowerthreadlocal/#adb1323a587666f6b6a98e4d7c2ba24af">anonymous{XCoreLowerThreadLocal.cpp}::XCoreLowerThreadLocal::lowerGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a>.</p>

</div>
</div>

### removeFromParent() {#a22e076c4cf000eba885dd00048641c6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalVariable::removeFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removeFromParent - This method unlinks 'this' from the containing module, but does not delete it.</p>

<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>, definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/module/#afb5360df1b24fc7637ea22a41193674e">llvm::Module::removeGlobalVariable</a>.</p>

</div>
</div>

### replaceInitializer() {#a36da270a9d55e053ba96b61f7f09a914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalVariable::replaceInitializer (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * InitVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>replaceInitializer - Sets the initializer for this global variable, and sets the value type of the global to the type of the initializer.</p>


<p>The initializer must not be null. This may affect the global's alignment if it isn't explicitly set.</p>


<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>, definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="#a095f8f031d99ce3c0b25478713293dea">setInitializer</a>.</p>

</div>
</div>

### setAttributes() {#a354e3a068c327a26d861d0d6851c90f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalVariable::setAttributes (<a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> A)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set attribute list for this global.</p>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>


<p>Referenced by <a href="#a53f47ebcc1a7ac4553ba2a2eeca596e5">copyAttributesFrom</a>.</p>

</div>
</div>

### setCodeModel() {#ac2b82881a2653d3ec234491e0c84ea71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalVariable::setCodeModel (<a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> CM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change the code model for this global.</p>

<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>, definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a339c8e24dbf600ae50b1aac2be2c1dbf">getCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aaf6a02ecb2b904406b783da5bfd6564e">llvm::GlobalValue::getGlobalValueSubClassData</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ab4e766c05dc79278ee675263c13c1cb0">llvm::GlobalValue::setGlobalValueSubClassData</a>.</p>


<p>Referenced by <a href="#a53f47ebcc1a7ac4553ba2a2eeca596e5">copyAttributesFrom</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aaf2ff3020b311fe77e208f80459017aa">llvm::setGlobalVariableLargeSection</a>.</p>

</div>
</div>

### setConstant() {#a40ae67d31da67ca17ed016839faf3390}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalVariable::setConstant (bool Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/loweremutls-cpp/#aeddd04f458fd6e9db5a892543636e240">addEmuTlsVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#abf4eceb96c86c97477d4bcf8eec661e5">EvaluateStaticConstructor</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a>.</p>

</div>
</div>

### setExternallyInitialized() {#adb67848f8b455ce9c5224a1f50b6c6e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalVariable::setExternallyInitialized (bool Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>


<p>Referenced by <a href="#a53f47ebcc1a7ac4553ba2a2eeca596e5">copyAttributesFrom</a>.</p>

</div>
</div>

### setInitializer() {#a095f8f031d99ce3c0b25478713293dea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalVariable::setInitializer (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * InitVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>setInitializer - Sets the initializer for this global variable, removing any existing initializer if InitVal==NULL.</p>


<p>The initializer must have the type <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">getValueType()</a>.</p>


<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>, definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a> and <a href="#a1c66d4eff947253e7610a66379974d63">hasInitializer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/loweremutls-cpp/#aeddd04f458fd6e9db5a892543636e240">addEmuTlsVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab371d6b308eb9772bdec63cf7a041407">llvm::CloneModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a1ca1f5b41c1408be83df43ab024cdd69">createRelLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#ab5c7f0f9f87d69820d8e4d8b31f4b0ff">ensurePromotedGV</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#afbf3f5773f08115de0ee332eae1ff187">DataScalarizerVisitor::findAndReplaceVectors</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilflattenarrays-cpp/#ab655865aaad374f00365011edc7440da">flattenGlobalArrays</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#adc155013f4c88522a318f0f19a29cbb2">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a8d20a7c0aa0ef76c738e2ca9e21d35d5">OptimizeGlobalVars</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="#a36da270a9d55e053ba96b61f7f09a914">replaceInitializer</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab02a4d4ecc962ea09ed6c79ebc699a54">updateAsyncFuncPointerContextSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### setGlobalVariableNumOperands() {#a209682ffdccb028dce7843c0bc639fe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalVariable::setGlobalVariableNumOperands (unsigned NumOps)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the number of operands on a <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a>.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> always allocates space for a single operands, but doesn't always use it.</p>


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Attrs {#ac88e1d3b61a6fa53a1f08d4f1846e81b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet llvm::GlobalVariable::Attrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>

</div>
</div>

### isConstantGlobal {#aaccefc19ade155690d250f5e9247e096}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalVariable::isConstantGlobal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>

</div>
</div>

### isExternallyInitializedConstant {#a9c21a6de0097c9986426ef37b54378f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalVariable::isExternallyInitializedConstant</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a8999cd0f7babf4c2b9158b16e2d1decb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalVariable::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### AllocMarker {#afb812898ea1801a6d25fbc63c7360b4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrusiveOperandsAllocMarker llvm::GlobalVariable::AllocMarker {1}</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>

</div>
</div>

### CodeModelBits {#ac00aa73e86debb93935ca11705437c3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::GlobalVariable::CodeModelBits = <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a456d28b8615245df4184bbeabdad0849a8b031f08caa89705d0671b902342ab09">LastCodeModelBit</a> - <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a456d28b8615245df4184bbeabdad0849a3506f6011beaf16702d54a98bb702c0c">LastAlignmentBit</a></td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>

</div>
</div>

### CodeModelMask {#ad3dd20ecaece728843cc2b3adf8a11dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::GlobalVariable::CodeModelMask = (1 &lt;&lt; CodeModelBits) - 1</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>

</div>
</div>

### CodeModelShift {#af6a34eff9dc39ff2c4a610c44b66ed32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::GlobalVariable::CodeModelShift = <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a456d28b8615245df4184bbeabdad0849a3506f6011beaf16702d54a98bb702c0c">LastAlignmentBit</a> + 1</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">GlobalVariable.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
