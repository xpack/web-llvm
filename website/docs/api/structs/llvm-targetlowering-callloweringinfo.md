---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/targetlowering/callloweringinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CallLoweringInfo` Struct Reference

<p>This structure contains all information that is necessary for lowering calls. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::TargetLowering::CallLoweringInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> (SelectionDAG &amp;DAG)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa05efb86ccf079a618d7ccc2d0984510">setDebugLoc</a> (const SDLoc &amp;dl)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8c9a19c4e49854df72efd6a33299ca6">setChain</a> (SDValue InChain)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3273e8eefbe635bf0be621b276e22add">setLibCallee</a> (CallingConv::ID CC, Type *ResultType, SDValue Target, ArgListTy &amp;&amp;ArgsList)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af85f2971df75297dfac1455dc7211b11">setCallee</a> (CallingConv::ID CC, Type *ResultType, SDValue Target, ArgListTy &amp;&amp;ArgsList, AttributeSet ResultAttrs={})</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ddc9a64edbc2fbd4ddef5dce758fbd0">setCallee</a> (Type *ResultType, FunctionType *FTy, SDValue Target, ArgListTy &amp;&amp;ArgsList, const CallBase &amp;Call)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a300dddb087cf0d8fce22f70be70de98f">setInRegister</a> (bool Value=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a463080ce54148082240cb19e03538">setNoReturn</a> (bool Value=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54fa25565af5a7e8ac0d490e678d93bc">setVarArg</a> (bool Value=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8b90e2248ac4afd696fe04d0363dba4">setTailCall</a> (bool Value=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92da69e2625a91ae468da5ed229a3a93">setDiscardResult</a> (bool Value=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03ba2eacb6adc820c314cd1455f1c504">setConvergent</a> (bool Value=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab983fdfb5b6ec04d4830c6c7982b5f3b">setSExtResult</a> (bool Value=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94d22aa7bb7d70c8ccdcb04d55e6b15e">setZExtResult</a> (bool Value=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a982d72dbe5b2fdba331ff1d7099cb22c">setIsPatchPoint</a> (bool Value=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8d48ba57acd45e77101777a817ac8ce">setIsPreallocated</a> (bool Value=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af34cfef3c11acfa3c1f2437f25984765">setPtrAuth</a> (PtrAuthInfo Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03ee6c968ba99e5c734ca0c403a80074">setIsPostTypeLegalization</a> (bool Value=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a248c253e17dbe9b14e68b192cf3962b5">setCFIType</a> (const ConstantInt *Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac08f737dbe6416c568d445a0fb062553">setConvergenceControlToken</a> (SDValue Token)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ae4ac6bc14db22dbd7b94a3b1bd276796">ArgListTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbf22b8a1f5ed1623341605748ec8df4">getArgs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4872f31b8be67e8a1998454db0766bd">Chain</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add4f6f94fcf01be61720d26a49591535">RetTy</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa70600610484cd4224ebf4b46656ef6a">RetSExt</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d1ffe16a83c436cac93b14e50ebf0bc">RetZExt</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eb6e80dc80f35553ccc33a89d691df8">IsVarArg</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06d8dcdadb7fe5b0b670265c16adcdc7">IsInReg</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff7c93844158eb2304289287f542b777">DoesNotReturn</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0915ec58e22758e2c4381de292b4790">IsReturnValueUsed</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade948d6152c2ba4ae5f265bb2e46ab85">IsConvergent</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a945fb9e2df3ba76a907952afc79b1773">IsPatchPoint</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4caeb21052d0c44c89c6718eb4b84162">IsPreallocated</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa91cc3233b03071cdfbb5a88d90703c9">NoMerge</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a283b7df55a414e3185b56aeea1ec7ee7">IsTailCall</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a587732fea793169dfae64b7f8386a8eb">IsPostTypeLegalization</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2860be7d7f42a52797181279c5f5d63">NumFixedArgs</a> = -1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae47a430364102f6e179d49cb3411b955">CallConv</a> = <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">CallingConv::C</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31faa4803c937d756c28947a070c6c2e">Callee</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ae4ac6bc14db22dbd7b94a3b1bd276796">ArgListTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a144154df8c813c3a0a9e8d7281c53853">Args</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae76ac9826f02f95aae34e845ac110244">DAG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b6fcbb7bdd8ae29e8af4cd38bce7a40">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd79db0f7d45129e8af1258541861ef8">CB</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a>, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad07ce660c9cb208ae98a53ad8b3ce1de">Outs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adba9c4dde08bb0a9de1c99e7e039d8a0">OutVals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a>, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a423dda4ff918d4145ccc1861f059f940">Ins</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58a3dfbca60dd5811b252fca05b254d3">InVals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f0ca4ab760f8e0574728142431554bd">CFIType</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f069901cdbc21b903dfedeaa63c3a26">ConvergenceControlToken</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/targetlowering/ptrauthinfo">PtrAuthInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8742a6e1203eb521404ec5a1d698a47d">PAI</a></td>
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

<p>This structure contains all information that is necessary for lowering calls.</p>


<p>It is passed to TLI::LowerCallTo when the <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> builder needs to lower a call, and targets will see this struct in their LowerCall implementation.</p>


<p>Definition at line 4529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CallLoweringInfo() {#af35bb64b495f2a61199dda4a3b9ec4b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetLowering::CallLoweringInfo::CallLoweringInfo (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4566 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#ae76ac9826f02f95aae34e845ac110244">DAG</a>, <a href="#aff7c93844158eb2304289287f542b777">DoesNotReturn</a>, <a href="#ade948d6152c2ba4ae5f265bb2e46ab85">IsConvergent</a>, <a href="#a06d8dcdadb7fe5b0b670265c16adcdc7">IsInReg</a>, <a href="#a945fb9e2df3ba76a907952afc79b1773">IsPatchPoint</a>, <a href="#a4caeb21052d0c44c89c6718eb4b84162">IsPreallocated</a>, <a href="#ac0915ec58e22758e2c4381de292b4790">IsReturnValueUsed</a>, <a href="#a3eb6e80dc80f35553ccc33a89d691df8">IsVarArg</a>, <a href="#aa91cc3233b03071cdfbb5a88d90703c9">NoMerge</a>, <a href="#aa70600610484cd4224ebf4b46656ef6a">RetSExt</a>, <a href="#a6d1ffe16a83c436cac93b14e50ebf0bc">RetZExt</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="#af85f2971df75297dfac1455dc7211b11">setCallee</a>, <a href="#a1ddc9a64edbc2fbd4ddef5dce758fbd0">setCallee</a>, <a href="#a248c253e17dbe9b14e68b192cf3962b5">setCFIType</a>, <a href="#ae8c9a19c4e49854df72efd6a33299ca6">setChain</a>, <a href="#ac08f737dbe6416c568d445a0fb062553">setConvergenceControlToken</a>, <a href="#a03ba2eacb6adc820c314cd1455f1c504">setConvergent</a>, <a href="#aa05efb86ccf079a618d7ccc2d0984510">setDebugLoc</a>, <a href="#a92da69e2625a91ae468da5ed229a3a93">setDiscardResult</a>, <a href="#a300dddb087cf0d8fce22f70be70de98f">setInRegister</a>, <a href="#a982d72dbe5b2fdba331ff1d7099cb22c">setIsPatchPoint</a>, <a href="#a03ee6c968ba99e5c734ca0c403a80074">setIsPostTypeLegalization</a>, <a href="#ab8d48ba57acd45e77101777a817ac8ce">setIsPreallocated</a>, <a href="#a3273e8eefbe635bf0be621b276e22add">setLibCallee</a>, <a href="#ab9a463080ce54148082240cb19e03538">setNoReturn</a>, <a href="#af34cfef3c11acfa3c1f2437f25984765">setPtrAuth</a>, <a href="#ab983fdfb5b6ec04d4830c6c7982b5f3b">setSExtResult</a>, <a href="#aa8b90e2248ac4afd696fe04d0363dba4">setTailCall</a>, <a href="#a54fa25565af5a7e8ac0d490e678d93bc">setVarArg</a> and <a href="#a94d22aa7bb7d70c8ccdcb04d55e6b15e">setZExtResult</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getArgs() {#abbf22b8a1f5ed1623341605748ec8df4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgListTy &amp; llvm::TargetLowering::CallLoweringInfo::getArgs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="#a144154df8c813c3a0a9e8d7281c53853">Args</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>.</p>

</div>
</div>

### setCallee() {#af85f2971df75297dfac1455dc7211b11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setCallee (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ResultType, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Target, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ae4ac6bc14db22dbd7b94a3b1bd276796">ArgListTy</a> &amp;&amp; ArgsList, <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> ResultAttrs={})</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a034082eea623803b4fa593f2e29f0d96">llvm::VETargetLowering::lowerDYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#af92646d30b3f15471c866cd83fadfb62">llvm::SparcTargetLowering::LowerF128Compare</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a85b82d7c69a744603ea8eccd2c40d52e">llvm::SparcTargetLowering::LowerF128Op</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a54af997c0e800a9cdfb65dabe296f7c4">llvm::SystemZTargetLowering::makeExternalCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a8a8a4b167d0244a5c34b6819dd3d5c56">llvm::SelectionDAGBuilder::populateCallLoweringInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae8662f747218aee8ddeb4cdfbd1435a7">llvm::SelectionDAGBuilder::visitSPDescriptorParent</a>.</p>

</div>
</div>

### setCallee() {#a1ddc9a64edbc2fbd4ddef5dce758fbd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setCallee (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ResultType, <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * FTy, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Target, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ae4ac6bc14db22dbd7b94a3b1bd276796">ArgListTy</a> &amp;&amp; ArgsList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#a144154df8c813c3a0a9e8d7281c53853">Args</a>, <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="#ae47a430364102f6e179d49cb3411b955">CallConv</a>, <a href="#a31faa4803c937d756c28947a070c6c2e">Callee</a>, <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a>, <a href="#acd79db0f7d45129e8af1258541861ef8">CB</a>, <a href="#aff7c93844158eb2304289287f542b777">DoesNotReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a104d6154321899b53e40455e71d8e83a">llvm::FunctionType::getNumParams</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a06d8dcdadb7fe5b0b670265c16adcdc7">IsInReg</a>, <a href="#ac0915ec58e22758e2c4381de292b4790">IsReturnValueUsed</a>, <a href="#a3eb6e80dc80f35553ccc33a89d691df8">IsVarArg</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#aa9d770048c7ab9e08222a50b7bc1be1c">llvm::FunctionType::isVarArg</a>, <a href="#aa91cc3233b03071cdfbb5a88d90703c9">NoMerge</a>, <a href="#aa2860be7d7f42a52797181279c5f5d63">NumFixedArgs</a>, <a href="#aa70600610484cd4224ebf4b46656ef6a">RetSExt</a>, <a href="#add4f6f94fcf01be61720d26a49591535">RetTy</a> and <a href="#a6d1ffe16a83c436cac93b14e50ebf0bc">RetZExt</a>.</p>

</div>
</div>

### setCFIType() {#a248c253e17dbe9b14e68b192cf3962b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setCFIType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * Type)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4698 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="#a5f0ca4ab760f8e0574728142431554bd">CFIType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>.</p>

</div>
</div>

### setChain() {#ae8c9a19c4e49854df72efd6a33299ca6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setChain (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> InChain)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="#aa4872f31b8be67e8a1998454db0766bd">Chain</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af13091d8b3eced08538be82392dc7d43">emitSMEStateSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo/#a3ef56098772bca9a4ca38bf149aa872c">llvm::ARMSelectionDAGInfo::EmitSpecializedLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64selectiondaginfo/#a4f4d5344fa41e237eb9a60c7b62975b8">llvm::AArch64SelectionDAGInfo::EmitStreamingCompatibleMemLibCall</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonselectiondaginfo/#a10a0dbb2ae8f208929d1f453d84cb101">llvm::HexagonSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreselectiondaginfo/#af87dbf9e0c8190963043ea6154532c25">llvm::XCoreSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adaa729f57e0b62f0dd995c6f5e3df8b7">llvm::SelectionDAG::expandMultipleResultFPLibCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c9c5b337e855fb0ce25e53c0bd3f992">llvm::SelectionDAG::getAtomicMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abe645b6f7de2918e594b110f3c819b07">llvm::SelectionDAG::getAtomicMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c60b6ae234b668266d9f21b0e1b8f89">llvm::SelectionDAG::getAtomicMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4590e453df8847d8d5eda7e37ae9dffa">llvm::SelectionDAG::getMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac3f766fb181e521628094d9a9e461606">llvm::SelectionDAG::getMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2150ad6f255dd827e24a5b76ec58d802">llvm::SelectionDAG::getMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a034082eea623803b4fa593f2e29f0d96">llvm::VETargetLowering::lowerDYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#af92646d30b3f15471c866cd83fadfb62">llvm::SparcTargetLowering::LowerF128Compare</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a85b82d7c69a744603ea8eccd2c40d52e">llvm::SparcTargetLowering::LowerF128Op</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a51e11fac59331e5e9704295214a2d5ee">LowerFSINCOS</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ab29b69c993fbb9a4b9d28c3600df005d">llvm::SelectionDAGBuilder::lowerInvokable</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a54af997c0e800a9cdfb65dabe296f7c4">llvm::SystemZTargetLowering::makeExternalCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a88f0e5db31eb88103b548f1bcce2da58">llvm::SelectionDAG::makeStateFunctionCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a8a8a4b167d0244a5c34b6819dd3d5c56">llvm::SelectionDAGBuilder::populateCallLoweringInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae8662f747218aee8ddeb4cdfbd1435a7">llvm::SelectionDAGBuilder::visitSPDescriptorParent</a>.</p>

</div>
</div>

### setConvergenceControlToken() {#ac08f737dbe6416c568d445a0fb062553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setConvergenceControlToken (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Token)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="#a3f069901cdbc21b903dfedeaa63c3a26">ConvergenceControlToken</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>.</p>

</div>
</div>

### setConvergent() {#a03ba2eacb6adc820c314cd1455f1c504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setConvergent (bool Value=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="#ade948d6152c2ba4ae5f265bb2e46ab85">IsConvergent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>.</p>

</div>
</div>

### setDebugLoc() {#aa05efb86ccf079a618d7ccc2d0984510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setDebugLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4572 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="#a3b6fcbb7bdd8ae29e8af4cd38bce7a40">DL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af13091d8b3eced08538be82392dc7d43">emitSMEStateSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo/#a3ef56098772bca9a4ca38bf149aa872c">llvm::ARMSelectionDAGInfo::EmitSpecializedLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64selectiondaginfo/#a4f4d5344fa41e237eb9a60c7b62975b8">llvm::AArch64SelectionDAGInfo::EmitStreamingCompatibleMemLibCall</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonselectiondaginfo/#a10a0dbb2ae8f208929d1f453d84cb101">llvm::HexagonSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreselectiondaginfo/#af87dbf9e0c8190963043ea6154532c25">llvm::XCoreSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adaa729f57e0b62f0dd995c6f5e3df8b7">llvm::SelectionDAG::expandMultipleResultFPLibCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c9c5b337e855fb0ce25e53c0bd3f992">llvm::SelectionDAG::getAtomicMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abe645b6f7de2918e594b110f3c819b07">llvm::SelectionDAG::getAtomicMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c60b6ae234b668266d9f21b0e1b8f89">llvm::SelectionDAG::getAtomicMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4590e453df8847d8d5eda7e37ae9dffa">llvm::SelectionDAG::getMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac3f766fb181e521628094d9a9e461606">llvm::SelectionDAG::getMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2150ad6f255dd827e24a5b76ec58d802">llvm::SelectionDAG::getMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a034082eea623803b4fa593f2e29f0d96">llvm::VETargetLowering::lowerDYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#af92646d30b3f15471c866cd83fadfb62">llvm::SparcTargetLowering::LowerF128Compare</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a85b82d7c69a744603ea8eccd2c40d52e">llvm::SparcTargetLowering::LowerF128Op</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a51e11fac59331e5e9704295214a2d5ee">LowerFSINCOS</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a54af997c0e800a9cdfb65dabe296f7c4">llvm::SystemZTargetLowering::makeExternalCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a88f0e5db31eb88103b548f1bcce2da58">llvm::SelectionDAG::makeStateFunctionCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a8a8a4b167d0244a5c34b6819dd3d5c56">llvm::SelectionDAGBuilder::populateCallLoweringInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae8662f747218aee8ddeb4cdfbd1435a7">llvm::SelectionDAGBuilder::visitSPDescriptorParent</a>.</p>

</div>
</div>

### setDiscardResult() {#a92da69e2625a91ae468da5ed229a3a93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setDiscardResult (bool Value=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4658 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="#ac0915ec58e22758e2c4381de292b4790">IsReturnValueUsed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo/#a3ef56098772bca9a4ca38bf149aa872c">llvm::ARMSelectionDAGInfo::EmitSpecializedLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonselectiondaginfo/#a10a0dbb2ae8f208929d1f453d84cb101">llvm::HexagonSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreselectiondaginfo/#af87dbf9e0c8190963043ea6154532c25">llvm::XCoreSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c9c5b337e855fb0ce25e53c0bd3f992">llvm::SelectionDAG::getAtomicMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abe645b6f7de2918e594b110f3c819b07">llvm::SelectionDAG::getAtomicMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c60b6ae234b668266d9f21b0e1b8f89">llvm::SelectionDAG::getAtomicMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4590e453df8847d8d5eda7e37ae9dffa">llvm::SelectionDAG::getMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac3f766fb181e521628094d9a9e461606">llvm::SelectionDAG::getMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2150ad6f255dd827e24a5b76ec58d802">llvm::SelectionDAG::getMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a034082eea623803b4fa593f2e29f0d96">llvm::VETargetLowering::lowerDYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a54af997c0e800a9cdfb65dabe296f7c4">llvm::SystemZTargetLowering::makeExternalCall</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a8a8a4b167d0244a5c34b6819dd3d5c56">llvm::SelectionDAGBuilder::populateCallLoweringInfo</a>.</p>

</div>
</div>

### setInRegister() {#a300dddb087cf0d8fce22f70be70de98f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setInRegister (bool Value=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4638 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="#a06d8dcdadb7fe5b0b670265c16adcdc7">IsInReg</a>.</p>

</div>
</div>

### setIsPatchPoint() {#a982d72dbe5b2fdba331ff1d7099cb22c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setIsPatchPoint (bool Value=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4678 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="#a945fb9e2df3ba76a907952afc79b1773">IsPatchPoint</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a8a8a4b167d0244a5c34b6819dd3d5c56">llvm::SelectionDAGBuilder::populateCallLoweringInfo</a>.</p>

</div>
</div>

### setIsPostTypeLegalization() {#a03ee6c968ba99e5c734ca0c403a80074}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setIsPostTypeLegalization (bool Value=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4693 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="#a587732fea793169dfae64b7f8386a8eb">IsPostTypeLegalization</a>.</p>

</div>
</div>

### setIsPreallocated() {#ab8d48ba57acd45e77101777a817ac8ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setIsPreallocated (bool Value=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4683 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="#a4caeb21052d0c44c89c6718eb4b84162">IsPreallocated</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a8a8a4b167d0244a5c34b6819dd3d5c56">llvm::SelectionDAGBuilder::populateCallLoweringInfo</a>.</p>

</div>
</div>

### setLibCallee() {#a3273e8eefbe635bf0be621b276e22add}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setLibCallee (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ResultType, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Target, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ae4ac6bc14db22dbd7b94a3b1bd276796">ArgListTy</a> &amp;&amp; ArgsList)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#a144154df8c813c3a0a9e8d7281c53853">Args</a>, <a href="#ae47a430364102f6e179d49cb3411b955">CallConv</a>, <a href="#a31faa4803c937d756c28947a070c6c2e">Callee</a>, <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#ae76ac9826f02f95aae34e845ac110244">DAG</a>, <a href="#aa2860be7d7f42a52797181279c5f5d63">NumFixedArgs</a> and <a href="#add4f6f94fcf01be61720d26a49591535">RetTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af13091d8b3eced08538be82392dc7d43">emitSMEStateSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo/#a3ef56098772bca9a4ca38bf149aa872c">llvm::ARMSelectionDAGInfo::EmitSpecializedLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64selectiondaginfo/#a4f4d5344fa41e237eb9a60c7b62975b8">llvm::AArch64SelectionDAGInfo::EmitStreamingCompatibleMemLibCall</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonselectiondaginfo/#a10a0dbb2ae8f208929d1f453d84cb101">llvm::HexagonSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreselectiondaginfo/#af87dbf9e0c8190963043ea6154532c25">llvm::XCoreSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adaa729f57e0b62f0dd995c6f5e3df8b7">llvm::SelectionDAG::expandMultipleResultFPLibCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c9c5b337e855fb0ce25e53c0bd3f992">llvm::SelectionDAG::getAtomicMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abe645b6f7de2918e594b110f3c819b07">llvm::SelectionDAG::getAtomicMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c60b6ae234b668266d9f21b0e1b8f89">llvm::SelectionDAG::getAtomicMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4590e453df8847d8d5eda7e37ae9dffa">llvm::SelectionDAG::getMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac3f766fb181e521628094d9a9e461606">llvm::SelectionDAG::getMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2150ad6f255dd827e24a5b76ec58d802">llvm::SelectionDAG::getMemset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a51e11fac59331e5e9704295214a2d5ee">LowerFSINCOS</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a88f0e5db31eb88103b548f1bcce2da58">llvm::SelectionDAG::makeStateFunctionCall</a>.</p>

</div>
</div>

### setNoReturn() {#ab9a463080ce54148082240cb19e03538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setNoReturn (bool Value=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="#aff7c93844158eb2304289287f542b777">DoesNotReturn</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a54af997c0e800a9cdfb65dabe296f7c4">llvm::SystemZTargetLowering::makeExternalCall</a>.</p>

</div>
</div>

### setPtrAuth() {#af34cfef3c11acfa3c1f2437f25984765}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setPtrAuth (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/ptrauthinfo">PtrAuthInfo</a> Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4688 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="#a8742a6e1203eb521404ec5a1d698a47d">PAI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>.</p>

</div>
</div>

### setSExtResult() {#ab983fdfb5b6ec04d4830c6c7982b5f3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setSExtResult (bool Value=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4668 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="#aa70600610484cd4224ebf4b46656ef6a">RetSExt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a54af997c0e800a9cdfb65dabe296f7c4">llvm::SystemZTargetLowering::makeExternalCall</a>.</p>

</div>
</div>

### setTailCall() {#aa8b90e2248ac4afd696fe04d0363dba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setTailCall (bool Value=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4653 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="#a283b7df55a414e3185b56aeea1ec7ee7">IsTailCall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c9c5b337e855fb0ce25e53c0bd3f992">llvm::SelectionDAG::getAtomicMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abe645b6f7de2918e594b110f3c819b07">llvm::SelectionDAG::getAtomicMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c60b6ae234b668266d9f21b0e1b8f89">llvm::SelectionDAG::getAtomicMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4590e453df8847d8d5eda7e37ae9dffa">llvm::SelectionDAG::getMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac3f766fb181e521628094d9a9e461606">llvm::SelectionDAG::getMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2150ad6f255dd827e24a5b76ec58d802">llvm::SelectionDAG::getMemset</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>.</p>

</div>
</div>

### setVarArg() {#a54fa25565af5a7e8ac0d490e678d93bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setVarArg (bool Value=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4648 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="#a3eb6e80dc80f35553ccc33a89d691df8">IsVarArg</a>.</p>

</div>
</div>

### setZExtResult() {#a94d22aa7bb7d70c8ccdcb04d55e6b15e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::TargetLowering::CallLoweringInfo::setZExtResult (bool Value=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="#a6d1ffe16a83c436cac93b14e50ebf0bc">RetZExt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a54af997c0e800a9cdfb65dabe296f7c4">llvm::SystemZTargetLowering::makeExternalCall</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Args {#a144154df8c813c3a0a9e8d7281c53853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgListTy llvm::TargetLowering::CallLoweringInfo::Args</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bf014c51371fcfb7c32e932c2d3b1d6">analyzeCallOperands</a>, <a href="#abbf22b8a1f5ed1623341605748ec8df4">getArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="#a1ddc9a64edbc2fbd4ddef5dce758fbd0">setCallee</a> and <a href="#a3273e8eefbe635bf0be621b276e22add">setLibCallee</a>.</p>

</div>
</div>

### CallConv {#ae47a430364102f6e179d49cb3411b955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallingConv::ID llvm::TargetLowering::CallLoweringInfo::CallConv = <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">CallingConv::C</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4551 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bf014c51371fcfb7c32e932c2d3b1d6">analyzeCallOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a93bebb4498805f11e17d91d7cde35511">llvm::MipsTargetLowering::getOpndList</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="#a1ddc9a64edbc2fbd4ddef5dce758fbd0">setCallee</a> and <a href="#a3273e8eefbe635bf0be621b276e22add">setLibCallee</a>.</p>

</div>
</div>

### Callee {#a31faa4803c937d756c28947a070c6c2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::CallLoweringInfo::Callee</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a93bebb4498805f11e17d91d7cde35511">llvm::MipsTargetLowering::getOpndList</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a2b01b00892f78bc1a75f271e3b9042f5">llvm::AMDGPUTargetLowering::lowerUnhandledCall</a>, <a href="#a1ddc9a64edbc2fbd4ddef5dce758fbd0">setCallee</a> and <a href="#a3273e8eefbe635bf0be621b276e22add">setLibCallee</a>.</p>

</div>
</div>

### CB {#acd79db0f7d45129e8af1258541861ef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallBase* llvm::TargetLowering::CallLoweringInfo::CB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ab29b69c993fbb9a4b9d28c3600df005d">llvm::SelectionDAGBuilder::lowerInvokable</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aae4a4706a2a2568c38bd04b1354eafb4">llvm::SITargetLowering::passSpecialInputs</a> and <a href="#a1ddc9a64edbc2fbd4ddef5dce758fbd0">setCallee</a>.</p>

</div>
</div>

### CFIType {#a5f0ca4ab760f8e0574728142431554bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstantInt* llvm::TargetLowering::CallLoweringInfo::CFIType = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a> and <a href="#a248c253e17dbe9b14e68b192cf3962b5">setCFIType</a>.</p>

</div>
</div>

### Chain {#aa4872f31b8be67e8a1998454db0766bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::CallLoweringInfo::Chain</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a> and <a href="#ae8c9a19c4e49854df72efd6a33299ca6">setChain</a>.</p>

</div>
</div>

### ConvergenceControlToken {#a3f069901cdbc21b903dfedeaa63c3a26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::CallLoweringInfo::ConvergenceControlToken</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a> and <a href="#ac08f737dbe6416c568d445a0fb062553">setConvergenceControlToken</a>.</p>

</div>
</div>

### DAG {#ae76ac9826f02f95aae34e845ac110244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectionDAG&amp; llvm::TargetLowering::CallLoweringInfo::DAG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bf014c51371fcfb7c32e932c2d3b1d6">analyzeCallOperands</a>, <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a93bebb4498805f11e17d91d7cde35511">llvm::MipsTargetLowering::getOpndList</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a2b01b00892f78bc1a75f271e3b9042f5">llvm::AMDGPUTargetLowering::lowerUnhandledCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aae4a4706a2a2568c38bd04b1354eafb4">llvm::SITargetLowering::passSpecialInputs</a> and <a href="#a3273e8eefbe635bf0be621b276e22add">setLibCallee</a>.</p>

</div>
</div>

### DL {#a3b6fcbb7bdd8ae29e8af4cd38bce7a40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDLoc llvm::TargetLowering::CallLoweringInfo::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4555 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a93bebb4498805f11e17d91d7cde35511">llvm::MipsTargetLowering::getOpndList</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a2b01b00892f78bc1a75f271e3b9042f5">llvm::AMDGPUTargetLowering::lowerUnhandledCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aae4a4706a2a2568c38bd04b1354eafb4">llvm::SITargetLowering::passSpecialInputs</a> and <a href="#aa05efb86ccf079a618d7ccc2d0984510">setDebugLoc</a>.</p>

</div>
</div>

### DoesNotReturn {#aff7c93844158eb2304289287f542b777}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::CallLoweringInfo::DoesNotReturn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="#a1ddc9a64edbc2fbd4ddef5dce758fbd0">setCallee</a> and <a href="#ab9a463080ce54148082240cb19e03538">setNoReturn</a>.</p>

</div>
</div>

### Ins {#a423dda4ff918d4145ccc1861f059f940}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;ISD::InputArg, 32&gt; llvm::TargetLowering::CallLoweringInfo::Ins</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a2b01b00892f78bc1a75f271e3b9042f5">llvm::AMDGPUTargetLowering::lowerUnhandledCall</a>.</p>

</div>
</div>

### InVals {#a58a3dfbca60dd5811b252fca05b254d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SDValue, 4&gt; llvm::TargetLowering::CallLoweringInfo::InVals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>.</p>

</div>
</div>

### IsConvergent {#ade948d6152c2ba4ae5f265bb2e46ab85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::CallLoweringInfo::IsConvergent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a> and <a href="#a03ba2eacb6adc820c314cd1455f1c504">setConvergent</a>.</p>

</div>
</div>

### IsInReg {#a06d8dcdadb7fe5b0b670265c16adcdc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::CallLoweringInfo::IsInReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a3c16ae9b6c38652cd59f72eeecc4e176">getReturnAttrs</a>, <a href="#a1ddc9a64edbc2fbd4ddef5dce758fbd0">setCallee</a> and <a href="#a300dddb087cf0d8fce22f70be70de98f">setInRegister</a>.</p>

</div>
</div>

### IsPatchPoint {#a945fb9e2df3ba76a907952afc79b1773}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::CallLoweringInfo::IsPatchPoint</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4539 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="#a982d72dbe5b2fdba331ff1d7099cb22c">setIsPatchPoint</a>.</p>

</div>
</div>

### IsPostTypeLegalization {#a587732fea793169dfae64b7f8386a8eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::CallLoweringInfo::IsPostTypeLegalization = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#a03ee6c968ba99e5c734ca0c403a80074">setIsPostTypeLegalization</a>.</p>

</div>
</div>

### IsPreallocated {#a4caeb21052d0c44c89c6718eb4b84162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::CallLoweringInfo::IsPreallocated</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a> and <a href="#ab8d48ba57acd45e77101777a817ac8ce">setIsPreallocated</a>.</p>

</div>
</div>

### IsReturnValueUsed {#ac0915ec58e22758e2c4381de292b4790}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::CallLoweringInfo::IsReturnValueUsed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a>, <a href="#a1ddc9a64edbc2fbd4ddef5dce758fbd0">setCallee</a> and <a href="#a92da69e2625a91ae468da5ed229a3a93">setDiscardResult</a>.</p>

</div>
</div>

### IsTailCall {#a283b7df55a414e3185b56aeea1ec7ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::CallLoweringInfo::IsTailCall = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ab29b69c993fbb9a4b9d28c3600df005d">llvm::SelectionDAGBuilder::lowerInvokable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a2b01b00892f78bc1a75f271e3b9042f5">llvm::AMDGPUTargetLowering::lowerUnhandledCall</a> and <a href="#aa8b90e2248ac4afd696fe04d0363dba4">setTailCall</a>.</p>

</div>
</div>

### IsVarArg {#a3eb6e80dc80f35553ccc33a89d691df8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::CallLoweringInfo::IsVarArg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4534 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bf014c51371fcfb7c32e932c2d3b1d6">analyzeCallOperands</a>, <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="#a1ddc9a64edbc2fbd4ddef5dce758fbd0">setCallee</a> and <a href="#a54fa25565af5a7e8ac0d490e678d93bc">setVarArg</a>.</p>

</div>
</div>

### NoMerge {#aa91cc3233b03071cdfbb5a88d90703c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::CallLoweringInfo::NoMerge</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a> and <a href="#a1ddc9a64edbc2fbd4ddef5dce758fbd0">setCallee</a>.</p>

</div>
</div>

### NumFixedArgs {#aa2860be7d7f42a52797181279c5f5d63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetLowering::CallLoweringInfo::NumFixedArgs = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4550 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="#a1ddc9a64edbc2fbd4ddef5dce758fbd0">setCallee</a> and <a href="#a3273e8eefbe635bf0be621b276e22add">setLibCallee</a>.</p>

</div>
</div>

### Outs {#ad07ce660c9cb208ae98a53ad8b3ce1de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;ISD::OutputArg, 32&gt; llvm::TargetLowering::CallLoweringInfo::Outs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bf014c51371fcfb7c32e932c2d3b1d6">analyzeCallOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a4ae582227faa40eda6e7066409e56596">llvm::SparcTargetLowering::IsEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a> and <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>.</p>

</div>
</div>

### OutVals {#adba9c4dde08bb0a9de1c99e7e039d8a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SDValue, 32&gt; llvm::TargetLowering::CallLoweringInfo::OutVals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4558 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a> and <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>.</p>

</div>
</div>

### PAI {#a8742a6e1203eb521404ec5a1d698a47d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;PtrAuthInfo&gt; llvm::TargetLowering::CallLoweringInfo::PAI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4564 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#af34cfef3c11acfa3c1f2437f25984765">setPtrAuth</a>.</p>

</div>
</div>

### RetSExt {#aa70600610484cd4224ebf4b46656ef6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::CallLoweringInfo::RetSExt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a3c16ae9b6c38652cd59f72eeecc4e176">getReturnAttrs</a>, <a href="#a1ddc9a64edbc2fbd4ddef5dce758fbd0">setCallee</a> and <a href="#ab983fdfb5b6ec04d4830c6c7982b5f3b">setSExtResult</a>.</p>

</div>
</div>

### RetTy {#add4f6f94fcf01be61720d26a49591535}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::TargetLowering::CallLoweringInfo::RetTy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a3c16ae9b6c38652cd59f72eeecc4e176">getReturnAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="#a1ddc9a64edbc2fbd4ddef5dce758fbd0">setCallee</a> and <a href="#a3273e8eefbe635bf0be621b276e22add">setLibCallee</a>.</p>

</div>
</div>

### RetZExt {#a6d1ffe16a83c436cac93b14e50ebf0bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::CallLoweringInfo::RetZExt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#af35bb64b495f2a61199dda4a3b9ec4b2">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a3c16ae9b6c38652cd59f72eeecc4e176">getReturnAttrs</a>, <a href="#a1ddc9a64edbc2fbd4ddef5dce758fbd0">setCallee</a> and <a href="#a94d22aa7bb7d70c8ccdcb04d55e6b15e">setZExtResult</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
