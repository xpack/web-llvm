---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/passregistrationlistener
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PassRegistrationListener` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener">PassRegistrationListener</a> class - This class is meant to be derived from by clients that are interested in which passes get registered and unregistered at runtime (which can be because of the <a href="/web-llvm/docs/api/structs/llvm/registerpass">RegisterPass</a> constructors being run as the program starts up, or may be because a shared object just got loaded). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::PassRegistrationListener { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h">llvm/PassSupport.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-pass-cpp-/getcfgonlypasses">GetCFGOnlyPasses</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/passnameparser">PassNameParser</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84540e48b241ec1f639c4f4b0dedc564">PassRegistrationListener</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af76aa3080dba888ed2c33f0680240415">~PassRegistrationListener</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a175dbba44bcb01ba49201959a0cc75f1">passRegistered</a> (const PassInfo *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback functions - These functions are invoked whenever a pass is loaded or removed from the current executable. <a href="#a175dbba44bcb01ba49201959a0cc75f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb9dad021ab08bbb8c51576841ddc7bd">enumeratePasses</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>enumeratePasses - Iterate over the registered passes, calling the passEnumerate callback on each <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> object. <a href="#aeb9dad021ab08bbb8c51576841ddc7bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae47e4af8ebd9ffc7d028c01e2e9dee54">passEnumerate</a> (const PassInfo *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>passEnumerate - Callback function invoked when someone calls enumeratePasses on this <a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener">PassRegistrationListener</a> object. <a href="#ae47e4af8ebd9ffc7d028c01e2e9dee54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener">PassRegistrationListener</a> class - This class is meant to be derived from by clients that are interested in which passes get registered and unregistered at runtime (which can be because of the <a href="/web-llvm/docs/api/structs/llvm/registerpass">RegisterPass</a> constructors being run as the program starts up, or may be because a shared object just got loaded).</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h">PassSupport.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PassRegistrationListener() {#a84540e48b241ec1f639c4f4b0dedc564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PassRegistrationListener::PassRegistrationListener ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h">PassSupport.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~PassRegistrationListener() {#af76aa3080dba888ed2c33f0680240415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::PassRegistrationListener::~PassRegistrationListener ()</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h">PassSupport.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### enumeratePasses() {#aeb9dad021ab08bbb8c51576841ddc7bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassRegistrationListener::enumeratePasses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>enumeratePasses - Iterate over the registered passes, calling the passEnumerate callback on each <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> object.</p>

<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h">PassSupport.h</a>, definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passnameparser/#a95f04ab8aa6ec4545d05f70348706704">llvm::PassNameParser::initialize</a>.</p>

</div>
</div>

### passEnumerate() {#ae47e4af8ebd9ffc7d028c01e2e9dee54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::PassRegistrationListener::passEnumerate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> *)</td>
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

<p>passEnumerate - Callback function invoked when someone calls enumeratePasses on this <a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener">PassRegistrationListener</a> object.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h">PassSupport.h</a>.</p>

</div>
</div>

### passRegistered() {#a175dbba44bcb01ba49201959a0cc75f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::PassRegistrationListener::passRegistered (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> *)</td>
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

<p>Callback functions - These functions are invoked whenever a pass is loaded or removed from the current executable.</p>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h">PassSupport.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h">PassSupport.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
