---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-bpfabstractmemberaccess-cpp-/bpfabstractmemberaccess
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BPFAbstractMemberAccess` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{BPFAbstractMemberAccess.cpp}::BPFAbstractMemberAccess { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::stack&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *, <a href="/web-llvm/docs/api/structs/anonymous-bpfabstractmemberaccess-cpp-/bpfabstractmemberaccess/callinfo">CallInfo</a> &gt; &gt; <a href="#a6092fa80f91f8782d89f7da4dff528b3">CallInfoStack</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"> : uint32_t { <a href="#abc105875bb6a3a3eea351dfad4a34b4b">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2906b7598612dd8714e43cd2d1ca15a">BPFAbstractMemberAccess</a> (BPFTargetMachine *TM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a592a12733b116d4ef519a2bae3ef64ed">run</a> (Function &amp;F)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c835406e78e4248b3128850449447ca">CheckAnonRecordType</a> (DIDerivedType *ParentTy, DIType *Ty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70ba18289268d0cbcb888d269d0e0598">CheckCompositeType</a> (DIDerivedType *ParentTy, DICompositeType *CTy)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af845631260e6ff85b68b07196c4c45de">CheckDerivedType</a> (DIDerivedType *ParentTy, DIDerivedType *DTy)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a886cf05f2e31cb9009975d868d4cb26e">ResetMetadata</a> (struct CallInfo &amp;CInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac914ed50f1320315219fccfd51169035">doTransformation</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac28826587a3cbe8c1b799744af4d780d">traceAICall</a> (CallInst *Call, CallInfo &amp;ParentInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea7ac0f19817373958759a1d9cc2838e">traceBitCast</a> (BitCastInst *BitCast, CallInst *Parent, CallInfo &amp;ParentInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4ed05fae393bfa56a53ca69b73d807a">traceGEP</a> (GetElementPtrInst *GEP, CallInst *Parent, CallInfo &amp;ParentInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12b5cdf690cdbd94b3eff1278041ddb8">collectAICallChains</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a472495704d70899f8acc11387aa655fd">IsPreserveDIAccessIndexCall</a> (const CallInst *Call, CallInfo &amp;Cinfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check whether a call is a preserve_*_access_index intrinsic call or not. <a href="#a472495704d70899f8acc11387aa655fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b7437ca3cca05058e48bed2cf20cbdf">IsValidAIChain</a> (const MDNode *ParentMeta, uint32_t ParentAI, const MDNode *ChildMeta)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check whether the access index chain is valid. <a href="#a2b7437ca3cca05058e48bed2cf20cbdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01bc51aea19602d2b315557b37b0e6e0">removePreserveAccessIndexIntrinsic</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ab541e9dd0f4ab54cef130b8806b81c">HasPreserveFieldInfoCall</a> (CallInfoStack &amp;CallStack)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bf89cd5668ddb8463914332d7b5522f">GetStorageBitRange</a> (DIDerivedType *MemberTy, Align RecordAlignment, uint32_t &amp;StartBitOffset, uint32_t &amp;EndBitOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the start and the end of storage offset for <span class="doxyComputerOutput">MemberTy</span>. <a href="#a5bf89cd5668ddb8463914332d7b5522f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a109cc6316d5d6818d044544956be11d5">GetFieldInfo</a> (uint32_t InfoKind, DICompositeType *CTy, uint32_t AccessIndex, uint32_t PatchImm, MaybeAlign RecordAlignment)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a977a8eff607d5d431db3e7a6cfd7a4a3">computeBaseAndAccessKey</a> (CallInst *Call, CallInfo &amp;CInfo, std::string &amp;AccessKey, MDNode *&amp;BaseMeta)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the base of the whole preserve_* intrinsics chains, i.e., the base pointer of the first preserve_*_access_index call, and construct the access string, which will be the name of a global variable. <a href="#a977a8eff607d5d431db3e7a6cfd7a4a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa635b1ce7a8025cb87be744b15d42796">computeAccessKey</a> (CallInst *Call, CallInfo &amp;CInfo, std::string &amp;AccessKey, bool &amp;IsInt32Ret)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd086b776bf3592077bd431c856edf0b">transformGEPChain</a> (CallInst *Call, CallInfo &amp;CInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call/Kind is the base preserve_*_access_index() call. <a href="#acd086b776bf3592077bd431c856edf0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae319411eef47e4ad151f6ec198c7edb9">TM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2970948bd4f6fd5a525819e1045c7284">DL</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f15a4b08e6d62df5717d6be3471cfb">M</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *, <a href="/web-llvm/docs/api/structs/anonymous-bpfabstractmemberaccess-cpp-/bpfabstractmemberaccess/callinfo">CallInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a389808253755ef8857caeef6f5318213">AIChain</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *, <a href="/web-llvm/docs/api/structs/anonymous-bpfabstractmemberaccess-cpp-/bpfabstractmemberaccess/callinfo">CallInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0717cdffc9bf497b8afe8ed833863bdc">BaseAICalls</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *, <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b7819948b8625b301987229dcf0c39d">AnonRecords</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::map&lt; std::string, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1a47f8b2c87e8b9a0ff95e60b1380da">GEPGlobals</a></td>
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


<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CallInfoStack {#a6092fa80f91f8782d89f7da4dff528b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::stack&lt;std::pair&lt;CallInst *, CallInfo&gt; &gt; anonymous{BPFAbstractMemberAccess.cpp}::BPFAbstractMemberAccess::CallInfoStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#abc105875bb6a3a3eea351dfad4a34b4b}

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
<td class="doxyEnumItemName">BPFPreserveArrayAI<a id="abc105875bb6a3a3eea351dfad4a34b4ba58127a3a949408617f0a1a16f440f877"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPFPreserveUnionAI<a id="abc105875bb6a3a3eea351dfad4a34b4bada83802dee93d7b6617029aab159422b"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPFPreserveStructAI<a id="abc105875bb6a3a3eea351dfad4a34b4ba65fa86360f9262d090b1f99009686543"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPFPreserveFieldInfoAI<a id="abc105875bb6a3a3eea351dfad4a34b4babf6d0e8e45fd485f82b590b0b51d9245"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BPFAbstractMemberAccess() {#af2906b7598612dd8714e43cd2d1ca15a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BPFAbstractMemberAccess.cpp}::BPFAbstractMemberAccess::BPFAbstractMemberAccess (<a href="/web-llvm/docs/api/classes/llvm/bpftargetmachine">BPFTargetMachine</a> * TM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a592a12733b116d4ef519a2bae3ef64ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BPFAbstractMemberAccess::run (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### CheckAnonRecordType() {#a0c835406e78e4248b3128850449447ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BPFAbstractMemberAccess::CheckAnonRecordType (<a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * ParentTy, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### CheckCompositeType() {#a70ba18289268d0cbcb888d269d0e0598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BPFAbstractMemberAccess::CheckCompositeType (<a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * ParentTy, <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * CTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### CheckDerivedType() {#af845631260e6ff85b68b07196c4c45de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BPFAbstractMemberAccess::CheckDerivedType (<a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * ParentTy, <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * DTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### collectAICallChains() {#a12b5cdf690cdbd94b3eff1278041ddb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BPFAbstractMemberAccess::collectAICallChains (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### computeAccessKey() {#aa635b1ce7a8025cb87be744b15d42796}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * BPFAbstractMemberAccess::computeAccessKey (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * Call, <a href="/web-llvm/docs/api/structs/anonymous-bpfabstractmemberaccess-cpp-/bpfabstractmemberaccess/callinfo">CallInfo</a> &amp; CInfo, std::string &amp; AccessKey, bool &amp; IsInt32Ret)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### computeBaseAndAccessKey() {#a977a8eff607d5d431db3e7a6cfd7a4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * BPFAbstractMemberAccess::computeBaseAndAccessKey (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * Call, <a href="/web-llvm/docs/api/structs/anonymous-bpfabstractmemberaccess-cpp-/bpfabstractmemberaccess/callinfo">CallInfo</a> &amp; CInfo, std::string &amp; AccessKey, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *&amp; BaseMeta)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the base of the whole preserve_* intrinsics chains, i.e., the base pointer of the first preserve_*_access_index call, and construct the access string, which will be the name of a global variable.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### doTransformation() {#ac914ed50f1320315219fccfd51169035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BPFAbstractMemberAccess::doTransformation (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### GetFieldInfo() {#a109cc6316d5d6818d044544956be11d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t BPFAbstractMemberAccess::GetFieldInfo (uint32_t InfoKind, <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * CTy, uint32_t AccessIndex, uint32_t PatchImm, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> RecordAlignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### GetStorageBitRange() {#a5bf89cd5668ddb8463914332d7b5522f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BPFAbstractMemberAccess::GetStorageBitRange (<a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * MemberTy, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> RecordAlignment, uint32_t &amp; StartBitOffset, uint32_t &amp; EndBitOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the start and the end of storage offset for <span class="doxyComputerOutput">MemberTy</span>.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### HasPreserveFieldInfoCall() {#a0ab541e9dd0f4ab54cef130b8806b81c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BPFAbstractMemberAccess::HasPreserveFieldInfoCall (<a href="#a6092fa80f91f8782d89f7da4dff528b3">CallInfoStack</a> &amp; CallStack)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### IsPreserveDIAccessIndexCall() {#a472495704d70899f8acc11387aa655fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BPFAbstractMemberAccess::IsPreserveDIAccessIndexCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * Call, <a href="/web-llvm/docs/api/structs/anonymous-bpfabstractmemberaccess-cpp-/bpfabstractmemberaccess/callinfo">CallInfo</a> &amp; Cinfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check whether a call is a preserve_*_access_index intrinsic call or not.</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### IsValidAIChain() {#a2b7437ca3cca05058e48bed2cf20cbdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BPFAbstractMemberAccess::IsValidAIChain (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * ParentType, uint32_t ParentAI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * ChildType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check whether the access index chain is valid.</p>


<p>We check here because there may be type casts between two access indexes. We want to ensure memory access still valid.</p>


<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### removePreserveAccessIndexIntrinsic() {#a01bc51aea19602d2b315557b37b0e6e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BPFAbstractMemberAccess::removePreserveAccessIndexIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### ResetMetadata() {#a886cf05f2e31cb9009975d868d4cb26e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BPFAbstractMemberAccess::ResetMetadata (struct <a href="/web-llvm/docs/api/structs/anonymous-bpfabstractmemberaccess-cpp-/bpfabstractmemberaccess/callinfo">CallInfo</a> &amp; CInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### traceAICall() {#ac28826587a3cbe8c1b799744af4d780d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BPFAbstractMemberAccess::traceAICall (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * Call, <a href="/web-llvm/docs/api/structs/anonymous-bpfabstractmemberaccess-cpp-/bpfabstractmemberaccess/callinfo">CallInfo</a> &amp; ParentInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### traceBitCast() {#aea7ac0f19817373958759a1d9cc2838e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BPFAbstractMemberAccess::traceBitCast (<a href="/web-llvm/docs/api/classes/llvm/bitcastinst">BitCastInst</a> * BitCast, <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * Parent, <a href="/web-llvm/docs/api/structs/anonymous-bpfabstractmemberaccess-cpp-/bpfabstractmemberaccess/callinfo">CallInfo</a> &amp; ParentInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### traceGEP() {#af4ed05fae393bfa56a53ca69b73d807a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BPFAbstractMemberAccess::traceGEP (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * GEP, <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * Parent, <a href="/web-llvm/docs/api/structs/anonymous-bpfabstractmemberaccess-cpp-/bpfabstractmemberaccess/callinfo">CallInfo</a> &amp; ParentInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### transformGEPChain() {#acd086b776bf3592077bd431c856edf0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BPFAbstractMemberAccess::transformGEPChain (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * Call, <a href="/web-llvm/docs/api/structs/anonymous-bpfabstractmemberaccess-cpp-/bpfabstractmemberaccess/callinfo">CallInfo</a> &amp; CInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Call/Kind is the base preserve_*_access_index() call.</p>


<p>Attempts to do transformation to a chain of relocable GEPs.</p>


<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AIChain {#a389808253755ef8857caeef6f5318213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;CallInst *, std::pair&lt;CallInst *, CallInfo&gt; &gt; anonymous{BPFAbstractMemberAccess.cpp}::BPFAbstractMemberAccess::AIChain</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### AnonRecords {#a1b7819948b8625b301987229dcf0c39d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;DICompositeType *, DIDerivedType *&gt; anonymous{BPFAbstractMemberAccess.cpp}::BPFAbstractMemberAccess::AnonRecords</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### BaseAICalls {#a0717cdffc9bf497b8afe8ed833863bdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;CallInst *, CallInfo&gt; anonymous{BPFAbstractMemberAccess.cpp}::BPFAbstractMemberAccess::BaseAICalls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### DL {#a2970948bd4f6fd5a525819e1045c7284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout* anonymous{BPFAbstractMemberAccess.cpp}::BPFAbstractMemberAccess::DL = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### M {#a08f15a4b08e6d62df5717d6be3471cfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module* anonymous{BPFAbstractMemberAccess.cpp}::BPFAbstractMemberAccess::M = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

### TM {#ae319411eef47e4ad151f6ec198c7edb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetMachine* anonymous{BPFAbstractMemberAccess.cpp}::BPFAbstractMemberAccess::TM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### GEPGlobals {#ab1a47f8b2c87e8b9a0ff95e60b1380da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt; std::string, GlobalVariable * &gt; anonymous{BPFAbstractMemberAccess.cpp}::BPFAbstractMemberAccess::GEPGlobals</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
