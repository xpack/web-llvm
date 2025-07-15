---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/type
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Type` Class Reference

<p>Just like <a href="/web-llvm/docs/api/classes/llvm/type">llvm::Type</a> these are immutable, unique, never get freed and can only be created via static factory methods. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::Type { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">llvm/SandboxIR/Type.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/arraytype">ArrayType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/functiontype">FunctionType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/integertype">IntegerType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to represent integer types. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/integertype/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/pointertype">PointerType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/structtype">StructType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype">VectorType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b575cff986b79d3497acba31e17655f">ArrayType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4d805ae7a1735765e14164b42b58cce">StructType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86bc4b915455f6961b9259ac614979f3">VectorType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8192a78541a91d734e9b974db08fda13">FixedVectorType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad91b1a4667c4207780fb5113ec6a0f9e">ScalableVectorType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb7721cfea46ef9d51188ae7df27cf17">PointerType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a32325cb875edb50b0e3a9aed24eb8b">FunctionType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa06efd1401ee152456eb22a467ddcb3">IntegerType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7194606aa12931e96f8f5448d418ed0">Function</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab98413af141c094f142c9dc597e88e4a">CallBase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3e5c6852681eae8e125a0db092e2e56">ConstantInt</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab25d2664c586d20df4d7a31d62f305b9">ConstantArray</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1696f5f9994bd1a179b4c2869d5d90ea">ConstantStruct</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d3f8660ca9292cbfc0256bb0188831a">ConstantVector</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a491288b9b4b16c83d513619f00fdcc6c">CmpInst</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc0f7da619e9e72510dc07ed7b5ff6d8">Utils</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48d3e47b0874a21308343f13b99ce71b">TargetExtType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21f639900c480510650969df9c74d17d">Module</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a203bf21939cd93b6539ca11553a18e8c">FPMathOperator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a386a56204d7dd7077ca711aff3c78d55">Type</a> (llvm::Type *LLVMTy, Context &amp;Ctx)</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a576a50ad3bfb28b8728f9263d86f0c56">~Type</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c4661418be55867a719a892bcec6171">print</a> (raw_ostream &amp;OS, bool IsForDebug=false, bool NoDetails=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the current type. <a href="#a5c4661418be55867a719a892bcec6171">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae662f556252fe75768094c7976518409">getContext</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6689b781b94b74e8b0b4903549fba87">isVoidTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is 'void'. <a href="#aa6689b781b94b74e8b0b4903549fba87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a653a09808a25c643bc85d6d801fc4b85">isHalfTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is 'half', a 16-bit IEEE fp type. <a href="#a653a09808a25c643bc85d6d801fc4b85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc69ff00f4dfce704386021f1195479a">isBFloatTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is 'bfloat', a 16-bit bfloat type. <a href="#afc69ff00f4dfce704386021f1195479a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75d0e9a1a8201baaa6705183195a24c3">is16bitFPTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a 16-bit float type. <a href="#a75d0e9a1a8201baaa6705183195a24c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1c1750c77a2aabe0f1bc43dad228938">isFloatTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is 'float', a 32-bit IEEE fp type. <a href="#ad1c1750c77a2aabe0f1bc43dad228938">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6633d096ce9fcaef9ec30c092ebbb63a">isDoubleTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is 'double', a 64-bit IEEE fp type. <a href="#a6633d096ce9fcaef9ec30c092ebbb63a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0122c81207adb71b9a84569afc7ad426">isX86_FP80Ty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is x86 long double. <a href="#a0122c81207adb71b9a84569afc7ad426">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a072fdcb6e855e1cafe35b401e5fb9e3c">isFP128Ty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is 'fp128'. <a href="#a072fdcb6e855e1cafe35b401e5fb9e3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eee2e276e155df99ab6465aff7e630f">isPPC_FP128Ty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is powerpc long double. <a href="#a8eee2e276e155df99ab6465aff7e630f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35588fbd7a709079413e1271cf557900">isIEEELikeFPTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a well-behaved IEEE-like type, which has a IEEE compatible layout as defined by <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af3bec23b6e372e677f17151bfd6af8fc">APFloat::isIEEE()</a>, and does not have non-IEEE values, such as x86_fp80's unnormal values. <a href="#a35588fbd7a709079413e1271cf557900">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a403d5aae9bd503730c3f24d9bd4f9d75">isFloatingPointTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is one of the floating-point types. <a href="#a403d5aae9bd503730c3f24d9bd4f9d75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8c3b8e29862ce750e9854578897f82e">isMultiUnitFPType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is a floating-point type that is an unevaluated sum of multiple floating-point units. <a href="#ab8c3b8e29862ce750e9854578897f82e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d80d64662239762d1571a3f30777110">getFltSemantics</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a657aea40682a55aeafe24659722d04db">isX86_AMXTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> AMX. <a href="#a657aea40682a55aeafe24659722d04db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a309006f37f3e1e2f0bf5f3dae40c81da">isTargetExtTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a target extension type. <a href="#a309006f37f3e1e2f0bf5f3dae40c81da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5e193143003276b3ff4f39efce27d34">isScalableTargetExtTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a target extension type with a scalable layout. <a href="#ab5e193143003276b3ff4f39efce27d34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04edb84fd1719b346874cfcc1caa268d">isScalableTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a type whose size is a known multiple of vscale. <a href="#a04edb84fd1719b346874cfcc1caa268d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a609b0218dcee7182f7da35c0269a089e">isFPOrFPVectorTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a FP type or a vector of FP. <a href="#a609b0218dcee7182f7da35c0269a089e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af383ba86b4ec0b76a0fc29c1e1fef520">isLabelTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is 'label'. <a href="#af383ba86b4ec0b76a0fc29c1e1fef520">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a75855ad2835b678df69c6b509f4895">isMetadataTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is 'metadata'. <a href="#a4a75855ad2835b678df69c6b509f4895">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa389f559f75d77d81e248787c811bccc">isTokenTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is 'token'. <a href="#aa389f559f75d77d81e248787c811bccc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bacc4d6d9314aee7630737b69fd0e6a">isIntegerTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/integertype">IntegerType</a>. <a href="#a5bacc4d6d9314aee7630737b69fd0e6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2ce7b7a68080f1d444cf19dc664064d">isIntegerTy</a> (unsigned Bitwidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is an <a href="/web-llvm/docs/api/classes/llvm/sandboxir/integertype">IntegerType</a> of the given width. <a href="#ad2ce7b7a68080f1d444cf19dc664064d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6016210f4eaf48db86de4f8a68e18992">isIntOrIntVectorTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is an integer type or a vector of integer types. <a href="#a6016210f4eaf48db86de4f8a68e18992">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affc0db115d57236915c758662cdc0e1d">isIntOrIntVectorTy</a> (unsigned BitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is an integer type or a vector of integer types of the given width. <a href="#affc0db115d57236915c758662cdc0e1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a273ddd8779c0b685831ecb9b00460c23">isIntOrPtrTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is an integer type or a pointer type. <a href="#a273ddd8779c0b685831ecb9b00460c23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0e36f09a9b993ef77dc9da5a3fdc669">isFunctionTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/functiontype">FunctionType</a>. <a href="#ab0e36f09a9b993ef77dc9da5a3fdc669">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6550d037ba2597eaf235932babc42cbc">isStructTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/structtype">StructType</a>. <a href="#a6550d037ba2597eaf235932babc42cbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dc0b8a87c047869511efe7f003cff5a">isArrayTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/arraytype">ArrayType</a>. <a href="#a8dc0b8a87c047869511efe7f003cff5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac031dfe19eddd49a7900e0c2288406c3">isPointerTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pointertype">PointerType</a>. <a href="#ac031dfe19eddd49a7900e0c2288406c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83fd7127228e04b69f4f1b95cc7fd0e2">isPtrOrPtrVectorTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a pointer type or a vector of pointer types. <a href="#a83fd7127228e04b69f4f1b95cc7fd0e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab72c549a3c63bf2f0093dc66b8a50e49">isVectorTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype">VectorType</a>. <a href="#ab72c549a3c63bf2f0093dc66b8a50e49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4421a693ebc6dcc93bb68b55fa4e8aeb">canLosslesslyBitCastTo</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this type could be converted with a lossless BitCast to type 'Ty'. <a href="#a4421a693ebc6dcc93bb68b55fa4e8aeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba7ad0f0c5541959cd15d2a8212d2805">isEmptyTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this type is empty, that is, it has no elements or all of its elements are empty. <a href="#aba7ad0f0c5541959cd15d2a8212d2805">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4ceea699daf16bb734ca70ed432da32">isFirstClassType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the type is "first class", meaning it is a valid type for a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a>. <a href="#ad4ceea699daf16bb734ca70ed432da32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92e96f4687959015000cacde3ef7fdc7">isSingleValueType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the type is a valid type for a register in codegen. <a href="#a92e96f4687959015000cacde3ef7fdc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad355244dc96e76a4dc72608668c02999">isAggregateType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the type is an aggregate type. <a href="#ad355244dc96e76a4dc72608668c02999">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75e560adcff5992e25a089e2a26c5959">isSized</a> (SmallPtrSetImpl&lt; Type * &gt; *Visited=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it makes sense to take the size of this type. <a href="#a75e560adcff5992e25a089e2a26c5959">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a595135fd17d77e8ed5e48a8033e5fa24">getPrimitiveSizeInBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the basic size of this type if it is a primitive type. <a href="#a595135fd17d77e8ed5e48a8033e5fa24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70633ba5047b4c5c7ce8a4db3b32bc86">getScalarSizeInBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a vector type, return the getPrimitiveSizeInBits value for the element type. <a href="#a70633ba5047b4c5c7ce8a4db3b32bc86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad74baa920a4b77b6d30407bf65c8cd2">getFPMantissaWidth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the width of the mantissa of this type. <a href="#aad74baa920a4b77b6d30407bf65c8cd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d234208b218b7ce24f588d074ba19e6">isIEEE</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the type is IEEE compatible, as defined by the eponymous method in <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a>. <a href="#a1d234208b218b7ce24f588d074ba19e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abecc000cb4767b88afe6f189716ae698">getScalarType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a vector type, return the element type, otherwise return 'this'. <a href="#abecc000cb4767b88afe6f189716ae698">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a636cb45b78340dd800a37d42120f52cc">getPointerAddressSpace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the address space of this pointer or pointer vector type. <a href="#a636cb45b78340dd800a37d42120f52cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab65fd199fac3312ff9d0426dbae8cba8">dumpOS</a> (raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a975aa15f5744af5a899e491135ab1384">dump</a> ()</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">llvm::Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae616c2dab17f3dc139020928ef67ecaa">Ctx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3741ff4c00516153fc0d9285a1e4c9e">getInt64Ty</a> (Context &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ba4ed00f8805b525fb7b4497a527876">getInt32Ty</a> (Context &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ef9c2652adaeee5bf72525dbd10677">getInt16Ty</a> (Context &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53974d47ba590e4418c5952730fd9559">getInt8Ty</a> (Context &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75eedc5667cb22e709e89fef21c08ee5">getInt1Ty</a> (Context &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57e9061fb6d18ee131661f3c68a66eb2">getDoubleTy</a> (Context &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4125c0ca2f91c4d506cfabc64fa4b20">getFloatTy</a> (Context &amp;Ctx)</td>
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

<p>Just like <a href="/web-llvm/docs/api/classes/llvm/type">llvm::Type</a> these are immutable, unique, never get freed and can only be created via static factory methods.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<div class="doxySectionDef">

## Friends

### ArrayType {#a5b575cff986b79d3497acba31e17655f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/arraytype">ArrayType</a></td>
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


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a5b575cff986b79d3497acba31e17655f">ArrayType</a>.</p>


<p>Referenced by <a href="#a5b575cff986b79d3497acba31e17655f">ArrayType</a>.</p>

</div>
</div>

### CallBase {#ab98413af141c094f142c9dc597e88e4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase">CallBase</a></td>
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


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#ab98413af141c094f142c9dc597e88e4a">CallBase</a>.</p>


<p>Referenced by <a href="#ab98413af141c094f142c9dc597e88e4a">CallBase</a>.</p>

</div>
</div>

### CmpInst {#a491288b9b4b16c83d513619f00fdcc6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst">CmpInst</a></td>
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


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a491288b9b4b16c83d513619f00fdcc6c">CmpInst</a>.</p>


<p>Referenced by <a href="#a491288b9b4b16c83d513619f00fdcc6c">CmpInst</a>.</p>

</div>
</div>

### ConstantArray {#ab25d2664c586d20df4d7a31d62f305b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantarray">ConstantArray</a></td>
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


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#ab25d2664c586d20df4d7a31d62f305b9">ConstantArray</a>.</p>


<p>Referenced by <a href="#ab25d2664c586d20df4d7a31d62f305b9">ConstantArray</a>.</p>

</div>
</div>

### ConstantInt {#ae3e5c6852681eae8e125a0db092e2e56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint">ConstantInt</a></td>
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


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#ae3e5c6852681eae8e125a0db092e2e56">ConstantInt</a>.</p>


<p>Referenced by <a href="#ae3e5c6852681eae8e125a0db092e2e56">ConstantInt</a>.</p>

</div>
</div>

### ConstantStruct {#a1696f5f9994bd1a179b4c2869d5d90ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantstruct">ConstantStruct</a></td>
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


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a1696f5f9994bd1a179b4c2869d5d90ea">ConstantStruct</a>.</p>


<p>Referenced by <a href="#a1696f5f9994bd1a179b4c2869d5d90ea">ConstantStruct</a>.</p>

</div>
</div>

### ConstantVector {#a1d3f8660ca9292cbfc0256bb0188831a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantvector">ConstantVector</a></td>
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


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a1d3f8660ca9292cbfc0256bb0188831a">ConstantVector</a>.</p>


<p>Referenced by <a href="#a1d3f8660ca9292cbfc0256bb0188831a">ConstantVector</a>.</p>

</div>
</div>

### Context {#ac26c806e60ca4a0547680edb68f6e39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a></td>
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


<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>.</p>


<p>Referenced by <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/integertype/#aae152feb9968318d68127c6c8c72dd73">llvm::sandboxir::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pointertype/#a6339a17772e61656c08fd77a488c9a50">llvm::sandboxir::PointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/structtype/#acdd011895dc673bd8b8edd5b8eaf871c">llvm::sandboxir::StructType::get</a>, <a href="#ae662f556252fe75768094c7976518409">getContext</a>, <a href="#a57e9061fb6d18ee131661f3c68a66eb2">getDoubleTy</a>, <a href="#af4125c0ca2f91c4d506cfabc64fa4b20">getFloatTy</a>, <a href="#af9ef9c2652adaeee5bf72525dbd10677">getInt16Ty</a>, <a href="#a75eedc5667cb22e709e89fef21c08ee5">getInt1Ty</a>, <a href="#a8ba4ed00f8805b525fb7b4497a527876">getInt32Ty</a>, <a href="#aa3741ff4c00516153fc0d9285a1e4c9e">getInt64Ty</a>, <a href="#a53974d47ba590e4418c5952730fd9559">getInt8Ty</a>, <a href="#abecc000cb4767b88afe6f189716ae698">getScalarType</a> and <a href="#a386a56204d7dd7077ca711aff3c78d55">Type</a>.</p>

</div>
</div>

### FixedVectorType {#a8192a78541a91d734e9b974db08fda13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fixedvectortype">FixedVectorType</a></td>
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


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a8192a78541a91d734e9b974db08fda13">FixedVectorType</a>.</p>


<p>Referenced by <a href="#a8192a78541a91d734e9b974db08fda13">FixedVectorType</a>.</p>

</div>
</div>

### FPMathOperator {#a203bf21939cd93b6539ca11553a18e8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fpmathoperator">FPMathOperator</a></td>
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


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a203bf21939cd93b6539ca11553a18e8c">FPMathOperator</a>.</p>


<p>Referenced by <a href="#a203bf21939cd93b6539ca11553a18e8c">FPMathOperator</a>.</p>

</div>
</div>

### Function {#ab7194606aa12931e96f8f5448d418ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function">Function</a></td>
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


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#ab7194606aa12931e96f8f5448d418ed0">Function</a>.</p>


<p>Referenced by <a href="#ab7194606aa12931e96f8f5448d418ed0">Function</a>.</p>

</div>
</div>

### FunctionType {#a8a32325cb875edb50b0e3a9aed24eb8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/functiontype">FunctionType</a></td>
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


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a8a32325cb875edb50b0e3a9aed24eb8b">FunctionType</a>.</p>


<p>Referenced by <a href="#a8a32325cb875edb50b0e3a9aed24eb8b">FunctionType</a>.</p>

</div>
</div>

### IntegerType {#aaa06efd1401ee152456eb22a467ddcb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/integertype">IntegerType</a></td>
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


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#aaa06efd1401ee152456eb22a467ddcb3">IntegerType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/integertype/#aae152feb9968318d68127c6c8c72dd73">llvm::sandboxir::IntegerType::get</a> and <a href="#aaa06efd1401ee152456eb22a467ddcb3">IntegerType</a>.</p>

</div>
</div>

### Module {#a21f639900c480510650969df9c74d17d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/module">Module</a></td>
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


<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a21f639900c480510650969df9c74d17d">Module</a>.</p>


<p>Referenced by <a href="#a21f639900c480510650969df9c74d17d">Module</a>.</p>

</div>
</div>

### PointerType {#abb7721cfea46ef9d51188ae7df27cf17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pointertype">PointerType</a></td>
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


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#abb7721cfea46ef9d51188ae7df27cf17">PointerType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pointertype/#a6339a17772e61656c08fd77a488c9a50">llvm::sandboxir::PointerType::get</a> and <a href="#abb7721cfea46ef9d51188ae7df27cf17">PointerType</a>.</p>

</div>
</div>

### ScalableVectorType {#ad91b1a4667c4207780fb5113ec6a0f9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/scalablevectortype">ScalableVectorType</a></td>
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


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#ad91b1a4667c4207780fb5113ec6a0f9e">ScalableVectorType</a>.</p>


<p>Referenced by <a href="#ad91b1a4667c4207780fb5113ec6a0f9e">ScalableVectorType</a>.</p>

</div>
</div>

### StructType {#ae4d805ae7a1735765e14164b42b58cce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/structtype">StructType</a></td>
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


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#ae4d805ae7a1735765e14164b42b58cce">StructType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/structtype/#acdd011895dc673bd8b8edd5b8eaf871c">llvm::sandboxir::StructType::get</a> and <a href="#ae4d805ae7a1735765e14164b42b58cce">StructType</a>.</p>

</div>
</div>

### TargetExtType {#a48d3e47b0874a21308343f13b99ce71b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/targetexttype">TargetExtType</a></td>
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


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a48d3e47b0874a21308343f13b99ce71b">TargetExtType</a>.</p>


<p>Referenced by <a href="#a48d3e47b0874a21308343f13b99ce71b">TargetExtType</a>.</p>

</div>
</div>

### Utils {#abc0f7da619e9e72510dc07ed7b5ff6d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/utils">Utils</a></td>
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


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#abc0f7da619e9e72510dc07ed7b5ff6d8">Utils</a>.</p>


<p>Referenced by <a href="#abc0f7da619e9e72510dc07ed7b5ff6d8">Utils</a>.</p>

</div>
</div>

### VectorType {#a86bc4b915455f6961b9259ac614979f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype">VectorType</a></td>
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


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a86bc4b915455f6961b9259ac614979f3">VectorType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a2bc7770aadd2793e71a149611e84b0b7">llvm::sandboxir::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a417f5824a665662b7c3ca5439d257b4d">llvm::sandboxir::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a992f8e70b5847690ae8ddb8adadc3037">llvm::sandboxir::VectorType::getDoubleElementsVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#ac96d755c768edd2cde7743330bbb6f5a">llvm::sandboxir::VectorType::getExtendedElementVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a9cd3c5065659bc840e36b5a96ec94d96">llvm::sandboxir::VectorType::getHalfElementsVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a78f34fdeeb7b2cc30adc895344d8df0f">llvm::sandboxir::VectorType::getInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a2b3fb17faf3c8e599183efe5cbeb41ce">llvm::sandboxir::VectorType::getSubdividedVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a950c035ff5222db07c7cc70a8d755e40">llvm::sandboxir::VectorType::getTruncatedElementVectorType</a> and <a href="#a86bc4b915455f6961b9259ac614979f3">VectorType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### Type() {#a386a56204d7dd7077ca711aff3c78d55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::Type::Type (<a href="/web-llvm/docs/api/classes/llvm/type">llvm::Type</a> * LLVMTy, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>References <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>, <a href="#ae616c2dab17f3dc139020928ef67ecaa">Ctx</a> and <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>


<p>Referenced by <a href="#a4421a693ebc6dcc93bb68b55fa4e8aeb">canLosslesslyBitCastTo</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/arraytype/#a3c013658646965dc531bf1bf68dc16ed">llvm::sandboxir::ArrayType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/functiontype/#a3afb28a7d344f4ae6c9ba13aef574862">llvm::sandboxir::FunctionType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/integertype/#a4a31a0075a81802a6819af6a75a64ca8">llvm::sandboxir::IntegerType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pointertype/#a1216d52d8d739088660964729affd967">llvm::sandboxir::PointerType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/structtype/#a7ffdded9dd28d8eb8b8563b295393de4">llvm::sandboxir::StructType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a37e3aa4bccef49d6abd3a6ecf5c2ba75">llvm::sandboxir::VectorType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a2bc7770aadd2793e71a149611e84b0b7">llvm::sandboxir::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a417f5824a665662b7c3ca5439d257b4d">llvm::sandboxir::VectorType::get</a>, <a href="#a57e9061fb6d18ee131661f3c68a66eb2">getDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#ae3f468d365ecf76cd72b905bbaaa30c8">llvm::sandboxir::VectorType::getElementType</a>, <a href="#af4125c0ca2f91c4d506cfabc64fa4b20">getFloatTy</a>, <a href="#af9ef9c2652adaeee5bf72525dbd10677">getInt16Ty</a>, <a href="#a75eedc5667cb22e709e89fef21c08ee5">getInt1Ty</a>, <a href="#a8ba4ed00f8805b525fb7b4497a527876">getInt32Ty</a>, <a href="#aa3741ff4c00516153fc0d9285a1e4c9e">getInt64Ty</a>, <a href="#a53974d47ba590e4418c5952730fd9559">getInt8Ty</a>, <a href="#abecc000cb4767b88afe6f189716ae698">getScalarType</a> and <a href="#a75e560adcff5992e25a089e2a26c5959">isSized</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~Type() {#a576a50ad3bfb28b8728f9263d86f0c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::Type::~Type ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### canLosslesslyBitCastTo() {#a4421a693ebc6dcc93bb68b55fa4e8aeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::canLosslesslyBitCastTo (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> * Ty)</td>
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

<p>Return true if this type could be converted with a lossless BitCast to type 'Ty'.</p>


<p>For example, i8* to i32*. BitCasts are valid for types of the same size only where no re-interpretation of the bits is done. Determine if this type could be losslessly bitcast to Ty</p>


<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>References <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a> and <a href="#a386a56204d7dd7077ca711aff3c78d55">Type</a>.</p>

</div>
</div>

### dump() {#a975aa15f5744af5a899e491135ab1384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Type::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#aaf8e099af367077208606316ecceb9db">llvm::sandboxir::dumpOS</a>.</p>

</div>
</div>

### dumpOS() {#ab65fd199fac3312ff9d0426dbae8cba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Type::dumpOS (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>References <a href="#ab65fd199fac3312ff9d0426dbae8cba8">dumpOS</a> and <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>


<p>Referenced by <a href="#ab65fd199fac3312ff9d0426dbae8cba8">dumpOS</a>.</p>

</div>
</div>

### getContext() {#ae662f556252fe75768094c7976518409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Context &amp; llvm::sandboxir::Type::getContext ()</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>References <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a> and <a href="#ae616c2dab17f3dc139020928ef67ecaa">Ctx</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/type/#a2f0388b8315300b55a8833caf090ef71">llvm::Type::containsNonLocalTargetExtType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a6224f807d740562c873c036926d0dfd9">llvm::sandboxir::ShuffleVectorInst::convertShuffleMaskForBitcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#ac96d755c768edd2cde7743330bbb6f5a">llvm::sandboxir::VectorType::getExtendedElementVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a9cd3c5065659bc840e36b5a96ec94d96">llvm::sandboxir::VectorType::getHalfElementsVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractvalueinst/#a4e6ed8a1c14cfbc9d22aa336c96e4e0b">llvm::sandboxir::ExtractValueInst::getIndexedType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a78f34fdeeb7b2cc30adc895344d8df0f">llvm::sandboxir::VectorType::getInteger</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#a7b33bd9843f6f96a4f390a9314692657">llvm::sandboxir::CmpInst::makeCmpResultType</a>.</p>

</div>
</div>

### getFltSemantics() {#a1d80d64662239762d1571a3f30777110}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::sandboxir::Type::getFltSemantics ()</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### getFPMantissaWidth() {#aad74baa920a4b77b6d30407bf65c8cd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::sandboxir::Type::getFPMantissaWidth ()</td>
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

<p>Return the width of the mantissa of this type.</p>


<p>This is only valid on floating-point types. If the FP type does not have a stable mantissa (e.g. ppc long double), this method returns -1.</p>


<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### getPointerAddressSpace() {#a636cb45b78340dd800a37d42120f52cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::Type::getPointerAddressSpace ()</td>
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

<p>Get the address space of this pointer or pointer vector type.</p>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/addrspacecastinst/#a774a0a887b03ce2aa37b5409105ebf6f">llvm::sandboxir::AddrSpaceCastInst::getDestAddressSpace</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/addrspacecastinst/#a088eb1bfed8c280333c53c97e981b4e0">llvm::sandboxir::AddrSpaceCastInst::getSrcAddressSpace</a>.</p>

</div>
</div>

### getPrimitiveSizeInBits() {#a595135fd17d77e8ed5e48a8033e5fa24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize llvm::sandboxir::Type::getPrimitiveSizeInBits ()</td>
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

<p>Return the basic size of this type if it is a primitive type.</p>


<p>These are fixed by LLVM and are not target-dependent. This will return zero if the type does not have a size or is not a primitive type.</p>


<p>If this is a scalable vector type, the scalable property will be set and the runtime size will be a positive integer multiple of the base size.</p>


<p>Note that this may not reflect the size of memory allocated for an instance of the type or the number of bytes that are written when an instance of the type is stored to memory. The <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> class provides additional query functions to provide this information.</p>


<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### getScalarSizeInBits() {#a70633ba5047b4c5c7ce8a4db3b32bc86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::Type::getScalarSizeInBits ()</td>
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

<p>If this is a vector type, return the getPrimitiveSizeInBits value for the element type.</p>


<p>Otherwise return the getPrimitiveSizeInBits value for this type.</p>


<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### getScalarType() {#abecc000cb4767b88afe6f189716ae698}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::sandboxir::Type::getScalarType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is a vector type, return the element type, otherwise return 'this'.</p>

<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>References <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>, <a href="#ae616c2dab17f3dc139020928ef67ecaa">Ctx</a> and <a href="#a386a56204d7dd7077ca711aff3c78d55">Type</a>.</p>

</div>
</div>

### is16bitFPTy() {#a75d0e9a1a8201baaa6705183195a24c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::is16bitFPTy ()</td>
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

<p>Return true if this is a 16-bit float type.</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isAggregateType() {#ad355244dc96e76a4dc72608668c02999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isAggregateType ()</td>
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

<p>Return true if the type is an aggregate type.</p>


<p>This means it is valid as the first operand of an insertvalue or extractvalue instruction. This includes struct and array types, but does not include vector types.</p>


<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isArrayTy() {#a8dc0b8a87c047869511efe7f003cff5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isArrayTy ()</td>
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

<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/arraytype">ArrayType</a>.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isBFloatTy() {#afc69ff00f4dfce704386021f1195479a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isBFloatTy ()</td>
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

<p>Return true if this is 'bfloat', a 16-bit bfloat type.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isDoubleTy() {#a6633d096ce9fcaef9ec30c092ebbb63a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isDoubleTy ()</td>
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

<p>Return true if this is 'double', a 64-bit IEEE fp type.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isEmptyTy() {#aba7ad0f0c5541959cd15d2a8212d2805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isEmptyTy ()</td>
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

<p>Return true if this type is empty, that is, it has no elements or all of its elements are empty.</p>

<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isFirstClassType() {#ad4ceea699daf16bb734ca70ed432da32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isFirstClassType ()</td>
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

<p>Return true if the type is "first class", meaning it is a valid type for a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a>.</p>

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isFloatingPointTy() {#a403d5aae9bd503730c3f24d9bd4f9d75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isFloatingPointTy ()</td>
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

<p>Return true if this is one of the floating-point types.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isFloatTy() {#ad1c1750c77a2aabe0f1bc43dad228938}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isFloatTy ()</td>
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

<p>Return true if this is 'float', a 32-bit IEEE fp type.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isFP128Ty() {#a072fdcb6e855e1cafe35b401e5fb9e3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isFP128Ty ()</td>
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

<p>Return true if this is 'fp128'.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isFPOrFPVectorTy() {#a609b0218dcee7182f7da35c0269a089e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isFPOrFPVectorTy ()</td>
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

<p>Return true if this is a FP type or a vector of FP.</p>

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isFunctionTy() {#ab0e36f09a9b993ef77dc9da5a3fdc669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isFunctionTy ()</td>
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

<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/functiontype">FunctionType</a>.</p>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isHalfTy() {#a653a09808a25c643bc85d6d801fc4b85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isHalfTy ()</td>
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

<p>Return true if this is 'half', a 16-bit IEEE fp type.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isIEEE() {#a1d234208b218b7ce24f588d074ba19e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isIEEE ()</td>
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

<p>Return whether the type is IEEE compatible, as defined by the eponymous method in <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a>.</p>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isIEEELikeFPTy() {#a35588fbd7a709079413e1271cf557900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isIEEELikeFPTy ()</td>
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

<p>Return true if this is a well-behaved IEEE-like type, which has a IEEE compatible layout as defined by <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af3bec23b6e372e677f17151bfd6af8fc">APFloat::isIEEE()</a>, and does not have non-IEEE values, such as x86_fp80's unnormal values.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isIntegerTy() {#a5bacc4d6d9314aee7630737b69fd0e6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isIntegerTy ()</td>
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

<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/integertype">IntegerType</a>.</p>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isIntegerTy() {#ad2ce7b7a68080f1d444cf19dc664064d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isIntegerTy (unsigned Bitwidth)</td>
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

<p>Return true if this is an <a href="/web-llvm/docs/api/classes/llvm/sandboxir/integertype">IntegerType</a> of the given width.</p>

<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isIntOrIntVectorTy() {#a6016210f4eaf48db86de4f8a68e18992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isIntOrIntVectorTy ()</td>
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

<p>Return true if this is an integer type or a vector of integer types.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isIntOrIntVectorTy() {#affc0db115d57236915c758662cdc0e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isIntOrIntVectorTy (unsigned BitWidth)</td>
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

<p>Return true if this is an integer type or a vector of integer types of the given width.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a> and <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isIntOrPtrTy() {#a273ddd8779c0b685831ecb9b00460c23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isIntOrPtrTy ()</td>
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

<p>Return true if this is an integer type or a pointer type.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isLabelTy() {#af383ba86b4ec0b76a0fc29c1e1fef520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isLabelTy ()</td>
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

<p>Return true if this is 'label'.</p>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isMetadataTy() {#a4a75855ad2835b678df69c6b509f4895}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isMetadataTy ()</td>
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

<p>Return true if this is 'metadata'.</p>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isMultiUnitFPType() {#ab8c3b8e29862ce750e9854578897f82e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isMultiUnitFPType ()</td>
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

<p>Returns true if this is a floating-point type that is an unevaluated sum of multiple floating-point units.</p>


<p>An example of such a type is ppc_fp128, also known as double-double, which consists of two IEEE 754 doubles.</p>


<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isPointerTy() {#ac031dfe19eddd49a7900e0c2288406c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isPointerTy ()</td>
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

<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pointertype">PointerType</a>.</p>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isPPC\_FP128Ty() {#a8eee2e276e155df99ab6465aff7e630f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isPPC_FP128Ty ()</td>
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

<p>Return true if this is powerpc long double.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isPtrOrPtrVectorTy() {#a83fd7127228e04b69f4f1b95cc7fd0e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isPtrOrPtrVectorTy ()</td>
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

<p>Return true if this is a pointer type or a vector of pointer types.</p>

<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isScalableTargetExtTy() {#ab5e193143003276b3ff4f39efce27d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isScalableTargetExtTy ()</td>
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

<p>Return true if this is a target extension type with a scalable layout.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isScalableTy() {#a04edb84fd1719b346874cfcc1caa268d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isScalableTy ()</td>
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

<p>Return true if this is a type whose size is a known multiple of vscale.</p>

<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isSingleValueType() {#a92e96f4687959015000cacde3ef7fdc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isSingleValueType ()</td>
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

<p>Return true if the type is a valid type for a register in codegen.</p>


<p>This includes all first-class types except struct and array types.</p>


<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isSized() {#a75e560adcff5992e25a089e2a26c5959}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isSized (<a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> * &gt; * Visited=nullptr)</td>
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

<p>Return true if it makes sense to take the size of this type.</p>


<p>To get the actual size for a particular target, it is reasonable to use the <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> subsystem to do this.</p>


<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#ae6450915b4be60dae8a3c11dc8fc95dc">llvm::SmallPtrSetImplBase::reserve</a> and <a href="#a386a56204d7dd7077ca711aff3c78d55">Type</a>.</p>

</div>
</div>

### isStructTy() {#a6550d037ba2597eaf235932babc42cbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isStructTy ()</td>
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

<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/structtype">StructType</a>.</p>

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isTargetExtTy() {#a309006f37f3e1e2f0bf5f3dae40c81da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isTargetExtTy ()</td>
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

<p>Return true if this is a target extension type.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isTokenTy() {#aa389f559f75d77d81e248787c811bccc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isTokenTy ()</td>
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

<p>Return true if this is 'token'.</p>

<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isVectorTy() {#ab72c549a3c63bf2f0093dc66b8a50e49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isVectorTy ()</td>
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

<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype">VectorType</a>.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isVoidTy() {#aa6689b781b94b74e8b0b4903549fba87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isVoidTy ()</td>
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

<p>Return true if this is 'void'.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isX86\_AMXTy() {#a657aea40682a55aeafe24659722d04db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isX86_AMXTy ()</td>
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

<p>Return true if this is <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> AMX.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### isX86\_FP80Ty() {#a0122c81207adb71b9a84569afc7ad426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Type::isX86_FP80Ty ()</td>
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

<p>Return true if this is x86 long double.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

### print() {#a5c4661418be55867a719a892bcec6171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Type::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsForDebug=false, bool NoDetails=false)</td>
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

<p>Print the current type.</p>


<p>Omit the type details if <span class="doxyComputerOutput">NoDetails</span> == true. E.g., let st = type { i32, i16 } When <span class="doxyComputerOutput">NoDetails</span> is true, we only print st. Put differently, <span class="doxyComputerOutput">NoDetails</span> prints the type as if inlined with the operands when printing an instruction.</p>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a330bbaf89b90196df6960be4724513c6">LLVMTy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Ctx {#ae616c2dab17f3dc139020928ef67ecaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Context&amp; llvm::sandboxir::Type::Ctx</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pointertype/#a6339a17772e61656c08fd77a488c9a50">llvm::sandboxir::PointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/structtype/#acdd011895dc673bd8b8edd5b8eaf871c">llvm::sandboxir::StructType::get</a>, <a href="#ae662f556252fe75768094c7976518409">getContext</a>, <a href="#a57e9061fb6d18ee131661f3c68a66eb2">getDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#ae3f468d365ecf76cd72b905bbaaa30c8">llvm::sandboxir::VectorType::getElementType</a>, <a href="#af4125c0ca2f91c4d506cfabc64fa4b20">getFloatTy</a>, <a href="#af9ef9c2652adaeee5bf72525dbd10677">getInt16Ty</a>, <a href="#a75eedc5667cb22e709e89fef21c08ee5">getInt1Ty</a>, <a href="#a8ba4ed00f8805b525fb7b4497a527876">getInt32Ty</a>, <a href="#aa3741ff4c00516153fc0d9285a1e4c9e">getInt64Ty</a>, <a href="#a53974d47ba590e4418c5952730fd9559">getInt8Ty</a>, <a href="#abecc000cb4767b88afe6f189716ae698">getScalarType</a> and <a href="#a386a56204d7dd7077ca711aff3c78d55">Type</a>.</p>

</div>
</div>

### LLVMTy {#a330bbaf89b90196df6960be4724513c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Type* llvm::sandboxir::Type::LLVMTy</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>Referenced by <a href="#a4421a693ebc6dcc93bb68b55fa4e8aeb">canLosslesslyBitCastTo</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/arraytype/#a3c013658646965dc531bf1bf68dc16ed">llvm::sandboxir::ArrayType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/functiontype/#a3afb28a7d344f4ae6c9ba13aef574862">llvm::sandboxir::FunctionType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/integertype/#a4a31a0075a81802a6819af6a75a64ca8">llvm::sandboxir::IntegerType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pointertype/#a1216d52d8d739088660964729affd967">llvm::sandboxir::PointerType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/structtype/#a7ffdded9dd28d8eb8b8563b295393de4">llvm::sandboxir::StructType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a37e3aa4bccef49d6abd3a6ecf5c2ba75">llvm::sandboxir::VectorType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a2f0388b8315300b55a8833caf090ef71">llvm::Type::containsNonLocalTargetExtType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a6224f807d740562c873c036926d0dfd9">llvm::sandboxir::ShuffleVectorInst::convertShuffleMaskForBitcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/castinst/#a9a5e242d5daa720bf3859f5f3cc2c727">llvm::sandboxir::CastInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/invokeinst/#a58be6f9d5ec9cd6dae7bd79e196fb837">llvm::sandboxir::InvokeInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5dcbbcb6c022f6f2c8b46a3e0a4821b5">llvm::Instruction::dropPoisonGeneratingReturnAttributes</a>, <a href="#ab65fd199fac3312ff9d0426dbae8cba8">dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a18f8eb5280ed8cfe6c45fa04ad45c703">llvm::sandboxir::VectorType::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#ae3f468d365ecf76cd72b905bbaaa30c8">llvm::sandboxir::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#ac96d755c768edd2cde7743330bbb6f5a">llvm::sandboxir::VectorType::getExtendedElementVectorType</a>, <a href="#a1d80d64662239762d1571a3f30777110">getFltSemantics</a>, <a href="#aad74baa920a4b77b6d30407bf65c8cd2">getFPMantissaWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a9cd3c5065659bc840e36b5a96ec94d96">llvm::sandboxir::VectorType::getHalfElementsVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractvalueinst/#a4e6ed8a1c14cfbc9d22aa336c96e4e0b">llvm::sandboxir::ExtractValueInst::getIndexedType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a78f34fdeeb7b2cc30adc895344d8df0f">llvm::sandboxir::VectorType::getInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/scalablevectortype/#aa62f2685c4d8d61f8f6ea9f346af76e9">llvm::sandboxir::ScalableVectorType::getMinNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fixedvectortype/#a3540d9ee4c3637633a1d7adb50a0cde1">llvm::sandboxir::FixedVectorType::getNumElements</a>, <a href="#a636cb45b78340dd800a37d42120f52cc">getPointerAddressSpace</a>, <a href="#a595135fd17d77e8ed5e48a8033e5fa24">getPrimitiveSizeInBits</a>, <a href="#a70633ba5047b4c5c7ce8a4db3b32bc86">getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a76908359b5b01e49efdd43d1d6e08c21">llvm::Instruction::hasAllowReciprocal</a>, <a href="#a75d0e9a1a8201baaa6705183195a24c3">is16bitFPTy</a>, <a href="#ad355244dc96e76a4dc72608668c02999">isAggregateType</a>, <a href="#a8dc0b8a87c047869511efe7f003cff5a">isArrayTy</a>, <a href="#afc69ff00f4dfce704386021f1195479a">isBFloatTy</a>, <a href="#a6633d096ce9fcaef9ec30c092ebbb63a">isDoubleTy</a>, <a href="#aba7ad0f0c5541959cd15d2a8212d2805">isEmptyTy</a>, <a href="#ad4ceea699daf16bb734ca70ed432da32">isFirstClassType</a>, <a href="#a403d5aae9bd503730c3f24d9bd4f9d75">isFloatingPointTy</a>, <a href="#ad1c1750c77a2aabe0f1bc43dad228938">isFloatTy</a>, <a href="#a072fdcb6e855e1cafe35b401e5fb9e3c">isFP128Ty</a>, <a href="#a609b0218dcee7182f7da35c0269a089e">isFPOrFPVectorTy</a>, <a href="#ab0e36f09a9b993ef77dc9da5a3fdc669">isFunctionTy</a>, <a href="#a653a09808a25c643bc85d6d801fc4b85">isHalfTy</a>, <a href="#a1d234208b218b7ce24f588d074ba19e6">isIEEE</a>, <a href="#a35588fbd7a709079413e1271cf557900">isIEEELikeFPTy</a>, <a href="#a5bacc4d6d9314aee7630737b69fd0e6a">isIntegerTy</a>, <a href="#ad2ce7b7a68080f1d444cf19dc664064d">isIntegerTy</a>, <a href="#a6016210f4eaf48db86de4f8a68e18992">isIntOrIntVectorTy</a>, <a href="#affc0db115d57236915c758662cdc0e1d">isIntOrIntVectorTy</a>, <a href="#a273ddd8779c0b685831ecb9b00460c23">isIntOrPtrTy</a>, <a href="#af383ba86b4ec0b76a0fc29c1e1fef520">isLabelTy</a>, <a href="#a4a75855ad2835b678df69c6b509f4895">isMetadataTy</a>, <a href="#ab8c3b8e29862ce750e9854578897f82e">isMultiUnitFPType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/structtype/#a914cfe5f464cfceb5050d7dce48eee61">llvm::sandboxir::StructType::isPacked</a>, <a href="#ac031dfe19eddd49a7900e0c2288406c3">isPointerTy</a>, <a href="#a8eee2e276e155df99ab6465aff7e630f">isPPC_FP128Ty</a>, <a href="#a83fd7127228e04b69f4f1b95cc7fd0e2">isPtrOrPtrVectorTy</a>, <a href="#ab5e193143003276b3ff4f39efce27d34">isScalableTargetExtTy</a>, <a href="#a04edb84fd1719b346874cfcc1caa268d">isScalableTy</a>, <a href="#a92e96f4687959015000cacde3ef7fdc7">isSingleValueType</a>, <a href="#a75e560adcff5992e25a089e2a26c5959">isSized</a>, <a href="#a6550d037ba2597eaf235932babc42cbc">isStructTy</a>, <a href="#a309006f37f3e1e2f0bf5f3dae40c81da">isTargetExtTy</a>, <a href="#aa389f559f75d77d81e248787c811bccc">isTokenTy</a>, <a href="#ab72c549a3c63bf2f0093dc66b8a50e49">isVectorTy</a>, <a href="#aa6689b781b94b74e8b0b4903549fba87">isVoidTy</a>, <a href="#a657aea40682a55aeafe24659722d04db">isX86_AMXTy</a>, <a href="#a0122c81207adb71b9a84569afc7ad426">isX86_FP80Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/integertype/#afe750bbb6de9c213aafafd32d06f13d3">llvm::sandboxir::IntegerType::operator llvm::IntegerType &amp;</a>, <a href="#a5c4661418be55867a719a892bcec6171">print</a> and <a href="#a386a56204d7dd7077ca711aff3c78d55">Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getDoubleTy() {#a57e9061fb6d18ee131661f3c68a66eb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getDoubleTy (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx)</td>
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



<p>Declaration at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>References <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>, <a href="#ae616c2dab17f3dc139020928ef67ecaa">Ctx</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acb145f988329d1d621f73abcafea21d8">llvm::Type::getDoubleTy</a> and <a href="#a386a56204d7dd7077ca711aff3c78d55">Type</a>.</p>

</div>
</div>

### getFloatTy() {#af4125c0ca2f91c4d506cfabc64fa4b20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getFloatTy (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx)</td>
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



<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>References <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>, <a href="#ae616c2dab17f3dc139020928ef67ecaa">Ctx</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ad5e0fe0efdd88f98a5b5eb512d5351c2">llvm::Type::getFloatTy</a> and <a href="#a386a56204d7dd7077ca711aff3c78d55">Type</a>.</p>

</div>
</div>

### getInt16Ty() {#af9ef9c2652adaeee5bf72525dbd10677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getInt16Ty (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx)</td>
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



<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>References <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>, <a href="#ae616c2dab17f3dc139020928ef67ecaa">Ctx</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a87f56db834c58ca630624956ecf6972f">llvm::Type::getInt16Ty</a> and <a href="#a386a56204d7dd7077ca711aff3c78d55">Type</a>.</p>

</div>
</div>

### getInt1Ty() {#a75eedc5667cb22e709e89fef21c08ee5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getInt1Ty (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx)</td>
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



<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>References <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>, <a href="#ae616c2dab17f3dc139020928ef67ecaa">Ctx</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a> and <a href="#a386a56204d7dd7077ca711aff3c78d55">Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#a7b33bd9843f6f96a4f390a9314692657">llvm::sandboxir::CmpInst::makeCmpResultType</a>.</p>

</div>
</div>

### getInt32Ty() {#a8ba4ed00f8805b525fb7b4497a527876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getInt32Ty (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx)</td>
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



<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>References <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>, <a href="#ae616c2dab17f3dc139020928ef67ecaa">Ctx</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a> and <a href="#a386a56204d7dd7077ca711aff3c78d55">Type</a>.</p>

</div>
</div>

### getInt64Ty() {#aa3741ff4c00516153fc0d9285a1e4c9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getInt64Ty (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx)</td>
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



<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>References <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>, <a href="#ae616c2dab17f3dc139020928ef67ecaa">Ctx</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a> and <a href="#a386a56204d7dd7077ca711aff3c78d55">Type</a>.</p>

</div>
</div>

### getInt8Ty() {#a53974d47ba590e4418c5952730fd9559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getInt8Ty (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx)</td>
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



<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>References <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>, <a href="#ae616c2dab17f3dc139020928ef67ecaa">Ctx</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a> and <a href="#a386a56204d7dd7077ca711aff3c78d55">Type</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
