---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/passinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PassInfo` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> class - An instance of this class exists for every pass known by the system, and can be obtained from a live <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> by calling its <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp/#a8fd5fd11f1d85fee7e28a197e915aa0d">getPassInfo()</a> method. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PassInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">llvm/PassInfo.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/registerpass">RegisterPass&lt;passName&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RegisterPass&lt;t&gt; template - This template class is used to notify the system that a <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> is available for use, and registers it into the internal database maintained by the <a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a>. <a href="/web-llvm/docs/api/structs/llvm/registerpass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3803d284215257f1a4c23823c5558da8">NormalCtor_t</a> = <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *(*)()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9120a17cdcf88826fb07b59bc7db1b20">PassInfo</a> (StringRef name, StringRef arg, const void *pi, NormalCtor_t normal, bool isCFGOnly, bool is_analysis)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> ctor - Do not call this directly, this should only be invoked through <a href="/web-llvm/docs/api/structs/llvm/registerpass">RegisterPass</a>. <a href="#a9120a17cdcf88826fb07b59bc7db1b20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a825ec7b3a452a54ee3e56971c4335bf5">PassInfo</a> (const PassInfo &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f196350062dbd33946efc2a359e6fec">operator=</a> (const PassInfo &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad724101068b8ea028579fc6051f66d09">getPassName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return the friendly name for the pass, never returns null <a href="#ad724101068b8ea028579fc6051f66d09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa87dd67a6b8cac7c29fc520f5475882e">getPassArgument</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassArgument - Return the command line option that may be passed to 'opt' that will cause this pass to be run. <a href="#aa87dd67a6b8cac7c29fc520f5475882e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa9af549f3d775035bdc272c1f35d632">getTypeInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getTypeInfo - Return the id object for the pass... TODO : Rename <a href="#afa9af549f3d775035bdc272c1f35d632">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1be404ffbece5f4349715b1871ec729c">isPassID</a> (const void *IDPtr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this PassID implements the specified <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> pointer. <a href="#a1be404ffbece5f4349715b1871ec729c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f599935d3a65631f812392f94bb5775">isAnalysis</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2cf0760dde346b2b4e9b4bf1dba0caa">isCFGOnlyPass</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isCFGOnlyPass - return true if this pass only looks at the CFG for the function. <a href="#af2cf0760dde346b2b4e9b4bf1dba0caa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3803d284215257f1a4c23823c5558da8">NormalCtor_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63416703d6141a1474e6334cab65a4f3">getNormalCtor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getNormalCtor - Return a pointer to a function, that when called, creates an instance of the pass and returns it. <a href="#a63416703d6141a1474e6334cab65a4f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8749ff81793f615b66449e8e19fd69a4">setNormalCtor</a> (NormalCtor_t Ctor)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ef9100efe3bf6e85f752bff9a14046">createPass</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#af9ef9100efe3bf6e85f752bff9a14046">createPass()</a> - <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> this method to create an instance of this pass. <a href="#af9ef9100efe3bf6e85f752bff9a14046">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39db534ec794a6b700651e2d6d78000b">PassName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86c829a0490e7679bcb94b5dc13537b9">PassArgument</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7bb745cd911ab2f72c68c525534f49a">PassID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b38cba81b11cb36fe4fb009c54e586e">IsCFGOnlyPass</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9e327eab96eeb8c0b0bd93885732aa4">IsAnalysis</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3803d284215257f1a4c23823c5558da8">NormalCtor_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5694f509d467ca83ecd6e2b26a551ab6">NormalCtor</a> = nullptr</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> class - An instance of this class exists for every pass known by the system, and can be obtained from a live <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> by calling its <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp/#a8fd5fd11f1d85fee7e28a197e915aa0d">getPassInfo()</a> method.</p>


<p>These objects are set up by the <a href="/web-llvm/docs/api/structs/llvm/registerpass">RegisterPass&lt;&gt;</a> template.</p>


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### NormalCtor\_t {#a3803d284215257f1a4c23823c5558da8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PassInfo::NormalCtor_t =  Pass* (*)()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PassInfo() {#a9120a17cdcf88826fb07b59bc7db1b20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PassInfo::PassInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> arg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * pi, <a href="#a3803d284215257f1a4c23823c5558da8">NormalCtor_t</a> normal, bool isCFGOnly, bool is_analysis)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> ctor - Do not call this directly, this should only be invoked through <a href="/web-llvm/docs/api/structs/llvm/registerpass">RegisterPass</a>.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>.</p>


<p>Referenced by <a href="#a1f196350062dbd33946efc2a359e6fec">operator=</a>, <a href="#a825ec7b3a452a54ee3e56971c4335bf5">PassInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/registerpass/#aee30bf48a272c4267cd3606e047aa3e8">llvm::RegisterPass&lt; passName &gt;::RegisterPass</a>.</p>

</div>
</div>

### PassInfo() {#a825ec7b3a452a54ee3e56971c4335bf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PassInfo::PassInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> &amp;)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>


<p>Reference <a href="#a9120a17cdcf88826fb07b59bc7db1b20">PassInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a1f196350062dbd33946efc2a359e6fec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassInfo &amp; llvm::PassInfo::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> &amp;)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>


<p>Reference <a href="#a9120a17cdcf88826fb07b59bc7db1b20">PassInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createPass() {#af9ef9100efe3bf6e85f752bff9a14046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass * llvm::PassInfo::createPass ()</td>
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

<p><a href="#af9ef9100efe3bf6e85f752bff9a14046">createPass()</a> - <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> this method to create an instance of this pass.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#ab7c7120f48a91e5972592b16ee7fd81b">llvm::PMDataManager::add</a> and <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a5fb719fc8062d116b93091d9c9addd43">llvm::PMTopLevelManager::schedulePass</a>.</p>

</div>
</div>

### getNormalCtor() {#a63416703d6141a1474e6334cab65a4f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NormalCtor_t llvm::PassInfo::getNormalCtor ()</td>
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

<p>getNormalCtor - Return a pointer to a function, that when called, creates an instance of the pass and returns it.</p>


<p>This pointer may be null if there is no default constructor for the pass.</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>

</div>
</div>

### getPassArgument() {#aa87dd67a6b8cac7c29fc520f5475882e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::PassInfo::getPassArgument ()</td>
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

<p>getPassArgument - Return the command line option that may be passed to 'opt' that will cause this pass to be run.</p>


<p>This will return null if there is no argument.</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a1c6b1d7b3e51a4eeefbf90b25edaf708">llvm::PassRegistry::registerPass</a> and <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a5fb719fc8062d116b93091d9c9addd43">llvm::PMTopLevelManager::schedulePass</a>.</p>

</div>
</div>

### getPassName() {#ad724101068b8ea028579fc6051f66d09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::PassInfo::getPassName ()</td>
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

<p>getPassName - Return the friendly name for the pass, never returns null</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>

</div>
</div>

### getTypeInfo() {#afa9af549f3d775035bdc272c1f35d632}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const void * llvm::PassInfo::getTypeInfo ()</td>
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

<p>getTypeInfo - Return the id object for the pass... TODO : Rename</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp/#a3c5faae50cf1ccc5bf0d1936557030ec">getPassIDFromName</a> and <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a1c6b1d7b3e51a4eeefbf90b25edaf708">llvm::PassRegistry::registerPass</a>.</p>

</div>
</div>

### isAnalysis() {#a6f599935d3a65631f812392f94bb5775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PassInfo::isAnalysis ()</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a452b3946fae687fe6ab129970b5f9c75">anonymous{LegacyPassManager.cpp}::MPPassManager::addLowerLevelRequiredPass</a> and <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a5fb719fc8062d116b93091d9c9addd43">llvm::PMTopLevelManager::schedulePass</a>.</p>

</div>
</div>

### isCFGOnlyPass() {#af2cf0760dde346b2b4e9b4bf1dba0caa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PassInfo::isCFGOnlyPass ()</td>
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

<p>isCFGOnlyPass - return true if this pass only looks at the CFG for the function.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>

</div>
</div>

### isPassID() {#a1be404ffbece5f4349715b1871ec729c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PassInfo::isPassID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * IDPtr)</td>
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

<p>Return true if this PassID implements the specified <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> pointer.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>

</div>
</div>

### setNormalCtor() {#a8749ff81793f615b66449e8e19fd69a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassInfo::setNormalCtor (<a href="#a3803d284215257f1a4c23823c5558da8">NormalCtor_t</a> Ctor)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IsAnalysis {#ad9e327eab96eeb8c0b0bd93885732aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::PassInfo::IsAnalysis</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>

</div>
</div>

### IsCFGOnlyPass {#a8b38cba81b11cb36fe4fb009c54e586e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::PassInfo::IsCFGOnlyPass = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>

</div>
</div>

### NormalCtor {#a5694f509d467ca83ecd6e2b26a551ab6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NormalCtor_t llvm::PassInfo::NormalCtor = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>

</div>
</div>

### PassArgument {#a86c829a0490e7679bcb94b5dc13537b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::PassInfo::PassArgument</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>

</div>
</div>

### PassID {#ad7bb745cd911ab2f72c68c525534f49a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const void* llvm::PassInfo::PassID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>

</div>
</div>

### PassName {#a39db534ec794a6b700651e2d6d78000b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::PassInfo::PassName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">PassInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
