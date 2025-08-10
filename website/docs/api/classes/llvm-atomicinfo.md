---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/atomicinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AtomicInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::AtomicInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">llvm/Frontend/Atomic/Atomic.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/atomicinfo">AtomicInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ea7a68c2719bfecbd0d5faa91e18a20">AtomicInfo</a> (IRBuilderBase *Builder, Type *Ty, uint64_t AtomicSizeInBits, uint64_t ValueSizeInBits, Align AtomicAlign, Align ValueAlign, bool UseLibcall)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d98c6eab5218f0f60dfa4ecbdd4bc4d">~AtomicInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff1e2bf0d0ed57b94d088c3fd16765cf">getAtomicAlignment</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a793a3c7a901e488f38175e19635d4c69">getAtomicSizeInBits</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0212e92929684a958c992db9a62c3fa8">getValueSizeInBits</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af07ae85c8434dc37b4e98effc215a6d8">shouldUseLibcall</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72e407abe152db528bd08b5085c5a24a">getAtomicTy</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c9497f34c36d59c799c39ccf1c48543">getAtomicPointer</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb7687cea7cdaa3c24a530d4270c1185">decorateWithTBAA</a> (Instruction *I)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bf5dcf0d3d351e98a115d86c0800158">CreateAlloca</a> (Type *Ty, const Twine &amp;Name) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0cd163c207daf5a6102bf0360fb4001">hasPadding</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab906464a67a9c2a25693e334679f0fbc">getLLVMContext</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b01f19f0c51a12ce5cfc45fa85ffde7">shouldCastToInt</a> (Type *ValTy, bool CmpXchg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a533a649b6b2b58c0705ba06f522598">EmitAtomicLoadOp</a> (AtomicOrdering AO, bool IsVolatile, bool CmpXchg=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad915c31dcf8d35cf0affa3f8f13a043b">EmitAtomicLibcall</a> (StringRef fnName, Type *ResultType, ArrayRef&lt; Value * &gt; Args)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af03ba86b5eeabd9ab0d8bb129933d9dc">getAtomicSizeValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85687b0be992ef172b4228ed69f5146a">EmitAtomicCompareExchangeLibcall</a> (Value *ExpectedVal, Value *DesiredVal, AtomicOrdering Success, AtomicOrdering Failure)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82a039c43dd6deabdfad356f8d53ba28">castToAtomicIntPointer</a> (Value *addr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba8ed90f2b02e66014ddbfbd0d046f6f">getAtomicAddressAsAtomicIntPointer</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6171686930f0c1f5e05cd860c378fcd9">EmitAtomicCompareExchangeOp</a> (Value *ExpectedVal, Value *DesiredVal, AtomicOrdering Success, AtomicOrdering Failure, bool IsVolatile=false, bool IsWeak=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eb01c3dac6f4fe25ccc05522f6df25f">EmitAtomicCompareExchange</a> (Value *ExpectedVal, Value *DesiredVal, AtomicOrdering Success, AtomicOrdering Failure, bool IsVolatile, bool IsWeak)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *, <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5df935e7c87e3e1dc8b3d7e1870ee1c9">EmitAtomicLoadLibcall</a> (AtomicOrdering AO)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c27291b548e72b9bf4343a22ed4083f">Builder</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4f20dbabd4a3ee01be6dfb21b0a4848">Ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa93515e53e90f7b9686dd6a38e28863c">AtomicSizeInBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaec286e960801b56b3f89ed3dce070ff">ValueSizeInBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00ccd578d316a8e3cfb74c9d9512fb18">AtomicAlign</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2ff9d9e30bcb377a2ade9341657ab22">ValueAlign</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19b0169936737092e5098af651e062b6">UseLibcall</a></td>
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


<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AtomicInfo() {#a9ea7a68c2719bfecbd0d5faa91e18a20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AtomicInfo::AtomicInfo (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> * Builder, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, uint64_t AtomicSizeInBits, uint64_t ValueSizeInBits, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> AtomicAlign, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ValueAlign, bool UseLibcall)</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>References <a href="#a00ccd578d316a8e3cfb74c9d9512fb18">AtomicAlign</a>, <a href="#aa93515e53e90f7b9686dd6a38e28863c">AtomicSizeInBits</a>, <a href="#a2c27291b548e72b9bf4343a22ed4083f">Builder</a>, <a href="#af4f20dbabd4a3ee01be6dfb21b0a4848">Ty</a>, <a href="#a19b0169936737092e5098af651e062b6">UseLibcall</a>, <a href="#ac2ff9d9e30bcb377a2ade9341657ab22">ValueAlign</a> and <a href="#aaec286e960801b56b3f89ed3dce070ff">ValueSizeInBits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AtomicInfo() {#a1d98c6eab5218f0f60dfa4ecbdd4bc4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::AtomicInfo::~AtomicInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### castToAtomicIntPointer() {#a82a039c43dd6deabdfad356f8d53ba28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::AtomicInfo::castToAtomicIntPointer (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * addr)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>Referenced by <a href="#aba8ed90f2b02e66014ddbfbd0d046f6f">getAtomicAddressAsAtomicIntPointer</a>.</p>

</div>
</div>

### CreateAlloca() {#a5bf5dcf0d3d351e98a115d86c0800158}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual AllocaInst * llvm::AtomicInfo::CreateAlloca (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>Reference <a href="#af4f20dbabd4a3ee01be6dfb21b0a4848">Ty</a>.</p>


<p>Referenced by <a href="#a5df935e7c87e3e1dc8b3d7e1870ee1c9">EmitAtomicLoadLibcall</a>.</p>

</div>
</div>

### decorateWithTBAA() {#acb7687cea7cdaa3c24a530d4270c1185}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::AtomicInfo::decorateWithTBAA (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a7a533a649b6b2b58c0705ba06f522598">EmitAtomicLoadOp</a>.</p>

</div>
</div>

### EmitAtomicCompareExchange() {#a3eb01c3dac6f4fe25ccc05522f6df25f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Value *, Value * &gt; AtomicInfo::EmitAtomicCompareExchange (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ExpectedVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * DesiredVal, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Success, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Failure, bool IsVolatile, bool IsWeak)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>, definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/atomic/atomic-cpp">Atomic.cpp</a>.</p>


<p>References <a href="#a85687b0be992ef172b4228ed69f5146a">EmitAtomicCompareExchangeLibcall</a>, <a href="#a6171686930f0c1f5e05cd860c378fcd9">EmitAtomicCompareExchangeOp</a>, <a href="#af07ae85c8434dc37b4e98effc215a6d8">shouldUseLibcall</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a>.</p>

</div>
</div>

### EmitAtomicCompareExchangeLibcall() {#a85687b0be992ef172b4228ed69f5146a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Value *, Value * &gt; AtomicInfo::EmitAtomicCompareExchangeLibcall (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ExpectedVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * DesiredVal, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Success, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Failure)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/atomic/atomic-cpp">Atomic.cpp</a>.</p>


<p>References <a href="#ad915c31dcf8d35cf0affa3f8f13a043b">EmitAtomicLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="#a7c9497f34c36d59c799c39ccf1c48543">getAtomicPointer</a>, <a href="#af03ba86b5eeabd9ab0d8bb129933d9dc">getAtomicSizeValue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a0154da1d06b29a1d5649607ae2dfc389">llvm::Constant::getIntegerValue</a>, <a href="#ab906464a67a9c2a25693e334679f0fbc">getLLVMContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a>.</p>


<p>Referenced by <a href="#a3eb01c3dac6f4fe25ccc05522f6df25f">EmitAtomicCompareExchange</a>.</p>

</div>
</div>

### EmitAtomicCompareExchangeOp() {#a6171686930f0c1f5e05cd860c378fcd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Value *, Value * &gt; AtomicInfo::EmitAtomicCompareExchangeOp (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ExpectedVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * DesiredVal, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Success, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Failure, bool IsVolatile=false, bool IsWeak=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/atomic/atomic-cpp">Atomic.cpp</a>.</p>


<p>References <a href="#a2c27291b548e72b9bf4343a22ed4083f">Builder</a>, <a href="#aba8ed90f2b02e66014ddbfbd0d046f6f">getAtomicAddressAsAtomicIntPointer</a>, <a href="#aff1e2bf0d0ed57b94d088c3fd16765cf">getAtomicAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a15caddcf5c9b41f2f15c2ec363589f6caf9706a2e196638078e8323bfd9ba17de">llvm::SyncScope::System</a>.</p>


<p>Referenced by <a href="#a3eb01c3dac6f4fe25ccc05522f6df25f">EmitAtomicCompareExchange</a>.</p>

</div>
</div>

### EmitAtomicLibcall() {#ad915c31dcf8d35cf0affa3f8f13a043b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * AtomicInfo::EmitAtomicLibcall (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> fnName, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ResultType, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/atomic/atomic-cpp">Atomic.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a59d23ba2e7eac46cbc6cd3086e013b49">llvm::AttrBuilder::addAttribute</a>, <a href="#a2c27291b548e72b9bf4343a22ed4083f">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">llvm::AttributeList::FunctionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a4ac0d01bf5ca24e679de53067c8f6a44">llvm::AttributeList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a85687b0be992ef172b4228ed69f5146a">EmitAtomicCompareExchangeLibcall</a>.</p>

</div>
</div>

### EmitAtomicLoadLibcall() {#a5df935e7c87e3e1dc8b3d7e1870ee1c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; LoadInst *, AllocaInst * &gt; AtomicInfo::EmitAtomicLoadLibcall (<a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> AO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/atomic/atomic-cpp">Atomic.cpp</a>.</p>


<p>References <a href="#a2c27291b548e72b9bf4343a22ed4083f">Builder</a>, <a href="#a5bf5dcf0d3d351e98a115d86c0800158">CreateAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="#a7c9497f34c36d59c799c39ccf1c48543">getAtomicPointer</a>, <a href="#a793a3c7a901e488f38175e19635d4c69">getAtomicSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a>, <a href="#ab906464a67a9c2a25693e334679f0fbc">getLLVMContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#af3bb24b322533dbe8a63c84b18568fe1">llvm::AllocaInst::setAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66e6f90f41f1ea69d5ee532384f0af4e">llvm::toCABI</a> and <a href="#af4f20dbabd4a3ee01be6dfb21b0a4848">Ty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a388d5a62753f4e7ff4b72e54c1233fbc">llvm::OpenMPIRBuilder::createAtomicRead</a>.</p>

</div>
</div>

### EmitAtomicLoadOp() {#a7a533a649b6b2b58c0705ba06f522598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AtomicInfo::EmitAtomicLoadOp (<a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> AO, bool IsVolatile, bool CmpXchg=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/atomic/atomic-cpp">Atomic.cpp</a>.</p>


<p>References <a href="#a00ccd578d316a8e3cfb74c9d9512fb18">AtomicAlign</a>, <a href="#aa93515e53e90f7b9686dd6a38e28863c">AtomicSizeInBits</a>, <a href="#a2c27291b548e72b9bf4343a22ed4083f">Builder</a>, <a href="#acb7687cea7cdaa3c24a530d4270c1185">decorateWithTBAA</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="#a7c9497f34c36d59c799c39ccf1c48543">getAtomicPointer</a>, <a href="#ab906464a67a9c2a25693e334679f0fbc">getLLVMContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="#a9b01f19f0c51a12ce5cfc45fa85ffde7">shouldCastToInt</a> and <a href="#af4f20dbabd4a3ee01be6dfb21b0a4848">Ty</a>.</p>

</div>
</div>

### getAtomicAddressAsAtomicIntPointer() {#aba8ed90f2b02e66014ddbfbd0d046f6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::AtomicInfo::getAtomicAddressAsAtomicIntPointer ()</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>References <a href="#a82a039c43dd6deabdfad356f8d53ba28">castToAtomicIntPointer</a> and <a href="#a7c9497f34c36d59c799c39ccf1c48543">getAtomicPointer</a>.</p>


<p>Referenced by <a href="#a6171686930f0c1f5e05cd860c378fcd9">EmitAtomicCompareExchangeOp</a>.</p>

</div>
</div>

### getAtomicAlignment() {#aff1e2bf0d0ed57b94d088c3fd16765cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::AtomicInfo::getAtomicAlignment ()</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>Reference <a href="#a00ccd578d316a8e3cfb74c9d9512fb18">AtomicAlign</a>.</p>


<p>Referenced by <a href="#a6171686930f0c1f5e05cd860c378fcd9">EmitAtomicCompareExchangeOp</a>.</p>

</div>
</div>

### getAtomicPointer() {#a7c9497f34c36d59c799c39ccf1c48543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Value * llvm::AtomicInfo::getAtomicPointer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>Referenced by <a href="#a85687b0be992ef172b4228ed69f5146a">EmitAtomicCompareExchangeLibcall</a>, <a href="#a5df935e7c87e3e1dc8b3d7e1870ee1c9">EmitAtomicLoadLibcall</a>, <a href="#a7a533a649b6b2b58c0705ba06f522598">EmitAtomicLoadOp</a> and <a href="#aba8ed90f2b02e66014ddbfbd0d046f6f">getAtomicAddressAsAtomicIntPointer</a>.</p>

</div>
</div>

### getAtomicSizeInBits() {#a793a3c7a901e488f38175e19635d4c69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AtomicInfo::getAtomicSizeInBits ()</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>Reference <a href="#aa93515e53e90f7b9686dd6a38e28863c">AtomicSizeInBits</a>.</p>


<p>Referenced by <a href="#a5df935e7c87e3e1dc8b3d7e1870ee1c9">EmitAtomicLoadLibcall</a>.</p>

</div>
</div>

### getAtomicSizeValue() {#af03ba86b5eeabd9ab0d8bb129933d9dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::AtomicInfo::getAtomicSizeValue ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>References <a href="#aa93515e53e90f7b9686dd6a38e28863c">AtomicSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a> and <a href="#ab906464a67a9c2a25693e334679f0fbc">getLLVMContext</a>.</p>


<p>Referenced by <a href="#a85687b0be992ef172b4228ed69f5146a">EmitAtomicCompareExchangeLibcall</a>.</p>

</div>
</div>

### getAtomicTy() {#a72e407abe152db528bd08b5085c5a24a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::AtomicInfo::getAtomicTy ()</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>Reference <a href="#af4f20dbabd4a3ee01be6dfb21b0a4848">Ty</a>.</p>

</div>
</div>

### getLLVMContext() {#ab906464a67a9c2a25693e334679f0fbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext &amp; llvm::AtomicInfo::getLLVMContext ()</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>Reference <a href="#a2c27291b548e72b9bf4343a22ed4083f">Builder</a>.</p>


<p>Referenced by <a href="#a85687b0be992ef172b4228ed69f5146a">EmitAtomicCompareExchangeLibcall</a>, <a href="#a5df935e7c87e3e1dc8b3d7e1870ee1c9">EmitAtomicLoadLibcall</a>, <a href="#a7a533a649b6b2b58c0705ba06f522598">EmitAtomicLoadOp</a> and <a href="#af03ba86b5eeabd9ab0d8bb129933d9dc">getAtomicSizeValue</a>.</p>

</div>
</div>

### getValueSizeInBits() {#a0212e92929684a958c992db9a62c3fa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AtomicInfo::getValueSizeInBits ()</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>Reference <a href="#aaec286e960801b56b3f89ed3dce070ff">ValueSizeInBits</a>.</p>

</div>
</div>

### hasPadding() {#aa0cd163c207daf5a6102bf0360fb4001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AtomicInfo::hasPadding ()</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>References <a href="#aa93515e53e90f7b9686dd6a38e28863c">AtomicSizeInBits</a> and <a href="#aaec286e960801b56b3f89ed3dce070ff">ValueSizeInBits</a>.</p>

</div>
</div>

### shouldCastToInt() {#a9b01f19f0c51a12ce5cfc45fa85ffde7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AtomicInfo::shouldCastToInt (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ValTy, bool CmpXchg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>, definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/atomic/atomic-cpp">Atomic.cpp</a>.</p>


<p>Referenced by <a href="#a7a533a649b6b2b58c0705ba06f522598">EmitAtomicLoadOp</a>.</p>

</div>
</div>

### shouldUseLibcall() {#af07ae85c8434dc37b4e98effc215a6d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AtomicInfo::shouldUseLibcall ()</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>Reference <a href="#a19b0169936737092e5098af651e062b6">UseLibcall</a>.</p>


<p>Referenced by <a href="#a3eb01c3dac6f4fe25ccc05522f6df25f">EmitAtomicCompareExchange</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AtomicAlign {#a00ccd578d316a8e3cfb74c9d9512fb18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::AtomicInfo::AtomicAlign</td>
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



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>Referenced by <a href="#a9ea7a68c2719bfecbd0d5faa91e18a20">AtomicInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/atomicinfo/#a55fdeba4e85100153b1078a53fe438c6">llvm::OpenMPIRBuilder::AtomicInfo::AtomicInfo</a>, <a href="#a7a533a649b6b2b58c0705ba06f522598">EmitAtomicLoadOp</a> and <a href="#aff1e2bf0d0ed57b94d088c3fd16765cf">getAtomicAlignment</a>.</p>

</div>
</div>

### AtomicSizeInBits {#aa93515e53e90f7b9686dd6a38e28863c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AtomicInfo::AtomicSizeInBits</td>
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



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>Referenced by <a href="#a9ea7a68c2719bfecbd0d5faa91e18a20">AtomicInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/atomicinfo/#a55fdeba4e85100153b1078a53fe438c6">llvm::OpenMPIRBuilder::AtomicInfo::AtomicInfo</a>, <a href="#a7a533a649b6b2b58c0705ba06f522598">EmitAtomicLoadOp</a>, <a href="#a793a3c7a901e488f38175e19635d4c69">getAtomicSizeInBits</a>, <a href="#af03ba86b5eeabd9ab0d8bb129933d9dc">getAtomicSizeValue</a> and <a href="#aa0cd163c207daf5a6102bf0360fb4001">hasPadding</a>.</p>

</div>
</div>

### Builder {#a2c27291b548e72b9bf4343a22ed4083f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRBuilderBase* llvm::AtomicInfo::Builder</td>
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



<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>Referenced by <a href="#a9ea7a68c2719bfecbd0d5faa91e18a20">AtomicInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/atomicinfo/#a55fdeba4e85100153b1078a53fe438c6">llvm::OpenMPIRBuilder::AtomicInfo::AtomicInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/atomicinfo/#a27eedf5da8f111fe29254e21d94ffaa1">llvm::OpenMPIRBuilder::AtomicInfo::CreateAlloca</a>, <a href="#a6171686930f0c1f5e05cd860c378fcd9">EmitAtomicCompareExchangeOp</a>, <a href="#ad915c31dcf8d35cf0affa3f8f13a043b">EmitAtomicLibcall</a>, <a href="#a5df935e7c87e3e1dc8b3d7e1870ee1c9">EmitAtomicLoadLibcall</a>, <a href="#a7a533a649b6b2b58c0705ba06f522598">EmitAtomicLoadOp</a> and <a href="#ab906464a67a9c2a25693e334679f0fbc">getLLVMContext</a>.</p>

</div>
</div>

### Ty {#af4f20dbabd4a3ee01be6dfb21b0a4848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::AtomicInfo::Ty</td>
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



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>Referenced by <a href="#a9ea7a68c2719bfecbd0d5faa91e18a20">AtomicInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/atomicinfo/#a55fdeba4e85100153b1078a53fe438c6">llvm::OpenMPIRBuilder::AtomicInfo::AtomicInfo</a>, <a href="#a5bf5dcf0d3d351e98a115d86c0800158">CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/atomicinfo/#a27eedf5da8f111fe29254e21d94ffaa1">llvm::OpenMPIRBuilder::AtomicInfo::CreateAlloca</a>, <a href="#a5df935e7c87e3e1dc8b3d7e1870ee1c9">EmitAtomicLoadLibcall</a>, <a href="#a7a533a649b6b2b58c0705ba06f522598">EmitAtomicLoadOp</a> and <a href="#a72e407abe152db528bd08b5085c5a24a">getAtomicTy</a>.</p>

</div>
</div>

### UseLibcall {#a19b0169936737092e5098af651e062b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AtomicInfo::UseLibcall</td>
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



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>Referenced by <a href="#a9ea7a68c2719bfecbd0d5faa91e18a20">AtomicInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/atomicinfo/#a55fdeba4e85100153b1078a53fe438c6">llvm::OpenMPIRBuilder::AtomicInfo::AtomicInfo</a> and <a href="#af07ae85c8434dc37b4e98effc215a6d8">shouldUseLibcall</a>.</p>

</div>
</div>

### ValueAlign {#ac2ff9d9e30bcb377a2ade9341657ab22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::AtomicInfo::ValueAlign</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>Referenced by <a href="#a9ea7a68c2719bfecbd0d5faa91e18a20">AtomicInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/atomicinfo/#a55fdeba4e85100153b1078a53fe438c6">llvm::OpenMPIRBuilder::AtomicInfo::AtomicInfo</a>.</p>

</div>
</div>

### ValueSizeInBits {#aaec286e960801b56b3f89ed3dce070ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AtomicInfo::ValueSizeInBits</td>
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



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a>.</p>


<p>Referenced by <a href="#a9ea7a68c2719bfecbd0d5faa91e18a20">AtomicInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/atomicinfo/#a55fdeba4e85100153b1078a53fe438c6">llvm::OpenMPIRBuilder::AtomicInfo::AtomicInfo</a>, <a href="#a0212e92929684a958c992db9a62c3fa8">getValueSizeInBits</a> and <a href="#aa0cd163c207daf5a6102bf0360fb4001">hasPadding</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/atomic/atomic-h">Atomic.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/atomic/atomic-cpp">Atomic.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
