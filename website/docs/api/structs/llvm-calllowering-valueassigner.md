---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/calllowering/valueassigner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ValueAssigner` Struct

<p><a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> handling is mostly uniform between the four places that make these decisions: function formal arguments, call instruction args, call instruction returns and function returns. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::CallLowering::ValueAssigner { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">llvm/CodeGen/GlobalISel/CallLowering.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvalueassigner">IncomingValueAssigner</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/calllowering/outgoingvalueassigner">OutgoingValueAssigner</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a356248ea0464de7b7fa769e23aa0690c">ValueAssigner</a> (bool IsIncoming, CCAssignFn *AssignFn_, CCAssignFn *AssignFnVarArg_=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf9cfe980b973046e1f6c0c50ca649e3">~ValueAssigner</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28e4c26abcb3bdc9eb7417d1a50fa09b">isIncomingArgumentHandler</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the handler is dealing with incoming arguments, i.e. <a href="#a28e4c26abcb3bdc9eb7417d1a50fa09b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1caf846fc79aa5976216a32724c9e10">assignArg</a> (unsigned ValNo, EVT OrigVT, MVT ValVT, MVT LocVT, CCValAssign::LocInfo LocInfo, const ArgInfo &amp;Info, ISD::ArgFlagsTy Flags, CCState &amp;State)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrap call to (typically tablegenerated <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a>). <a href="#ab1caf846fc79aa5976216a32724c9e10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a0f6ac9de105b73856d1312951be8f6">getAssignFn</a> (bool IsVarArg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select the appropriate assignment function depending on whether this is a variadic call. <a href="#a0a0f6ac9de105b73856d1312951be8f6">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4934d684655675f163edd0da344f9b1d">anchor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27f3aed59700f4ccc3924ea6e6eb1f34">AssignFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assignment function to use for a general call. <a href="#a27f3aed59700f4ccc3924ea6e6eb1f34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a758ece099367984b17faa8d140b2b787">AssignFnVarArg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assignment function to use for a variadic call. <a href="#a758ece099367984b17faa8d140b2b787">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad737172e1e2f85c9f819c2e4e8b364b7">StackSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The size of the currently allocated portion of the stack. <a href="#ad737172e1e2f85c9f819c2e4e8b364b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac59036306cbb3832740ef0aed58e8d53">IsIncomingArgumentHandler</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> handling is mostly uniform between the four places that make these decisions: function formal arguments, call instruction args, call instruction returns and function returns.</p>


<p>However, once a decision has been made on where an argument should go, exactly what happens can vary slightly. This class abstracts the differences.</p>


<p><a href="/web-llvm/docs/api/structs/llvm/calllowering/valueassigner">ValueAssigner</a> should not depend on any specific function state, and only determine the types and locations for arguments.</p>


<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ValueAssigner() {#a356248ea0464de7b7fa769e23aa0690c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CallLowering::ValueAssigner::ValueAssigner (bool IsIncoming, <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> * AssignFn_, <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> * AssignFnVarArg_=nullptr)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>References <a href="#a27f3aed59700f4ccc3924ea6e6eb1f34">AssignFn</a> and <a href="#a758ece099367984b17faa8d140b2b787">AssignFnVarArg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvalueassigner/#a13b43a063ba0bd7c472e835dc34f0a95">llvm::CallLowering::IncomingValueAssigner::IncomingValueAssigner</a> and <a href="/web-llvm/docs/api/structs/llvm/calllowering/outgoingvalueassigner/#a2189160214171b9862ade30c943b7a8e">llvm::CallLowering::OutgoingValueAssigner::OutgoingValueAssigner</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ValueAssigner() {#adf9cfe980b973046e1f6c0c50ca649e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::CallLowering::ValueAssigner::~ValueAssigner ()</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assignArg() {#ab1caf846fc79aa5976216a32724c9e10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::CallLowering::ValueAssigner::assignArg (unsigned ValNo, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> OrigVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> LocInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo">ArgInfo</a> &amp; Info, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wrap call to (typically tablegenerated <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a>).</p>


<p>This may be overridden to track additional state information as arguments are assigned or apply target specific hacks around the legacy infrastructure.</p>


<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>References <a href="#a0a0f6ac9de105b73856d1312951be8f6">getAssignFn</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a> and <a href="#ad737172e1e2f85c9f819c2e4e8b364b7">StackSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-mipscalllowering-cpp-/mipsincomingvalueassigner/#af7adc7bea2e74a6a1b49c5543c53c119">anonymous{MipsCallLowering.cpp}::MipsIncomingValueAssigner::assignArg</a>, <a href="/web-llvm/docs/api/structs/anonymous-mipscalllowering-cpp-/mipsoutgoingvalueassigner/#a3df6a7e63762376a088acec41d1f3623">anonymous{MipsCallLowering.cpp}::MipsOutgoingValueAssigner::assignArg</a> and <a href="/web-llvm/docs/api/classes/llvm/calllowering/#ac6db7ce806dd7cbdce7f3c1b06dcd54e">llvm::CallLowering::determineAssignments</a>.</p>

</div>
</div>

### getAssignFn() {#a0a0f6ac9de105b73856d1312951be8f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCAssignFn * llvm::CallLowering::ValueAssigner::getAssignFn (bool IsVarArg)</td>
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

<p>Select the appropriate assignment function depending on whether this is a variadic call.</p>

<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>References <a href="#a27f3aed59700f4ccc3924ea6e6eb1f34">AssignFn</a> and <a href="#a758ece099367984b17faa8d140b2b787">AssignFnVarArg</a>.</p>


<p>Referenced by <a href="#ab1caf846fc79aa5976216a32724c9e10">assignArg</a>.</p>

</div>
</div>

### isIncomingArgumentHandler() {#a28e4c26abcb3bdc9eb7417d1a50fa09b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallLowering::ValueAssigner::isIncomingArgumentHandler ()</td>
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

<p>Returns true if the handler is dealing with incoming arguments, i.e.</p>


<p>those that move values from some physical location to vregs.</p>


<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a4934d684655675f163edd0da344f9b1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallLowering::ValueAssigner::anchor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>, definition at line 1340 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp">CallLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AssignFn {#a27f3aed59700f4ccc3924ea6e6eb1f34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCAssignFn* llvm::CallLowering::ValueAssigner::AssignFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assignment function to use for a general call.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/aarch64outgoingvalueassigner/#a4e31012ae290be156077d90c19f46432">anonymous{AArch64CallLowering.cpp}::AArch64OutgoingValueAssigner::assignArg</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86outgoingvalueassigner/#a9526e056885df10409e93a5fa871bad1">anonymous{X86CallLowering.cpp}::X86OutgoingValueAssigner::assignArg</a>, <a href="#a0a0f6ac9de105b73856d1312951be8f6">getAssignFn</a> and <a href="#a356248ea0464de7b7fa769e23aa0690c">ValueAssigner</a>.</p>

</div>
</div>

### AssignFnVarArg {#a758ece099367984b17faa8d140b2b787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCAssignFn* llvm::CallLowering::ValueAssigner::AssignFnVarArg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assignment function to use for a variadic call.</p>


<p>This is usually the same as AssignFn on most targets.</p>


<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/aarch64outgoingvalueassigner/#a4e31012ae290be156077d90c19f46432">anonymous{AArch64CallLowering.cpp}::AArch64OutgoingValueAssigner::assignArg</a>, <a href="#a0a0f6ac9de105b73856d1312951be8f6">getAssignFn</a> and <a href="#a356248ea0464de7b7fa769e23aa0690c">ValueAssigner</a>.</p>

</div>
</div>

### StackSize {#ad737172e1e2f85c9f819c2e4e8b364b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::CallLowering::ValueAssigner::StackSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The size of the currently allocated portion of the stack.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/aarch64outgoingvalueassigner/#a4e31012ae290be156077d90c19f46432">anonymous{AArch64CallLowering.cpp}::AArch64OutgoingValueAssigner::assignArg</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvalueassigner/#aa00177ed35b852b9cff4b22d156ad7f2">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueAssigner::assignArg</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvalueassigner/#a61e12e1e3da12382d22ca82cc6156ac0">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueAssigner::assignArg</a>, <a href="#ab1caf846fc79aa5976216a32724c9e10">assignArg</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#af3fdfad8a2951ca4c86fd64560c550a7">llvm::ARMCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kcalllowering/#a2c714d045da3eaad01dfd893048e9a0c">llvm::M68kCallLowering::lowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#acf79ac9988d00b2ded8a68907a1569e4">llvm::AMDGPUCallLowering::lowerFormalArguments</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IsIncomingArgumentHandler {#ac59036306cbb3832740ef0aed58e8d53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::CallLowering::ValueAssigner::IsIncomingArgumentHandler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp">CallLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
