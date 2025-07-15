---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/inlineasm
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InlineAsm` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::InlineAsm { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">llvm/IR/InlineAsm.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> Representation. <a href="/web-llvm/docs/api/classes/llvm/value/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbd59a81e5e06598a94e8b0e3b216d99">ConstraintCodeVector</a> = std::vector&lt; std::string &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50ba5ef85decec05c8ea0fc180379eeb">SubConstraintInfoVector</a> = std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/inlineasm/subconstraintinfo">SubConstraintInfo</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6698ed8a3a2b1518a9bd8af9b026bfc2">ConstraintInfoVector</a> = std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/inlineasm/constraintinfo">ConstraintInfo</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AsmDialect { <a href="#a2c0e1ae3b31928af2e0a390bbc2ea9b8">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ConstraintPrefix { <a href="#a511f48809ad14f13e50b957a137a9d34">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : uint32_t { <a href="#af263df97504e0800bba5e552246b7370">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Kind : uint8_t { <a href="#a49585056d1d7051dd2bd6f012e5b5e94">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ConstraintCode : uint32_t { <a href="#af73223719f15f8ca95f36ce43aa9d6d0">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74b8883dc082dbeb076577e547621d36">InlineAsmKeyType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a916551e92fc8fc31148f6eb6e965ea02">ConstantUniqueMap&lt; InlineAsm &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae35813cadbd041edcfc43b8eb8097ec">InlineAsm</a> (const InlineAsm &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fae9c27c34fe2eabaaadf977c1055bc">InlineAsm</a> (FunctionType *Ty, const std::string &amp;AsmString, const std::string &amp;Constraints, bool hasSideEffects, bool isAlignStack, AsmDialect asmDialect, bool canThrow)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff1a6db682357ee9a0ee7f7d49da9f5b">operator=</a> (const InlineAsm &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaef3692d4ae1e74e3454e6337905930">hasSideEffects</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75cb5f07582633941b6b701c396f5c32">isAlignStack</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2c0e1ae3b31928af2e0a390bbc2ea9b8">AsmDialect</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a897e9f191ef8dc5dfb7f62225cc89904">getDialect</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc52a9074bd1b2bd07880eda4cb4811b">canThrow</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af135b4f1b9124a5a7497af5f39fc012a">getType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getType - <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a>'s are always pointers. <a href="#af135b4f1b9124a5a7497af5f39fc012a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa40ee2f082e2383c242624d8732b8ade">getFunctionType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFunctionType - <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a>'s are always pointers to functions. <a href="#aa40ee2f082e2383c242624d8732b8ade">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43dca86de94e08e39f00076224b26760">getAsmString</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cd4ad0429969d0c8fb0ba9485dfdd22">getConstraintString</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f6c06a6e0a4bb5192193116bded1308">collectAsmStrs</a> (SmallVectorImpl&lt; StringRef &gt; &amp;AsmStrs) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6698ed8a3a2b1518a9bd8af9b026bfc2">ConstraintInfoVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab675369ba0886613d29348cb04a1f1d7">ParseConstraints</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseConstraints - Parse the constraints of this inlineasm object, returning them the same way that ParseConstraints(str) does. <a href="#ab675369ba0886613d29348cb04a1f1d7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a240d44f57aee4fcf2c6f17de4dc1549f">destroyConstant</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When the <a href="/web-llvm/docs/api/classes/llvm/constantuniquemap">ConstantUniqueMap</a> merges two types and makes two InlineAsms identical, it destroys one of them with this method. <a href="#a240d44f57aee4fcf2c6f17de4dc1549f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa93281b0b0620fa5bf60d3cf51724eca">AsmString</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5d838764a540bdf59bfaf62e59abacd">Constraints</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaef01f0cfdb5aaa3a7ca068ee87583f">FTy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c396afcf0844d6b3dc230760522944f">HasSideEffects</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac76d1ac963f545d23bc6f04da5d24395">IsAlignStack</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2c0e1ae3b31928af2e0a390bbc2ea9b8">AsmDialect</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a402919923b12edb0f9f9787f03917b16">Dialect</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0618e7d3cbdb2a09deab4428580aa635">CanThrow</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44dec91bb943f56f8bba3e9171a76947">get</a> (FunctionType *Ty, StringRef AsmString, StringRef Constraints, bool hasSideEffects, bool isAlignStack=false, AsmDialect asmDialect=AD_ATT, bool canThrow=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a44dec91bb943f56f8bba3e9171a76947">InlineAsm::get</a> - Return the specified uniqued inline asm string. <a href="#a44dec91bb943f56f8bba3e9171a76947">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfcd3a2486f54c348da1859c41f6cc09">verify</a> (FunctionType *Ty, StringRef Constraints)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This static method can be used by the parser to check to see if the specified constraint string is legal for the type. <a href="#adfcd3a2486f54c348da1859c41f6cc09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a6698ed8a3a2b1518a9bd8af9b026bfc2">ConstraintInfoVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66b2f8cc39befa7a141f20ef9a74ed36">ParseConstraints</a> (StringRef ConstraintString)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseConstraints - Split up the constraint string into the specific constraints and their prefixes. <a href="#a66b2f8cc39befa7a141f20ef9a74ed36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaf51ba283866e0cc1400691f2956c49">classof</a> (const Value *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71b4b44c1ad06ba84d21d0be6c5c2276">getExtraInfoNames</a> (unsigned ExtraInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade110db5cd02d02d8d11534fa679b52b">getMemConstraintName</a> (ConstraintCode C)</td>
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


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ConstraintCodeVector {#adbd59a81e5e06598a94e8b0e3b216d99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InlineAsm::ConstraintCodeVector =  std::vector&lt;std::string&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### ConstraintInfoVector {#a6698ed8a3a2b1518a9bd8af9b026bfc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InlineAsm::ConstraintInfoVector =  std::vector&lt;ConstraintInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### SubConstraintInfoVector {#a50ba5ef85decec05c8ea0fc180379eeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InlineAsm::SubConstraintInfoVector =  std::vector&lt;SubConstraintInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#af263df97504e0800bba5e552246b7370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uint32_t</td>
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
<td class="doxyEnumItemName">Op_InputChain<a id="af263df97504e0800bba5e552246b7370a561c23f9fc6d8fe79f70cebf74937b30"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Op_AsmString<a id="af263df97504e0800bba5e552246b7370a697a92728413dc065842407e006b87fe"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Op_MDNode<a id="af263df97504e0800bba5e552246b7370aa7de3aedc6eaa004e9c6523f21fa4a53"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Op_ExtraInfo<a id="af263df97504e0800bba5e552246b7370a5c9183275c4ec573ab0f9ecc202ed26e"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Op_FirstOperand<a id="af263df97504e0800bba5e552246b7370afed51603ce2d64ec9af92ff0154913ca"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MIOp_AsmString<a id="af263df97504e0800bba5e552246b7370aae2aa90a74f555d8cc300b2b36403d1d"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MIOp_ExtraInfo<a id="af263df97504e0800bba5e552246b7370ab049673bbc307f5502c8aba23224a605"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MIOp_FirstOperand<a id="af263df97504e0800bba5e552246b7370ad8e4e0d44daebe8c07cf5d6d60a4fc30"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Extra_HasSideEffects<a id="af263df97504e0800bba5e552246b7370a68a61079919e61d3af1002124c2f1ff9"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Extra_IsAlignStack<a id="af263df97504e0800bba5e552246b7370ada6152484586a08fa711d4b0d44c87e5"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Extra_AsmDialect<a id="af263df97504e0800bba5e552246b7370abff974c258dde829c1c6b6f32667be3a"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Extra_MayLoad<a id="af263df97504e0800bba5e552246b7370aa21b27c3cc4550dcd3ff599dbe76d0c3"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Extra_MayStore<a id="af263df97504e0800bba5e552246b7370ab01e1dce8dabbbb3d14ed5f34c366008"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Extra_IsConvergent<a id="af263df97504e0800bba5e552246b7370a9921f5d5868939f49675e7fe34d1be70"></a></td>
<td class="doxyEnumItemDescription"> (= 32)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### AsmDialect {#a2c0e1ae3b31928af2e0a390bbc2ea9b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::InlineAsm::AsmDialect </td>
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
<td class="doxyEnumItemName">AD_ATT<a id="a2c0e1ae3b31928af2e0a390bbc2ea9b8ae46075a65afe271f3d7f91e1243aacca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AD_Intel<a id="a2c0e1ae3b31928af2e0a390bbc2ea9b8ac2322cfab42cb6c46aa198861244231e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### ConstraintCode {#af73223719f15f8ca95f36ce43aa9d6d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::InlineAsm::ConstraintCode : uint32_t</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Unknown<a id="af73223719f15f8ca95f36ce43aa9d6d0a88183b946cc5f0e8c96b2e66e1c74a7e"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">es<a id="af73223719f15f8ca95f36ce43aa9d6d0a12470fe406d44017d96eab37dd65fc14"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">i<a id="af73223719f15f8ca95f36ce43aa9d6d0a865c0c0b4ab0e063e5caa3387c1a8741"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k<a id="af73223719f15f8ca95f36ce43aa9d6d0a8ce4b16b22b58894aa86c421e8759df3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">m<a id="af73223719f15f8ca95f36ce43aa9d6d0a6f8f57715090da2632453988d9a1501b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">o<a id="af73223719f15f8ca95f36ce43aa9d6d0ad95679752134a2d9eb61dbd7b91c4bcc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v<a id="af73223719f15f8ca95f36ce43aa9d6d0a9e3669d19b675bd57058fd4664205d2a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">A<a id="af73223719f15f8ca95f36ce43aa9d6d0a7fc56270e7a70fa81a5935b72eacbe29"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Q<a id="af73223719f15f8ca95f36ce43aa9d6d0af09564c9ca56850d4cd6b3319e541aee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R<a id="af73223719f15f8ca95f36ce43aa9d6d0ae1e1d3d40573127e9ee0480caf1283d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S<a id="af73223719f15f8ca95f36ce43aa9d6d0a5dbc98dcc983a70728bd082d1a47546e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">T<a id="af73223719f15f8ca95f36ce43aa9d6d0ab9ece18c950afbfa6b0fdbfa4ff731d3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Um<a id="af73223719f15f8ca95f36ce43aa9d6d0a96bc320e4d72edda450c7a9abc8a214f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Un<a id="af73223719f15f8ca95f36ce43aa9d6d0a80a9a9f289a503c7e4218d1c34e05a02"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Uq<a id="af73223719f15f8ca95f36ce43aa9d6d0a278aaecf82149517409e1b5ad208d723"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Us<a id="af73223719f15f8ca95f36ce43aa9d6d0a85e8f233669adc62acf13417cb9649ca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ut<a id="af73223719f15f8ca95f36ce43aa9d6d0a51de5514f3c808babd19f42217fcba49"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Uv<a id="af73223719f15f8ca95f36ce43aa9d6d0a4efc6436bf7fb6078171376735b85588"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Uy<a id="af73223719f15f8ca95f36ce43aa9d6d0adac43929efc16c2681ae620d0602b299"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">X<a id="af73223719f15f8ca95f36ce43aa9d6d0a02129bb861061d1a052c592e2dc6b383"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Z<a id="af73223719f15f8ca95f36ce43aa9d6d0a21c2e59531c8710156d34a3c30ac81d5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZB<a id="af73223719f15f8ca95f36ce43aa9d6d0aa37ae7b0ac4edace48544f3f3c60f60a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZC<a id="af73223719f15f8ca95f36ce43aa9d6d0af341c2cd8bebc8a5b414a5121df2997f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Zy<a id="af73223719f15f8ca95f36ce43aa9d6d0ad94eb39b7c5996a928c1d97e2d336207"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">p<a id="af73223719f15f8ca95f36ce43aa9d6d0a83878c91171338902e0fe0fb97a8c47a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZQ<a id="af73223719f15f8ca95f36ce43aa9d6d0abb60ed902e221bef6558eb43f6ed3d64"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZR<a id="af73223719f15f8ca95f36ce43aa9d6d0a50390e75aac138ff69bd26a338e042a4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZS<a id="af73223719f15f8ca95f36ce43aa9d6d0a8a6b178d3af0a5a9b2744ca31921d5e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZT<a id="af73223719f15f8ca95f36ce43aa9d6d0a7b7cd24ea6f08b711cf4053beac43cc5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Max<a id="af73223719f15f8ca95f36ce43aa9d6d0a6a061313d22e51e0f25b7cd4dc065233"></a></td>
<td class="doxyEnumItemDescription"> (= ZT)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### ConstraintPrefix {#a511f48809ad14f13e50b957a137a9d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::InlineAsm::ConstraintPrefix </td>
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
<td class="doxyEnumItemName">isInput<a id="a511f48809ad14f13e50b957a137a9d34a79ca3881430605a6c7da5227cfb115d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">isOutput<a id="a511f48809ad14f13e50b957a137a9d34aabfa616f81b4833fdf462b07aabfa53f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">isClobber<a id="a511f48809ad14f13e50b957a137a9d34adf39e7f7e158f2ccacae6d4446197322"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">isLabel<a id="a511f48809ad14f13e50b957a137a9d34a2903cfed1fe44719f76b46abcac40955"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### Kind {#a49585056d1d7051dd2bd6f012e5b5e94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::InlineAsm::Kind : uint8_t</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">RegUse<a id="a49585056d1d7051dd2bd6f012e5b5e94a4ac13b7b2bba42947e897ffdf8797788"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegDef<a id="a49585056d1d7051dd2bd6f012e5b5e94a1fbd4693daf9a506101ec4cd36caa8dd"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegDefEarlyClobber<a id="a49585056d1d7051dd2bd6f012e5b5e94adda36cdb69635bdfb9f3d925753dc2d3"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Clobber<a id="a49585056d1d7051dd2bd6f012e5b5e94ac50132234eb8c934e71b7f2f0fa5099c"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Imm<a id="a49585056d1d7051dd2bd6f012e5b5e94ada9470e1aa5be1858e667318254dcb4b"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mem<a id="a49585056d1d7051dd2bd6f012e5b5e94adba5553473d129a7985fb532dc249ff4"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Func<a id="a49585056d1d7051dd2bd6f012e5b5e94a00d0b4f2d7dcdaaef835b97cf5d1e0df"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### ConstantUniqueMap&lt; InlineAsm &gt; {#a916551e92fc8fc31148f6eb6e965ea02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/constantuniquemap">ConstantUniqueMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="#abc52a9074bd1b2bd07880eda4cb4811b">canThrow</a>, <a href="#aaaef3692d4ae1e74e3454e6337905930">hasSideEffects</a>, <a href="#a74b8883dc082dbeb076577e547621d36">InlineAsmKeyType</a> and <a href="#a75cb5f07582633941b6b701c396f5c32">isAlignStack</a>.</p>

</div>
</div>

### InlineAsmKeyType {#a74b8883dc082dbeb076577e547621d36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/inlineasmkeytype">InlineAsmKeyType</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Referenced by <a href="#a916551e92fc8fc31148f6eb6e965ea02">ConstantUniqueMap&lt; InlineAsm &gt;</a> and <a href="#a44dec91bb943f56f8bba3e9171a76947">get</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InlineAsm() {#aae35813cadbd041edcfc43b8eb8097ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InlineAsm::InlineAsm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a> &amp;)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### InlineAsm() {#a4fae9c27c34fe2eabaaadf977c1055bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAsm::InlineAsm (<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; AsmString, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Constraints, bool hasSideEffects, bool isAlignStack, <a href="#a2c0e1ae3b31928af2e0a390bbc2ea9b8">AsmDialect</a> asmDialect, bool canThrow)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/inlineasm-cpp">InlineAsm.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#aff1a6db682357ee9a0ee7f7d49da9f5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAsm &amp; llvm::InlineAsm::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a> &amp;)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="#a2c0e1ae3b31928af2e0a390bbc2ea9b8ae46075a65afe271f3d7f91e1243aacca">AD_ATT</a>, <a href="#abc52a9074bd1b2bd07880eda4cb4811b">canThrow</a>, <a href="#aaaef3692d4ae1e74e3454e6337905930">hasSideEffects</a> and <a href="#a75cb5f07582633941b6b701c396f5c32">isAlignStack</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### canThrow() {#abc52a9074bd1b2bd07880eda4cb4811b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::canThrow ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Referenced by <a href="#a916551e92fc8fc31148f6eb6e965ea02">ConstantUniqueMap&lt; InlineAsm &gt;</a>, <a href="#a44dec91bb943f56f8bba3e9171a76947">get</a> and <a href="#aff1a6db682357ee9a0ee7f7d49da9f5b">operator=</a>.</p>

</div>
</div>

### collectAsmStrs() {#a2f6c06a6e0a4bb5192193116bded1308}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineAsm::collectAsmStrs (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; AsmStrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/inlineasm-cpp">InlineAsm.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>

</div>
</div>

### getAsmString() {#a43dca86de94e08e39f00076224b26760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::InlineAsm::getAsmString ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### getConstraintString() {#a0cd4ad0429969d0c8fb0ba9485dfdd22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::InlineAsm::getConstraintString ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### getDialect() {#a897e9f191ef8dc5dfb7f62225cc89904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmDialect llvm::InlineAsm::getDialect ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### getFunctionType() {#aa40ee2f082e2383c242624d8732b8ade}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType * InlineAsm::getFunctionType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getFunctionType - <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a>'s are always pointers to functions.</p>

<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/inlineasm-cpp">InlineAsm.cpp</a>.</p>

</div>
</div>

### getType() {#af135b4f1b9124a5a7497af5f39fc012a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType * llvm::InlineAsm::getType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getType - <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a>'s are always pointers.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>

</div>
</div>

### hasSideEffects() {#aaaef3692d4ae1e74e3454e6337905930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::hasSideEffects ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Referenced by <a href="#a916551e92fc8fc31148f6eb6e965ea02">ConstantUniqueMap&lt; InlineAsm &gt;</a>, <a href="#a44dec91bb943f56f8bba3e9171a76947">get</a> and <a href="#aff1a6db682357ee9a0ee7f7d49da9f5b">operator=</a>.</p>

</div>
</div>

### isAlignStack() {#a75cb5f07582633941b6b701c396f5c32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::isAlignStack ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Referenced by <a href="#a916551e92fc8fc31148f6eb6e965ea02">ConstantUniqueMap&lt; InlineAsm &gt;</a>, <a href="#a44dec91bb943f56f8bba3e9171a76947">get</a> and <a href="#aff1a6db682357ee9a0ee7f7d49da9f5b">operator=</a>.</p>

</div>
</div>

### ParseConstraints() {#ab675369ba0886613d29348cb04a1f1d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstraintInfoVector llvm::InlineAsm::ParseConstraints ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseConstraints - Parse the constraints of this inlineasm object, returning them the same way that ParseConstraints(str) does.</p>

<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Reference <a href="#ab675369ba0886613d29348cb04a1f1d7">ParseConstraints</a>.</p>


<p>Referenced by <a href="#ab675369ba0886613d29348cb04a1f1d7">ParseConstraints</a> and <a href="#adfcd3a2486f54c348da1859c41f6cc09">verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### destroyConstant() {#a240d44f57aee4fcf2c6f17de4dc1549f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineAsm::destroyConstant ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When the <a href="/web-llvm/docs/api/classes/llvm/constantuniquemap">ConstantUniqueMap</a> merges two types and makes two InlineAsms identical, it destroys one of them with this method.</p>

<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/inlineasm-cpp">InlineAsm.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AsmString {#aa93281b0b0620fa5bf60d3cf51724eca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::InlineAsm::AsmString</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### CanThrow {#a0618e7d3cbdb2a09deab4428580aa635}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::CanThrow</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### Constraints {#ad5d838764a540bdf59bfaf62e59abacd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::InlineAsm::Constraints</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### Dialect {#a402919923b12edb0f9f9787f03917b16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmDialect llvm::InlineAsm::Dialect</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### FTy {#adaef01f0cfdb5aaa3a7ca068ee87583f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* llvm::InlineAsm::FTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### HasSideEffects {#a3c396afcf0844d6b3dc230760522944f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::HasSideEffects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### IsAlignStack {#ac76d1ac963f545d23bc6f04da5d24395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::IsAlignStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#afaf51ba283866e0cc1400691f2956c49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#a18dbfcb332af7515599ee795cf462843">llvm::Value::Value</a>.</p>

</div>
</div>

### get() {#a44dec91bb943f56f8bba3e9171a76947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAsm * InlineAsm::get (<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> AsmString, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraints, bool hasSideEffects, bool isAlignStack=false, <a href="#a2c0e1ae3b31928af2e0a390bbc2ea9b8">AsmDialect</a> asmDialect=<a href="#a2c0e1ae3b31928af2e0a390bbc2ea9b8ae46075a65afe271f3d7f91e1243aacca">AD_ATT</a>, bool canThrow=false)</td>
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

<p><a href="#a44dec91bb943f56f8bba3e9171a76947">InlineAsm::get</a> - Return the specified uniqued inline asm string.</p>

<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/inlineasm-cpp">InlineAsm.cpp</a>.</p>


<p>References <a href="#abc52a9074bd1b2bd07880eda4cb4811b">canThrow</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="#aaaef3692d4ae1e74e3454e6337905930">hasSideEffects</a>, <a href="#a74b8883dc082dbeb076577e547621d36">InlineAsmKeyType</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#ac9a2da2321bac0d860e669057aa11d6d">llvm::LLVMContextImpl::InlineAsms</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="#a75cb5f07582633941b6b701c396f5c32">isAlignStack</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#aa22cef0c6abab1ef18f9e35efc2b537e">emitInlineAsm</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantexpressions/#gaa4f6920721724ad7a4d50144c64ec975">LLVMConstInlineAsm</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga4efd515d9e18a2bc89017e53a44142c2">LLVMGetInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a7d5502a6047fb27d6c33ea2820608c2c">anonymous{ValueMapper.cpp}::Mapper::mapValue</a> and <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#abc1dbfd3922f952c6e5edbed42521c54">anonymous{AddressSanitizer.cpp}::AddressSanitizer::maybeInsertDynamicShadowAtFunctionEntry</a>.</p>

</div>
</div>

### getExtraInfoNames() {#a71b4b44c1ad06ba84d21d0be6c5c2276}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; StringRef &gt; llvm::InlineAsm::getExtraInfoNames (unsigned ExtraInfo)</td>
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



<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="#a2c0e1ae3b31928af2e0a390bbc2ea9b8ae46075a65afe271f3d7f91e1243aacca">AD_ATT</a>, <a href="#a2c0e1ae3b31928af2e0a390bbc2ea9b8ac2322cfab42cb6c46aa198861244231e">AD_Intel</a>, <a href="#af263df97504e0800bba5e552246b7370abff974c258dde829c1c6b6f32667be3a">Extra_AsmDialect</a>, <a href="#af263df97504e0800bba5e552246b7370a68a61079919e61d3af1002124c2f1ff9">Extra_HasSideEffects</a>, <a href="#af263df97504e0800bba5e552246b7370ada6152484586a08fa711d4b0d44c87e5">Extra_IsAlignStack</a>, <a href="#af263df97504e0800bba5e552246b7370a9921f5d5868939f49675e7fe34d1be70">Extra_IsConvergent</a>, <a href="#af263df97504e0800bba5e552246b7370aa21b27c3cc4550dcd3ff599dbe76d0c3">Extra_MayLoad</a> and <a href="#af263df97504e0800bba5e552246b7370ab01e1dce8dabbbb3d14ed5f34c366008">Extra_MayStore</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aea7fb8b18a37883f51af73238e47dea4">llvm::TargetInstrInfo::createMIROperandComment</a>.</p>

</div>
</div>

### getMemConstraintName() {#ade110db5cd02d02d8d11534fa679b52b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::InlineAsm::getMemConstraintName (<a href="#af73223719f15f8ca95f36ce43aa9d6d0">ConstraintCode</a> C)</td>
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



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="#af73223719f15f8ca95f36ce43aa9d6d0a7fc56270e7a70fa81a5935b72eacbe29">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0a12470fe406d44017d96eab37dd65fc14">es</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0a865c0c0b4ab0e063e5caa3387c1a8741">i</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0a8ce4b16b22b58894aa86c421e8759df3">k</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0a6f8f57715090da2632453988d9a1501b">m</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0ad95679752134a2d9eb61dbd7b91c4bcc">o</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0a83878c91171338902e0fe0fb97a8c47a">p</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0af09564c9ca56850d4cd6b3319e541aee">Q</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0ae1e1d3d40573127e9ee0480caf1283d6">R</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0a5dbc98dcc983a70728bd082d1a47546e">S</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0ab9ece18c950afbfa6b0fdbfa4ff731d3">T</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0a96bc320e4d72edda450c7a9abc8a214f">Um</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0a80a9a9f289a503c7e4218d1c34e05a02">Un</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0a278aaecf82149517409e1b5ad208d723">Uq</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0a85e8f233669adc62acf13417cb9649ca">Us</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0a51de5514f3c808babd19f42217fcba49">Ut</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0a4efc6436bf7fb6078171376735b85588">Uv</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0adac43929efc16c2681ae620d0602b299">Uy</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0a9e3669d19b675bd57058fd4664205d2a">v</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0a02129bb861061d1a052c592e2dc6b383">X</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0a21c2e59531c8710156d34a3c30ac81d5">Z</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0aa37ae7b0ac4edace48544f3f3c60f60a">ZB</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0af341c2cd8bebc8a5b414a5121df2997f">ZC</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0abb60ed902e221bef6558eb43f6ed3d64">ZQ</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0a50390e75aac138ff69bd26a338e042a4">ZR</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0a8a6b178d3af0a5a9b2744ca31921d5e2">ZS</a>, <a href="#af73223719f15f8ca95f36ce43aa9d6d0a7b7cd24ea6f08b711cf4053beac43cc5">ZT</a> and <a href="#af73223719f15f8ca95f36ce43aa9d6d0ad94eb39b7c5996a928c1d97e2d336207">Zy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aea7fb8b18a37883f51af73238e47dea4">llvm::TargetInstrInfo::createMIROperandComment</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a48e904486c2be7b98450bc2306c10648">llvm::MachineInstr::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a6182598aaa3c33b0c1e4eb1f7b1ce870">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectInlineAsmMemoryOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a5c6e604c1448af21dd7165a086728b31">llvm::RISCVDAGToDAGISel::SelectInlineAsmMemoryOperand</a>.</p>

</div>
</div>

### ParseConstraints() {#a66b2f8cc39befa7a141f20ef9a74ed36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAsm::ConstraintInfoVector InlineAsm::ParseConstraints (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ConstraintString)</td>
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

<p>ParseConstraints - Split up the constraint string into the specific constraints and their prefixes.</p>


<p>If this returns an empty vector, and if the constraint string itself isn't empty, there was an error parsing.</p>


<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>, definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/inlineasm-cpp">InlineAsm.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### verify() {#adfcd3a2486f54c348da1859c41f6cc09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error InlineAsm::verify (<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraints)</td>
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

<p>This static method can be used by the parser to check to see if the specified constraint string is legal for the type.</p>

<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/inlineasm-cpp">InlineAsm.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a858efd7b61654c0de28c56f9adafa13d">llvm::StructType::getNumElements</a>, <a href="#a511f48809ad14f13e50b957a137a9d34adf39e7f7e158f2ccacae6d4446197322">isClobber</a>, <a href="#a511f48809ad14f13e50b957a137a9d34a79ca3881430605a6c7da5227cfb115d6">isInput</a>, <a href="#a511f48809ad14f13e50b957a137a9d34a2903cfed1fe44719f76b46abcac40955">isLabel</a>, <a href="#a511f48809ad14f13e50b957a137a9d34aabfa616f81b4833fdf462b07aabfa53f">isOutput</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/inlineasm-cpp/#a8e411a1d43f11899e8431f4107a89a7c">makeStringError</a>, <a href="#ab675369ba0886613d29348cb04a1f1d7">ParseConstraints</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/inlineasm-cpp">InlineAsm.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
