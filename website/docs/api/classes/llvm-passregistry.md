---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/passregistry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PassRegistry` Class

<p><a href="/web-llvm/docs/api/classes/llvm/passregistry">PassRegistry</a> - This class manages the registration and intitialization of the pass subsystem as application startup, and assists the <a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a> in resolving pass dependencies. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PassRegistry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">llvm/PassRegistry.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d7a3da391ee50729de306978ce1807c">MapType</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PassInfoMap - Keep track of the <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> object for each registered pass. <a href="#a9d7a3da391ee50729de306978ce1807c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83e0a6e01ec5805061f1371037a2d248">StringMapType</a> = <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92455815852331744ed1967790e461b2">PassRegistry</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb90fd97bbccc952c3ccb177395374ab">~PassRegistry</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58f089b4fc400d1bfb6f2e6d21a00dbb">getPassInfo</a> (const void *TI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassInfo - Look up a pass' corresponding <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a>, indexed by the pass' type identifier (&amp;MyPass::ID). <a href="#a58f089b4fc400d1bfb6f2e6d21a00dbb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd2db1155bb77bddf0d45bfdc6c27526">getPassInfo</a> (StringRef Arg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassInfo - Look up a pass' corresponding <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a>, indexed by the pass' argument string. <a href="#afd2db1155bb77bddf0d45bfdc6c27526">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c6b1d7b3e51a4eeefbf90b25edaf708">registerPass</a> (const PassInfo &amp;PI, bool ShouldFree=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>registerPass - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a pass (by means of its <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a>) with the registry. <a href="#a1c6b1d7b3e51a4eeefbf90b25edaf708">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2069e3f991ab4ff213c1ca75bc52837e">enumerateWith</a> (PassRegistrationListener *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>enumerateWith - Enumerate the registered passes, calling the provided <a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener">PassRegistrationListener</a>'s passEnumerate() callback on each of them. <a href="#a2069e3f991ab4ff213c1ca75bc52837e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a107c9a9b3248919e9584185449e2c7d8">addRegistrationListener</a> (PassRegistrationListener *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addRegistrationListener - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> the given <a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener">PassRegistrationListener</a> to receive passRegistered() callbacks whenever a new pass is registered. <a href="#a107c9a9b3248919e9584185449e2c7d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1adebe5cc926e41d4f52bbee145529b9">removeRegistrationListener</a> (PassRegistrationListener *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeRegistrationListener - Unregister a <a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener">PassRegistrationListener</a> so that it no longer receives passRegistered() callbacks. <a href="#a1adebe5cc926e41d4f52bbee145529b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/smartrwmutex">sys::SmartRWMutex</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3394634116c8ec7fd4ef103496e85511">Lock</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">MapType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a270bcceabaa3eb9b122babd17ad08933">PassInfoMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMapType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a266fa22d69cddded44e7a84ce91fc547">PassInfoStringMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbfe63edb201b018b37ab5beaabadbfc">ToFree</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener">PassRegistrationListener</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace87907231c4889ec065cec7e128e442">Listeners</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/passregistry">PassRegistry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05a729900b76c89e808c6c3094921b2f">getPassRegistry</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassRegistry - Access the global registry object, which is automatically initialized at application launch and destroyed by llvm_shutdown. <a href="#a05a729900b76c89e808c6c3094921b2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/passregistry">PassRegistry</a> - This class manages the registration and intitialization of the pass subsystem as application startup, and assists the <a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a> in resolving pass dependencies.</p>


<p>NOTE: <a href="/web-llvm/docs/api/classes/llvm/passregistry">PassRegistry</a> is NOT thread-safe. If you want to use LLVM on multiple threads simultaneously, you will need to use a separate <a href="/web-llvm/docs/api/classes/llvm/passregistry">PassRegistry</a> on each thread.</p>


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">PassRegistry.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### MapType {#a9d7a3da391ee50729de306978ce1807c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PassRegistry::MapType =  DenseMap&lt;const void *, const PassInfo *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PassInfoMap - Keep track of the <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> object for each registered pass.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">PassRegistry.h</a>.</p>

</div>
</div>

### StringMapType {#a83e0a6e01ec5805061f1371037a2d248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PassRegistry::StringMapType =  StringMap&lt;const PassInfo *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">PassRegistry.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PassRegistry() {#a92455815852331744ed1967790e461b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PassRegistry::PassRegistry ()</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">PassRegistry.h</a>.</p>


<p>Referenced by <a href="#a05a729900b76c89e808c6c3094921b2f">getPassRegistry</a> and <a href="#abb90fd97bbccc952c3ccb177395374ab">~PassRegistry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~PassRegistry() {#abb90fd97bbccc952c3ccb177395374ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassRegistry::~PassRegistry ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">PassRegistry.h</a>.</p>


<p>Reference <a href="#a92455815852331744ed1967790e461b2">PassRegistry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addRegistrationListener() {#a107c9a9b3248919e9584185449e2c7d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassRegistry::addRegistrationListener (<a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener">PassRegistrationListener</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addRegistrationListener - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> the given <a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener">PassRegistrationListener</a> to receive passRegistered() callbacks whenever a new pass is registered.</p>

<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">PassRegistry.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passregistry-cpp">PassRegistry.cpp</a>.</p>

</div>
</div>

### enumerateWith() {#a2069e3f991ab4ff213c1ca75bc52837e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassRegistry::enumerateWith (<a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener">PassRegistrationListener</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>enumerateWith - Enumerate the registered passes, calling the provided <a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener">PassRegistrationListener</a>'s passEnumerate() callback on each of them.</p>

<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">PassRegistry.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passregistry-cpp">PassRegistry.cpp</a>.</p>

</div>
</div>

### getPassInfo() {#a58f089b4fc400d1bfb6f2e6d21a00dbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PassInfo * PassRegistry::getPassInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * TI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getPassInfo - Look up a pass' corresponding <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a>, indexed by the pass' type identifier (&amp;MyPass::ID).</p>

<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">PassRegistry.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passregistry-cpp">PassRegistry.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a43fed8d1dfacc9362ed5b08f841782f8">llvm::PMTopLevelManager::findAnalysisPassInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp/#a8fd5fd11f1d85fee7e28a197e915aa0d">getPassInfo</a>.</p>

</div>
</div>

### getPassInfo() {#afd2db1155bb77bddf0d45bfdc6c27526}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PassInfo * PassRegistry::getPassInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Arg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getPassInfo - Look up a pass' corresponding <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a>, indexed by the pass' argument string.</p>

<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">PassRegistry.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passregistry-cpp">PassRegistry.cpp</a>.</p>

</div>
</div>

### registerPass() {#a1c6b1d7b3e51a4eeefbf90b25edaf708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassRegistry::registerPass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> &amp; PI, bool ShouldFree=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>registerPass - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a pass (by means of its <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a>) with the registry.</p>


<p>Required in order to use the pass with a <a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a>.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">PassRegistry.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passregistry-cpp">PassRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/passinfo/#aa87dd67a6b8cac7c29fc520f5475882e">llvm::PassInfo::getPassArgument</a> and <a href="/web-llvm/docs/api/classes/llvm/passinfo/#afa9af549f3d775035bdc272c1f35d632">llvm::PassInfo::getTypeInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/registerpass/#aee30bf48a272c4267cd3606e047aa3e8">llvm::RegisterPass&lt; passName &gt;::RegisterPass</a>.</p>

</div>
</div>

### removeRegistrationListener() {#a1adebe5cc926e41d4f52bbee145529b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassRegistry::removeRegistrationListener (<a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener">PassRegistrationListener</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removeRegistrationListener - Unregister a <a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener">PassRegistrationListener</a> so that it no longer receives passRegistered() callbacks.</p>

<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">PassRegistry.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passregistry-cpp">PassRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Listeners {#ace87907231c4889ec065cec7e128e442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;PassRegistrationListener *&gt; llvm::PassRegistry::Listeners</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">PassRegistry.h</a>.</p>

</div>
</div>

### Lock {#a3394634116c8ec7fd4ef103496e85511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::SmartRWMutex&lt;true&gt; llvm::PassRegistry::Lock</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">PassRegistry.h</a>.</p>

</div>
</div>

### PassInfoMap {#a270bcceabaa3eb9b122babd17ad08933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapType llvm::PassRegistry::PassInfoMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">PassRegistry.h</a>.</p>

</div>
</div>

### PassInfoStringMap {#a266fa22d69cddded44e7a84ce91fc547}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMapType llvm::PassRegistry::PassInfoStringMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">PassRegistry.h</a>.</p>

</div>
</div>

### ToFree {#abbfe63edb201b018b37ab5beaabadbfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;const PassInfo&gt; &gt; llvm::PassRegistry::ToFree</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">PassRegistry.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getPassRegistry() {#a05a729900b76c89e808c6c3094921b2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassRegistry * PassRegistry::getPassRegistry ()</td>
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

<p>getPassRegistry - Access the global registry object, which is automatically initialized at application launch and destroyed by llvm_shutdown.</p>

<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">PassRegistry.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passregistry-cpp">PassRegistry.cpp</a>.</p>


<p>Reference <a href="#a92455815852331744ed1967790e461b2">PassRegistry</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64a53fix835769-cpp-/aarch64a53fix835769/#ac52fc16d4ed2d6d6cda4146d91c0b539">anonymous{AArch64A53Fix835769.cpp}::AArch64A53Fix835769::AArch64A53Fix835769</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64a57fploadbalancing-cpp-/aarch64a57fploadbalancing/#ac9d2d9de6ef4e622f3ccd8e458f79c75">anonymous{AArch64A57FPLoadBalancing.cpp}::AArch64A57FPLoadBalancing::AArch64A57FPLoadBalancing</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64advsimdscalarpass-cpp-/aarch64advsimdscalar/#abc76d508c783676bf522fbbd8d1d855b">anonymous{AArch64AdvSIMDScalarPass.cpp}::AArch64AdvSIMDScalar::AArch64AdvSIMDScalar</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a8ed0ce49492f441faef4ff3eda95feef">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::AArch64Arm64ECCallLowering</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64compressjumptables-cpp-/aarch64compressjumptables/#a8571317da954746ede4febff44c04d51">anonymous{AArch64CompressJumpTables.cpp}::AArch64CompressJumpTables::AArch64CompressJumpTables</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64condbrtuning-cpp-/aarch64condbrtuning/#ab993c5e5a9d4f1d58fc1a3837521d845">anonymous{AArch64CondBrTuning.cpp}::AArch64CondBrTuning::AArch64CondBrTuning</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionalcompares-cpp-/aarch64conditionalcompares/#a8e9494d7e3bf515011c0961efe205868">anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::AArch64ConditionalCompares</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#a4720f92c0f82e1ad3c747f6c5d0648e4">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::AArch64ConditionOptimizer</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64deadregisterdefinitionspass-cpp-/aarch64deadregisterdefinitions/#a613a0335d9bd2e675b19fc9c6d0c2ae4">anonymous{AArch64DeadRegisterDefinitionsPass.cpp}::AArch64DeadRegisterDefinitions::AArch64DeadRegisterDefinitions</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64expandpseudoinsts-cpp-/aarch64expandpseudo/#a35b8b827667d6c17bfa61671bc767917">anonymous{AArch64ExpandPseudoInsts.cpp}::AArch64ExpandPseudo::AArch64ExpandPseudo</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#ab95fa8e00277362a0918c3b6e782ba63">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::AArch64LoadStoreOpt</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64lowerhomogeneousprologepilog-cpp-/aarch64lowerhomogeneousprologepilog/#adc2672f63aad171342014dffec3b97ae">anonymous{AArch64LowerHomogeneousPrologEpilog.cpp}::AArch64LowerHomogeneousPrologEpilog::AArch64LowerHomogeneousPrologEpilog</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#aa8f8caae338ea16cca352c1597f381df">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::AArch64MIPeepholeOpt</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64postcoalescerpass-cpp-/aarch64postcoalescer/#a6ec94d1cad16972fe68cc95cb356651e">anonymous{AArch64PostCoalescerPass.cpp}::AArch64PostCoalescer::AArch64PostCoalescer</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64postselectoptimize-cpp-/aarch64postselectoptimize/#a9bb0abcf72dd53c0896e0cf6d31bd829">anonymous{AArch64PostSelectOptimize.cpp}::AArch64PostSelectOptimize::AArch64PostSelectOptimize</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64promoteconstant-cpp-/aarch64promoteconstant/#a332e5f6f2291c407f086104317716727">anonymous{AArch64PromoteConstant.cpp}::AArch64PromoteConstant::AArch64PromoteConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64redundantcopyelimination-cpp-/aarch64redundantcopyelimination/#a3f6ddb5e7da894ad9caee4f4f650ceb6">anonymous{AArch64RedundantCopyElimination.cpp}::AArch64RedundantCopyElimination::AArch64RedundantCopyElimination</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#aaaa4405aa609fc3cebea46e423a471c1">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::AArch64SIMDInstrOpt</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64speculationhardening-cpp-/aarch64speculationhardening/#a641f90971fd86de8eb2138b4de0819e1">anonymous{AArch64SpeculationHardening.cpp}::AArch64SpeculationHardening::AArch64SpeculationHardening</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a977ae62624a122f4098b79d247473509">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::AArch64StackTagging</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktaggingprera-cpp-/aarch64stacktaggingprera/#a80605317d8259420beae268d3af34713">anonymous{AArch64StackTaggingPreRA.cpp}::AArch64StackTaggingPreRA::AArch64StackTaggingPreRA</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64storepairsuppress-cpp-/aarch64storepairsuppress/#a995d74eac8e48fc3500539293e418dbb">anonymous{AArch64StorePairSuppress.cpp}::AArch64StorePairSuppress::AArch64StorePairSuppress</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresultswrapperpass/#ad140b4039c874106ee187d3b791bb3e4">llvm::AAResultsWrapperPass::AAResultsWrapperPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppctargetmachine-cpp-/ppcpassconfig/#ab05a6b644262de692a1b8917d9eda863">anonymous{PPCTargetMachine.cpp}::PPCPassConfig::addPreRegAlloc</a>, <a href="/web-llvm/docs/api/structs/anonymous-alwaysinliner-cpp-/alwaysinlinerlegacypass/#a79388c6b1888fd0ff6894d9224c2a896">anonymous{AlwaysInliner.cpp}::AlwaysInlinerLegacyPass::AlwaysInlinerLegacyPass</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuaawrapperpass/#aca3c1f380407cc6c17ccc971ec568f31">llvm::AMDGPUAAWrapperPass::AMDGPUAAWrapperPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepare/#aaa9aff825377ac1212a4199212830454">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepare::AMDGPUCodeGenPrepare</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/amdgpuglobaliseldivergencelowering/#a3ddde021bfb380d8c1c878a3855818fb">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::AMDGPUGlobalISelDivergenceLowering::AMDGPUGlobalISelDivergenceLowering</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/amdgpulowerbufferfatpointers/#aa9edf8aedc2f0167dbf3e9e475a86a99">anonymous{AMDGPULowerBufferFatPointers.cpp}::AMDGPULowerBufferFatPointers::AMDGPULowerBufferFatPointers</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermoduleldslegacy/#a5a1002d207ccfd4b08378258e5720962">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDSLegacy::AMDGPULowerModuleLDSLegacy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumarklastscratchload-cpp-/amdgpumarklastscratchload/#a1e6069bb345f6b0682743565052ccfdb">anonymous{AMDGPUMarkLastScratchLoad.cpp}::AMDGPUMarkLastScratchLoad::AMDGPUMarkLastScratchLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuprintfruntimebinding-cpp-/amdgpuprintfruntimebinding/#a2db1aa71153eccba89849ffab810b47a">anonymous{AMDGPUPrintfRuntimeBinding.cpp}::AMDGPUPrintfRuntimeBinding::AMDGPUPrintfRuntimeBinding</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregbanklegalize-cpp-/amdgpuregbanklegalize/#ae1a94473e2889e7f8f5c9fd262c50bc9">anonymous{AMDGPURegBankLegalize.cpp}::AMDGPURegBankLegalize::AMDGPURegBankLegalize</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregbankselect-cpp-/amdgpuregbankselect/#ae5cf5a5258b519a546bf3dfa4ef5b770">anonymous{AMDGPURegBankSelect.cpp}::AMDGPURegBankSelect::AMDGPURegBankSelect</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpureservewwmregs-cpp-/amdgpureservewwmregs/#a627b2220409f49021df723c12cf9396c">anonymous{AMDGPUReserveWWMRegs.cpp}::AMDGPUReserveWWMRegs::AMDGPUReserveWWMRegs</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteundefforphi-cpp-/amdgpurewriteundefforphilegacy/#ab4364a3e329320d216bc2b5666e6ad3f">anonymous{AMDGPURewriteUndefForPHI.cpp}::AMDGPURewriteUndefForPHILegacy::AMDGPURewriteUndefForPHILegacy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerldslegacy/#af64ddca703faac9c20e9baca773051b6">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDSLegacy::AMDGPUSwLowerLDSLegacy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodes/#afb18db9d69a1fce77837747e74e4f236">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodes::AMDGPUUnifyDivergentExitNodes</a>, <a href="/web-llvm/docs/api/classes/anonymous-arcbranchfinalize-cpp-/arcbranchfinalize/#a43dcb6d7e952f336f345457cc642699b">anonymous{ARCBranchFinalize.cpp}::ARCBranchFinalize::ARCBranchFinalize</a>, <a href="/web-llvm/docs/api/classes/anonymous-armfixcortexa57aes1742098pass-cpp-/armfixcortexa57aes1742098/#ad491cdbff0c7d5aa100ac2aec66eb173">anonymous{ARMFixCortexA57AES1742098Pass.cpp}::ARMFixCortexA57AES1742098::ARMFixCortexA57AES1742098</a>, <a href="/web-llvm/docs/api/classes/anonymous-armslshardening-cpp-/armslshardening/#a5b2ab303265a35c700caf7241ae3991c">anonymous{ARMSLSHardening.cpp}::ARMSLSHardening::ARMSLSHardening</a>, <a href="/web-llvm/docs/api/classes/llvm/assumptioncachetracker/#af6f2b5ca7e621ccfdda6462a700f2865">llvm::AssumptionCacheTracker::AssumptionCacheTracker</a>, <a href="/web-llvm/docs/api/classes/anonymous-atomicexpandpass-cpp-/atomicexpandlegacy/#a36dad74089210c43c8fa985f86ce4183">anonymous{AtomicExpandPass.cpp}::AtomicExpandLegacy::AtomicExpandLegacy</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrexpandpseudoinsts-cpp-/avrexpandpseudo/#a3a9340f714a9e64a69b5fd17649a5fb2">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::AVRExpandPseudo</a>, <a href="/web-llvm/docs/api/classes/anonymous-barriernooppass-cpp-/barriernoop/#ae24fa7a872ebae5182168324db0398d4">anonymous{BarrierNoopPass.cpp}::BarrierNoop::BarrierNoop</a>, <a href="/web-llvm/docs/api/classes/llvm/basicaawrapperpass/#ad00909fdd6a351163236e611797d9f54">llvm::BasicAAWrapperPass::BasicAAWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblockpathcloning/#ae4a37977976469d30192cab0877ff50e">llvm::BasicBlockPathCloning::BasicBlockPathCloning</a>, <a href="/web-llvm/docs/api/classes/anonymous-basicblocksections-cpp-/basicblocksections/#ad9f31ce8e3479d0eacbc2bb95fa85fc4">anonymous{BasicBlockSections.cpp}::BasicBlockSections::BasicBlockSections</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblocksectionsprofilereaderwrapperpass/#ab196b483867e867596d4b0c724887d26">llvm::BasicBlockSectionsProfileReaderWrapperPass::BasicBlockSectionsProfileReaderWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblocksectionsprofilereaderwrapperpass/#af672c06aa34ac7d31e4d703c95afedb5">llvm::BasicBlockSectionsProfileReaderWrapperPass::BasicBlockSectionsProfileReaderWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfowrapperpass/#a9a768738e6751ab883e9dd4075a52461">llvm::BlockFrequencyInfoWrapperPass::BlockFrequencyInfoWrapperPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfmipeephole-cpp-/bpfmipeephole/#a1bf1adde9a5b3486aa72c17cbcccbf2f">anonymous{BPFMIPeephole.cpp}::BPFMIPeephole::BPFMIPeephole</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfmichecking-cpp-/bpfmipreemitchecking/#a33902c723a327fd802835a5688a16cc7">anonymous{BPFMIChecking.cpp}::BPFMIPreEmitChecking::BPFMIPreEmitChecking</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfmipeephole-cpp-/bpfmipreemitpeephole/#a739a5e8bdafa9e880440191f21e284ae">anonymous{BPFMIPeephole.cpp}::BPFMIPreEmitPeephole::BPFMIPreEmitPeephole</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfmisimplifypatchable-cpp-/bpfmisimplifypatchable/#afbeb01be11cc281ea0718f9af111c247">anonymous{BPFMISimplifyPatchable.cpp}::BPFMISimplifyPatchable::BPFMISimplifyPatchable</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfowrapperpass/#a9b02436688f4921a0ff96e38d8c4c3dd">llvm::BranchProbabilityInfoWrapperPass::BranchProbabilityInfoWrapperPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-breakcriticaledges-cpp-/breakcriticaledges/#ac21a294d5fce24be2628e880c45d061d">anonymous{BreakCriticalEdges.cpp}::BreakCriticalEdges::BreakCriticalEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/breakfalsedeps/#aee9e205adc440a2bc0e4acc1f2b2c112">llvm::BreakFalseDeps::BreakFalseDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphwrapperpass/#ae2338c2c1223123110b34bd597acf4f2">llvm::CallGraphWrapperPass::CallGraphWrapperPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-canonicalizefreezeinloops-cpp-/canonicalizefreezeinloops/#a83567a87f5b34a5b00fca7dc8b311481">anonymous{CanonicalizeFreezeInLoops.cpp}::CanonicalizeFreezeInLoops::CanonicalizeFreezeInLoops</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifycfgpass-cpp-/cfgsimplifypass/#ab469828cefd4c2640ee0314b7f205734">anonymous{SimplifyCFGPass.cpp}::CFGSimplifyPass::CFGSimplifyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguard/#af4f230a99088b0961011852ef17371ea">anonymous{CFGuard.cpp}::CFGuard::CFGuard</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguardlongjmp-cpp-/cfguardlongjmp/#a1925e8fe035ec85aa03651c028879720">anonymous{CFGuardLongjmp.cpp}::CFGuardLongjmp::CFGuardLongjmp</a>, <a href="/web-llvm/docs/api/classes/llvm/cfifixup/#a1a8ae1e7243f1429ae068d347151f0b5">llvm::CFIFixup::CFIFixup</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfiinstrinserter-cpp-/cfiinstrinserter/#ac7e514de1dcee523358111d416cc6c9a">anonymous{CFIInstrInserter.cpp}::CFIInstrInserter::CFIInstrInserter</a>, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/codegenpreparelegacypass/#abe90e64ef1d08a332db00bfda116c9db">anonymous{CodeGenPrepare.cpp}::CodeGenPrepareLegacyPass::CodeGenPrepareLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinglegacypass/#a78349fcba3363b558979efb4ad86f3cb">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingLegacyPass::ComplexDeinterleavingLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-constanthoisting-cpp-/constanthoistinglegacypass/#a3bbef9bd51f5d580aac624910e3b7502">anonymous{ConstantHoisting.cpp}::ConstantHoistingLegacyPass::ConstantHoistingLegacyPass</a>, <a href="/web-llvm/docs/api/classes/llvm/cycleinfowrapperpass/#a3b6224f94970e54990302908ea595efb">llvm::CycleInfoWrapperPass::CycleInfoWrapperPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-deadargumentelimination-cpp-/dae/#af71a57a261ea9b266bb3547bd4533720">anonymous{DeadArgumentElimination.cpp}::DAE::DAE</a>, <a href="/web-llvm/docs/api/structs/anonymous-dce-cpp-/dcelegacypass/#a6d81339349414c116fc93bb31fbfeed0">anonymous{DCE.cpp}::DCELegacyPass::DCELegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-deadmachineinstructionelim-cpp-/deadmachineinstructionelim/#ab7d5025e5d117aedd7f52d417de08980">anonymous{DeadMachineInstructionElim.cpp}::DeadMachineInstructionElim::DeadMachineInstructionElim</a>, <a href="/web-llvm/docs/api/classes/llvm/dependenceanalysiswrapperpass/#af6208fa726b6d92d547bc76f79b5df5e">llvm::DependenceAnalysisWrapperPass::DependenceAnalysisWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/dominancefrontierwrapperpass/#a4fc7d1801f47b2516e9e74bf19fca4fc">llvm::DominanceFrontierWrapperPass::DominanceFrontierWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreewrapperpass/#a1a4fd5fd8cd3525c7b5d82c9f4b28745">llvm::DominatorTreeWrapperPass::DominatorTreeWrapperPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-domprinter-cpp-/domonlyviewerwrapperpass/#ad98d8b8836cfc50842f0f41e4f655298">anonymous{DomPrinter.cpp}::DomOnlyViewerWrapperPass::DomOnlyViewerWrapperPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-domprinter-cpp-/domviewerwrapperpass/#aa128757dbe3ff1cd4887b9b5917bc77e">anonymous{DomPrinter.cpp}::DomViewerWrapperPass::DomViewerWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/dummycgsccpass/#a8eca94a66ab1e41a8f3d8dcf8e9f65cd">llvm::DummyCGSCCPass::DummyCGSCCPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxcontainerglobals-cpp-/dxcontainerglobals/#a9f02629d28b8bfd6a6a638e625c76c1a">anonymous{DXContainerGlobals.cpp}::DXContainerGlobals::DXContainerGlobals</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilmetadataanalysiswrapperpass/#ae4919c955018df24f7523c1e68263d9f">llvm::DXILMetadataAnalysisWrapperPass::DXILMetadataAnalysisWrapperPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilprettyprinter-cpp-/dxilprettyprinterlegacy/#a0d6db3ce0d525ab72e89de9188f6e338">anonymous{DXILPrettyPrinter.cpp}::DXILPrettyPrinterLegacy::DXILPrettyPrinterLegacy</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilprettyprinter-cpp-/dxilprettyprinterlegacy/#a8911e177250fc9777dcbf119e058b830">anonymous{DXILPrettyPrinter.cpp}::DXILPrettyPrinterLegacy::DXILPrettyPrinterLegacy</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilresourcebindingwrapperpass/#a704c9266b7056b418b57d247a40df132">llvm::DXILResourceBindingWrapperPass::DXILResourceBindingWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilresourcetypewrapperpass/#a2e563407bc251aa23a70a82dac7445b0">llvm::DXILResourceTypeWrapperPass::DXILResourceTypeWrapperPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlycse-cpp-/earlycselegacycommonpass/#a1b6d50260ead226bbb9aaf34c60db66f">anonymous{EarlyCSE.cpp}::EarlyCSELegacyCommonPass&lt; UseMemorySSA &gt;::EarlyCSELegacyCommonPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinelicm-cpp-/earlymachinelicm/#a60f02363b12b88b573993eea977b930a">anonymous{MachineLICM.cpp}::EarlyMachineLICM::EarlyMachineLICM</a>, <a href="/web-llvm/docs/api/classes/anonymous-tailduplication-cpp-/earlytailduplicatelegacy/#a51dd9218edc389d659f792521eb6ac28">anonymous{TailDuplication.cpp}::EarlyTailDuplicateLegacy::EarlyTailDuplicateLegacy</a>, <a href="/web-llvm/docs/api/classes/anonymous-ehcontguardcatchret-cpp-/ehcontguardcatchret/#a9034bc1de2ad8853e93752e4d2a2efd2">anonymous{EHContGuardCatchret.cpp}::EHContGuardCatchret::EHContGuardCatchret</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilwriterpass-cpp-/embeddxilpass/#a7cfcd385587ffd9348894f5926903605">anonymous{DXILWriterPass.cpp}::EmbedDXILPass::EmbedDXILPass</a>, <a href="/web-llvm/docs/api/classes/llvm/errataworkaround/#a2908eea7212c17ca4b6c800950454830">llvm::ErrataWorkaround::ErrataWorkaround</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandlargedivrem-cpp-/expandlargedivremlegacypass/#a052a652cbc5d07e4dc01de8070fd20e4">anonymous{ExpandLargeDivRem.cpp}::ExpandLargeDivRemLegacyPass::ExpandLargeDivRemLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandlargefpconvert-cpp-/expandlargefpconvertlegacypass/#a14dc9b561de4b16aea3e22b7d638af6b">anonymous{ExpandLargeFpConvert.cpp}::ExpandLargeFpConvertLegacyPass::ExpandLargeFpConvertLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandmemcmp-cpp-/expandmemcmplegacypass/#a6ed0570b3b68c4cb7e97b01976719eb7">anonymous{ExpandMemCmp.cpp}::ExpandMemCmpLegacyPass::ExpandMemCmpLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandreductions-cpp-/expandreductions/#ab94fcab793fc5d9665d6c60d3ff404e2">anonymous{ExpandReductions.cpp}::ExpandReductions::ExpandReductions</a>, <a href="/web-llvm/docs/api/structs/llvm/externalaawrapperpass/#a396ec86f9c2d49fc33d7988e955bb8c4">llvm::ExternalAAWrapperPass::ExternalAAWrapperPass</a>, <a href="/web-llvm/docs/api/structs/llvm/externalaawrapperpass/#ae0bc518752c4d4d10b6bc9caaa703525">llvm::ExternalAAWrapperPass::ExternalAAWrapperPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64falkorhwpffix-cpp-/falkorhwpffix/#ae08ddfd01392230349d183851e1ddbb8">anonymous{AArch64FalkorHWPFFix.cpp}::FalkorHWPFFix::FalkorHWPFFix</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64falkorhwpffix-cpp-/falkormarkstridedaccesseslegacy/#a5433d9efff45d1b962edd8b333f83dc8">anonymous{AArch64FalkorHWPFFix.cpp}::FalkorMarkStridedAccessesLegacy::FalkorMarkStridedAccessesLegacy</a>, <a href="/web-llvm/docs/api/structs/anonymous-fentryinserter-cpp-/fentryinserter/#a36ba165e6b9b16a6ca1dbd1d11469b65">anonymous{FEntryInserter.cpp}::FEntryInserter::FEntryInserter</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineinstrbundle-cpp-/finalizemachinebundles/#a97244d9925a6bf37261989439f3aa5ea">anonymous{MachineInstrBundle.cpp}::FinalizeMachineBundles::FinalizeMachineBundles</a>, <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a43fed8d1dfacc9362ed5b08f841782f8">llvm::PMTopLevelManager::findAnalysisPassInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-fixirreducible-cpp-/fixirreducible/#a771ed04c404ee8847afa926f034c9695">anonymous{FixIrreducible.cpp}::FixIrreducible::FixIrreducible</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/fixupstatepointcallersaved/#a0c1e46c08bb509de4b3d8ad55d55bec7">anonymous{FixupStatepointCallerSaved.cpp}::FixupStatepointCallerSaved::FixupStatepointCallerSaved</a>, <a href="/web-llvm/docs/api/structs/anonymous-flattencfgpass-cpp-/flattencfglegacypass/#a9ccbab2fe56b8d9421d1affd1d046fe4">anonymous{FlattenCFGPass.cpp}::FlattenCFGLegacyPass::FlattenCFGLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-funcletlayout-cpp-/funcletlayout/#ac8b77f52f6c6563e390b16966a9b284d">anonymous{FuncletLayout.cpp}::FuncletLayout::FuncletLayout</a>, <a href="/web-llvm/docs/api/classes/gcemptybasicblocks/#a417e363f30acac4927adeaa4e5a92b9d">GCEmptyBasicBlocks::GCEmptyBasicBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/gcmoduleinfo/#aef9a20d9d1ca159dbb4419dc2b964e0d">llvm::GCModuleInfo::GCModuleInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnnsareassign-cpp-/gcnnsareassign/#abd583ab8cb69cc1fb36126964e5e5f59">anonymous{GCNNSAReassign.cpp}::GCNNSAReassign::GCNNSAReassign</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnpreralongbranchreg-cpp-/gcnpreralongbranchreg/#aae0968a2a73f573c144bf5d33512c92b">anonymous{GCNPreRALongBranchReg.cpp}::GCNPreRALongBranchReg::GCNPreRALongBranchReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnpreraoptimizations-cpp-/gcnpreraoptimizations/#a7822b5641c7fbfec0289dd461958f8c5">anonymous{GCNPreRAOptimizations.cpp}::GCNPreRAOptimizations::GCNPreRAOptimizations</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp/#a8fd5fd11f1d85fee7e28a197e915aa0d">getPassInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/giselcseanalysiswrapperpass/#ae0fcf7c40a3d9174bb4f4513951f33bd">llvm::GISelCSEAnalysisWrapperPass::GISelCSEAnalysisWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbitsanalysis/#a60120fdb9fda94efd174c20485d7fc6a">llvm::GISelKnownBitsAnalysis::GISelKnownBitsAnalysis</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmerge-cpp-/globalmerge/#a92cb5e0ddb6f9c0ddacb9a9b791977af">anonymous{GlobalMerge.cpp}::GlobalMerge::GlobalMerge</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmerge-cpp-/globalmerge/#a7cf1070f862ab357580f5b924f603f97">anonymous{GlobalMerge.cpp}::GlobalMerge::GlobalMerge</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmergefunctions-cpp-/globalmergefuncpasswrapper/#a31d8ba521e28dc750693f4ab0ef24430">anonymous{GlobalMergeFunctions.cpp}::GlobalMergeFuncPassWrapper::GlobalMergeFuncPassWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/globalsaawrapperpass/#a80689972219595f22363d542bc9d2ad3">llvm::GlobalsAAWrapperPass::GlobalsAAWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/gvn/gvnlegacypass/#a1d3a6becc90b78d1a05cfaa947f802b1">llvm::gvn::GVNLegacyPass::GVNLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-hardwareloops-cpp-/hardwareloopslegacy/#a615f2d90d7ae440a010bd7dc6b51ba08">anonymous{HardwareLoops.cpp}::HardwareLoopsLegacy::HardwareLoopsLegacy</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonbranchrelaxation-cpp-/hexagonbranchrelaxation/#a606394dff375216a6537fd176bdeb852">anonymous{HexagonBranchRelaxation.cpp}::HexagonBranchRelaxation::HexagonBranchRelaxation</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonframelowering-cpp-/hexagoncallframeinformation/#adfe283520dd1b282bc4174e6e50194ff">anonymous{HexagonFrameLowering.cpp}::HexagonCallFrameInformation::HexagonCallFrameInformation</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a2ba581e9dbe6327f7df9bf62a7f3aa0f">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::HexagonCFGOptimizer</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncommongep-cpp-/hexagoncommongep/#a74cb22deaf6cfa14e0591240b5ee0be5">anonymous{HexagonCommonGEP.cpp}::HexagonCommonGEP::HexagonCommonGEP</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a86dde240344525272b07f5b7360040bc">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::HexagonCopyHoisting</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonexpandcondsets-cpp-/hexagonexpandcondsets/#a320f430bcb4b19adc1c60ddb4de3a923">anonymous{HexagonExpandCondsets.cpp}::HexagonExpandCondsets::HexagonExpandCondsets</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonfixuphwloops-cpp-/hexagonfixuphwloops/#a8912e2114a5b67875ede6a4c841f9598">anonymous{HexagonFixupHwLoops.cpp}::HexagonFixupHwLoops::HexagonFixupHwLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagongenextract-cpp-/hexagongenextract/#a9ae1e132ed9476f925ef1193d4524f42">anonymous{HexagonGenExtract.cpp}::HexagonGenExtract::HexagonGenExtract</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagongeninsert-cpp-/hexagongeninsert/#adc3b64e403064b40a5b718ef24a49af7">anonymous{HexagonGenInsert.cpp}::HexagonGenInsert::HexagonGenInsert</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagongenmemabsolute-cpp-/hexagongenmemabsolute/#a0c5c5370ba575af495f14fac5d8cb5a1">anonymous{HexagonGenMemAbsolute.cpp}::HexagonGenMemAbsolute::HexagonGenMemAbsolute</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagongenpredicate-cpp-/hexagongenpredicate/#acad043f152a108896067170b9fdeebc4">anonymous{HexagonGenPredicate.cpp}::HexagonGenPredicate::HexagonGenPredicate</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonloadstorewidening-cpp-/hexagonloadwidening/#af98dabe4e484cd8da4c2f508659e359b">anonymous{HexagonLoadStoreWidening.cpp}::HexagonLoadWidening::HexagonLoadWidening</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonloopalign-cpp-/hexagonloopalign/#a30a0fc5fdadaae72daa23244a415fbdb">anonymous{HexagonLoopAlign.cpp}::HexagonLoopAlign::HexagonLoopAlign</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonloopidiomrecognition-cpp-/hexagonloopidiomrecognizelegacypass/#ab79fd5e720414ada4a1a82dedf88ad5a">anonymous{HexagonLoopIdiomRecognition.cpp}::HexagonLoopIdiomRecognizeLegacyPass::HexagonLoopIdiomRecognizeLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonlooprescheduling/#afb103de2c5626116f030cf8b54515c89">anonymous{HexagonBitSimplify.cpp}::HexagonLoopRescheduling::HexagonLoopRescheduling</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmask/#a0e73ffba0c24eb0603947fda27641313">llvm::HexagonMask::HexagonMask</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonoptimizeszextends-cpp-/hexagonoptimizeszextends/#aba37b39bbd2fb8453250fe0d501edd9a">anonymous{HexagonOptimizeSZextends.cpp}::HexagonOptimizeSZextends::HexagonOptimizeSZextends</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonpeephole-cpp-/hexagonpeephole/#a9ecb5c2b12b572f5bb7ab3600d572c2d">anonymous{HexagonPeephole.cpp}::HexagonPeephole::HexagonPeephole</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonsplitconst32andconst64-cpp-/hexagonsplitconst32andconst64/#abb1c7db518ab36d747a6cec6858334e5">anonymous{HexagonSplitConst32AndConst64.cpp}::HexagonSplitConst32AndConst64::HexagonSplitConst32AndConst64</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonloadstorewidening-cpp-/hexagonstorewidening/#a521d3ff3aa49ab138787f660cb0409a3">anonymous{HexagonLoadStoreWidening.cpp}::HexagonStoreWidening::HexagonStoreWidening</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetmachine/#aaba049307055dcc9ea7de0eb29f0d5b3">llvm::HexagonTargetMachine::HexagonTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagontfrcleanup-cpp-/hexagontfrcleanup/#a091a2e79a66de1aba58ec88d7727fb66">anonymous{HexagonTfrCleanup.cpp}::HexagonTfrCleanup::HexagonTfrCleanup</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorloopcarriedreuse-cpp-/hexagonvectorloopcarriedreuselegacypass/#a353d40914ce6d9eb4da9ed6523f5671c">anonymous{HexagonVectorLoopCarriedReuse.cpp}::HexagonVectorLoopCarriedReuseLegacyPass::HexagonVectorLoopCarriedReuseLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorprint-cpp-/hexagonvectorprint/#a6fe8b2d2195324f7b778c6decf50ffc6">anonymous{HexagonVectorPrint.cpp}::HexagonVectorPrint::HexagonVectorPrint</a>, <a href="/web-llvm/docs/api/classes/anonymous-ifconversion-cpp-/ifconverter/#aaed2e7dcab6610335c9197555baaac11">anonymous{IfConversion.cpp}::IfConverter::IfConverter</a>, <a href="/web-llvm/docs/api/classes/llvm/immutablemodulesummaryindexwrapperpass/#aa0c9111e9461334b142968bcb17df3ea">llvm::ImmutableModuleSummaryIndexWrapperPass::ImmutableModuleSummaryIndexWrapperPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-implicitnullchecks-cpp-/implicitnullchecks/#a85677a944f59f0cffed7481333a790c1">anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::ImplicitNullChecks</a>, <a href="/web-llvm/docs/api/classes/anonymous-indirectbrexpandpass-cpp-/indirectbrexpandlegacypass/#a7c756eabde497fca45ba89f0d191de48">anonymous{IndirectBrExpandPass.cpp}::IndirectBrExpandLegacyPass::IndirectBrExpandLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-inferaddressspaces-cpp-/inferaddressspaces/#a744cfdb1e23dd1a022fd46716b7ad528">anonymous{InferAddressSpaces.cpp}::InferAddressSpaces::InferAddressSpaces</a>, <a href="/web-llvm/docs/api/classes/anonymous-inferaddressspaces-cpp-/inferaddressspaces/#a0a78647c99e454f2f9bc19990214425f">anonymous{InferAddressSpaces.cpp}::InferAddressSpaces::InferAddressSpaces</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp/#a0ee6d21a9c3c91cd985c0b25cc11af59">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/livedebugvalues-cpp/#aac9c207ca492dbfc2dee0caa3fdb0864">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecfgprinter-cpp/#ad1679477eafc18339c046f53cde423fa">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinedominators-cpp/#a175529e8e05ebbe3b683db7dcc6001d8">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepostdominators-cpp/#abb1e8e970b1c9d9eb6f0ba67f10509c1">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/domprinter-cpp/#a9b79a001d7887becdfe0ea8df40205da">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp/#a85b6c88c975bbd4d6dd24d0841154df9">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeredundantdebugvalues-cpp/#a4160213620f4be1bfdbecc9034c1bf6e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaplivenessanalysis-cpp/#a560ef9e88415138e451c74c92d5bfddb">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncombiningpass/#a0dd4dac14ef239990364482706fd75f3">llvm::InstructionCombiningPass::InstructionCombiningPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-instsimplifypass-cpp-/instsimplifylegacypass/#a14099b42033742c6c000496cd6902eef">anonymous{InstSimplifyPass.cpp}::InstSimplifyLegacyPass::InstSimplifyLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-interleavedaccesspass-cpp-/interleavedaccess/#a69a3a83e198c16cf40f8f065238602d1">anonymous{InterleavedAccessPass.cpp}::InterleavedAccess::InterleavedAccess</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/interleavedloadcombine/#a2deb0f39bab32cc794af7b1be7ae6012">anonymous{InterleavedLoadCombinePass.cpp}::InterleavedLoadCombine::InterleavedLoadCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ivuserswrapperpass/#a5f2ff52689aeae08cca03646c448bb91">llvm::IVUsersWrapperPass::IVUsersWrapperPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-jmcinstrumenter-cpp-/jmcinstrumenter/#a49449a066ac7e9da62ad7f7f83f76bed">anonymous{JMCInstrumenter.cpp}::JMCInstrumenter::JMCInstrumenter</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaimemalucombiner-cpp-/lanaimemalucombiner/#a503c450620115362e26fc90fbc7be47f">anonymous{LanaiMemAluCombiner.cpp}::LanaiMemAluCombiner::LanaiMemAluCombiner</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyblockfrequencyinfopass/#ae107b172f74e294f4c657b851fa8a42d">llvm::LazyBlockFrequencyInfoPass::LazyBlockFrequencyInfoPass</a>, <a href="/web-llvm/docs/api/classes/llvm/lazybranchprobabilityinfopass/#ae535ac0ecc5c9986d1b7561b27ebf125">llvm::LazyBranchProbabilityInfoPass::LazyBranchProbabilityInfoPass</a>, <a href="/web-llvm/docs/api/classes/llvm/lazymachineblockfrequencyinfopass/#a976393e8e2e8c6eb8a214775ed43481b">llvm::LazyMachineBlockFrequencyInfoPass::LazyMachineBlockFrequencyInfoPass</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfowrapperpass/#ac166ee6fcd842179c721701c494a4c1b">llvm::LazyValueInfoWrapperPass::LazyValueInfoWrapperPass</a>, <a href="/web-llvm/docs/api/structs/llvm/lcssaverificationpass/#aca91975e3660d087bfc8b98ffca0645a">llvm::LCSSAVerificationPass::LCSSAVerificationPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-lcssa-cpp-/lcssawrapperpass/#a5b6d9b6d951eadd996b8faf096e290c9">anonymous{LCSSA.cpp}::LCSSAWrapperPass::LCSSAWrapperPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64cleanuplocaldynamictlspass-cpp-/ldtlscleanup/#a17344fd5260d73805496ae43b221db29">anonymous{AArch64CleanupLocalDynamicTLSPass.cpp}::LDTLSCleanup::LDTLSCleanup</a>, <a href="/web-llvm/docs/api/structs/anonymous-licm-cpp-/legacylicmpass/#a4ca93bfd48742106afe0a529f3032a22">anonymous{LICM.cpp}::LegacyLICMPass::LegacyLICMPass</a>, <a href="/web-llvm/docs/api/classes/llvm/livedebugvariableswrapperlegacy/#a33511817339d41d5a36b6c0130fe2764">llvm::LiveDebugVariablesWrapperLegacy::LiveDebugVariablesWrapperLegacy</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalswrapperpass/#ac01110e36e4b5ad87d778b1c0b3f029a">llvm::LiveIntervalsWrapperPass::LiveIntervalsWrapperPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-liverangeshrink-cpp-/liverangeshrink/#ac1ddde7b263d8ad7b0add9a8f5b4a799">anonymous{LiveRangeShrink.cpp}::LiveRangeShrink::LiveRangeShrink</a>, <a href="/web-llvm/docs/api/classes/llvm/livestackswrapperlegacy/#a5592647b51ec84f1fb0258b4e452c1cc">llvm::LiveStacksWrapperLegacy::LiveStacksWrapperLegacy</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariableswrapperpass/#a50e87d44151d946f89ba6bb6bd957cc3">llvm::LiveVariablesWrapperPass::LiveVariablesWrapperPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#ad29f792516a692b403e4f66d9815002f">LLVMInitializeAArch64Target</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#ab1daa0f11648eb67d340b69f83f6e196">LLVMInitializeAMDGPUTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arctargetmachine-cpp/#a7a0d1dafcf74f4d12be428d38b236876">LLVMInitializeARCTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp/#a6685488f57ab6c8880f8e18a5364181a">LLVMInitializeARMTarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8fd5bdf026357cb11043211e812f91e5">llvm::LLVMInitializeAVRTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpftargetmachine-cpp/#a25f2b3e2f3a759d1986d97f81dab0ec5">LLVMInitializeBPFTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskytargetmachine-cpp/#aef449992ce85170fc4e20ccc1fb822dc">LLVMInitializeCSKYTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-cpp/#a7c874778b9aadea658c289d076d1b8b8">LLVMInitializeDirectXTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#af01d552fbdd044b3e41bb99f905bcccd">LLVMInitializeHexagonTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaitargetmachine-cpp/#ab3f2305043d5778e874d45de4b7f9ea2">LLVMInitializeLanaiTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchtargetmachine-cpp/#adf9c18b7627d3daa19cd81911ffcf703">LLVMInitializeLoongArchTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ktargetmachine-cpp/#a37850ef8b98b5c3049cf47d36a0fa38a">LLVMInitializeM68kTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetmachine-cpp/#abef57f2f45a7ce74cf7267749570eb17">LLVMInitializeMipsTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430targetmachine-cpp/#a4d4f67c31571fbace48e599ebbd66fc9">LLVMInitializeMSP430Target</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp/#aaed7e2473819aa12e64e58f5e9e8d79f">LLVMInitializeNVPTXTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargetmachine-cpp/#afcd90d71029f6f8cc67de62444a5d681">LLVMInitializePowerPCTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp/#a8b9a09dbbf4b2bacd980a00284a2c143">LLVMInitializeRISCVTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparctargetmachine-cpp/#a5ced6bd290b4ef3d5c9eb4d47d164490">LLVMInitializeSparcTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp/#aa3b9ca78bbd44f9b9c4417b261aa1175">LLVMInitializeSPIRVTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetmachine-cpp/#a6b9585b9bf84e64f4acc5808772f0eec">LLVMInitializeSystemZTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vetargetmachine-cpp/#a4c27f0cd53f78a7bb743fe7d1653726e">LLVMInitializeVETarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp/#a5193d47b6ee96653d85049ae1ab002e9">LLVMInitializeWebAssemblyTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp/#aa63db78a8378c10074d19a12e66ad98f">LLVMInitializeX86Target</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetmachine-cpp/#a2ed1605d9ce6d806b0b046dcc4d30819">LLVMInitializeXCoreTarget</a>, <a href="/web-llvm/docs/api/classes/anonymous-loadstorevectorizer-cpp-/loadstorevectorizerlegacypass/#a5496d45523c2e59631c5eb78365ff432">anonymous{LoadStoreVectorizer.cpp}::LoadStoreVectorizerLegacyPass::LoadStoreVectorizerLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-localstackslotallocation-cpp-/localstackslotpass/#ac5e2231e755cdee5c0c1d0a58debbd52">anonymous{LocalStackSlotAllocation.cpp}::LocalStackSlotPass::LocalStackSlotPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchexpandatomicpseudoinsts-cpp-/loongarchexpandatomicpseudo/#a76f4448487bbc129d73f0b9cbaf314e8">anonymous{LoongArchExpandAtomicPseudoInsts.cpp}::LoongArchExpandAtomicPseudo::LoongArchExpandAtomicPseudo</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchexpandpseudoinsts-cpp-/loongarchexpandpseudo/#acf26b7fa05388dd3d67b2c062f5c2104">anonymous{LoongArchExpandPseudoInsts.cpp}::LoongArchExpandPseudo::LoongArchExpandPseudo</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchexpandpseudoinsts-cpp-/loongarchpreraexpandpseudo/#a2d218a81b5aaffd52cd6e9a3d5906ff4">anonymous{LoongArchExpandPseudoInsts.cpp}::LoongArchPreRAExpandPseudo::LoongArchPreRAExpandPseudo</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdataprefetch-cpp-/loopdataprefetchlegacypass/#a06078462e1f54a11ba44429eb45e78c7">anonymous{LoopDataPrefetch.cpp}::LoopDataPrefetchLegacyPass::LoopDataPrefetchLegacyPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopextractor-cpp-/loopextractorlegacypass/#ac708cf6ddd7c434fb2ce92d8deba5bc6">anonymous{LoopExtractor.cpp}::LoopExtractorLegacyPass::LoopExtractorLegacyPass</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfowrapperpass/#a961c86177bf3257b60bef12e132a840b">llvm::LoopInfoWrapperPass::LoopInfoWrapperPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopsimplify-cpp-/loopsimplify/#a8501dc656b72a664396172545314bb19">anonymous{LoopSimplify.cpp}::LoopSimplify::LoopSimplify</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/loopstrengthreduce/#af80949a15e2bf1220022362faa9579e0">anonymous{LoopStrengthReduce.cpp}::LoopStrengthReduce::LoopStrengthReduce</a>, <a href="/web-llvm/docs/api/classes/anonymous-looptermfold-cpp-/looptermfold/#a767ac61ce082443ba72c2ec15b0f6439">anonymous{LoopTermFold.cpp}::LoopTermFold::LoopTermFold</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopunrollpass-cpp-/loopunroll/#a75e222e94c61c768491fb808096d1953">anonymous{LoopUnrollPass.cpp}::LoopUnroll::LoopUnroll</a>, <a href="/web-llvm/docs/api/classes/anonymous-loweratomicpass-cpp-/loweratomiclegacypass/#a50b840858b5e03cebc1dafeddf7008b1">anonymous{LowerAtomicPass.cpp}::LowerAtomicLegacyPass::LowerAtomicLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-loweremutls-cpp-/loweremutls/#a7ea06d345a80b1b83f9d16834ca92fb4">anonymous{LowerEmuTLS.cpp}::LowerEmuTLS::LowerEmuTLS</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowerglobaldtors-cpp-/lowerglobaldtorslegacypass/#aaacafddaf15c9892004cb5aada5780b1">anonymous{LowerGlobalDtors.cpp}::LowerGlobalDtorsLegacyPass::LowerGlobalDtorsLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/lowerintrinsics/#a6f650cca785b60797616895846715923">anonymous{GCRootLowering.cpp}::LowerIntrinsics::LowerIntrinsics</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowerinvoke-cpp-/lowerinvokelegacypass/#a7e3b7f68d51ab1f20f063c18e28a3203">anonymous{LowerInvoke.cpp}::LowerInvokeLegacyPass::LowerInvokeLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowerswitch-cpp-/lowerswitchlegacypass/#ac0b06d86a423b349cbbef8b257011762">anonymous{LowerSwitch.cpp}::LowerSwitchLegacyPass::LowerSwitchLegacyPass</a>, <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfowrapperpass/#ab1d0f4807af42f0b40d5c258636d690b">llvm::MachineBlockFrequencyInfoWrapperPass::MachineBlockFrequencyInfoWrapperPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacement/#ad7175334e09f55bf7b5fb08d9522449e">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::MachineBlockPlacement</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacementstats/#ab048335b4f8ed04dfd6d34baa1881a9c">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacementStats::MachineBlockPlacementStats</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfowrapperpass/#ad81c5080ac82b77e1411da9d8aa8699b">llvm::MachineBranchProbabilityInfoWrapperPass::MachineBranchProbabilityInfoWrapperPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecombiner-cpp-/machinecombiner/#ae516950e802bf6d6170ad7574ac59a91">anonymous{MachineCombiner.cpp}::MachineCombiner::MachineCombiner</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/machinecopypropagation/#aff25a007ce7835a747eb0ba8eac4d5a7">anonymous{MachineCopyPropagation.cpp}::MachineCopyPropagation::MachineCopyPropagation</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecse-cpp-/machinecselegacy/#a472b54387d8f1686ce21cd0e5bd39c66">anonymous{MachineCSE.cpp}::MachineCSELegacy::MachineCSELegacy</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecycleanalysis-cpp-/machinecycleinfoprinterpass/#a0b66c506a44f4bad85f30f975f32a414">anonymous{MachineCycleAnalysis.cpp}::MachineCycleInfoPrinterPass::MachineCycleInfoPrinterPass</a>, <a href="/web-llvm/docs/api/classes/llvm/machinecycleinfowrapperpass/#a125313bddaf556f85f4e39e1071960ae">llvm::MachineCycleInfoWrapperPass::MachineCycleInfoWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/machinedominancefrontier/#a8b08c5248fd0dbccca12e77a9686fe5c">llvm::MachineDominanceFrontier::MachineDominanceFrontier</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinefunctionsplitter-cpp-/machinefunctionsplitter/#a7acc3b5f1afa6f3824eec2cb0dbd1d95">anonymous{MachineFunctionSplitter.cpp}::MachineFunctionSplitter::MachineFunctionSplitter</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinelateinstrscleanup-cpp-/machinelateinstrscleanup/#a4c223117947cd9c06e788a5a193b7bef">anonymous{MachineLateInstrsCleanup.cpp}::MachineLateInstrsCleanup::MachineLateInstrsCleanup</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinelicm-cpp-/machinelicm/#a122481ff15eebc8f0456022e1346b4d1">anonymous{MachineLICM.cpp}::MachineLICM::MachineLICM</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloopinfowrapperpass/#ab03bdd06982c78c9d060dcf3611bcabe">llvm::MachineLoopInfoWrapperPass::MachineLoopInfoWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfowrapperpass/#a7563ec3fdfea7bbc85c3c03c3169c720">llvm::MachineModuleInfoWrapperPass::MachineModuleInfoWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfowrapperpass/#a6b73500cda87f22b0c0866c6139c95be">llvm::MachineModuleInfoWrapperPass::MachineModuleInfoWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkemitterpass/#afc21e44136ae33a1f3d3cc32d286f5b9">llvm::MachineOptimizationRemarkEmitterPass::MachineOptimizationRemarkEmitterPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a8390acb69c9afa4044e5d8f3ffec7d12">anonymous{MachineOutliner.cpp}::MachineOutliner::MachineOutliner</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepipeliner/#ab6e3bfef0e625e4c1ec7d4cf3d5f7d84">llvm::MachinePipeliner::MachinePipeliner</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregioninfopass/#af1c246248a49df0c52fd3055ea258faa">llvm::MachineRegionInfoPass::MachineRegionInfoPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-sanitizerbinarymetadata-cpp-/machinesanitizerbinarymetadata/#a7411820cbca201d2964f2ea01714b829">anonymous{SanitizerBinaryMetadata.cpp}::MachineSanitizerBinaryMetadata::MachineSanitizerBinaryMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#a0107c12ed6aa7d7935b96015ef5b9ca4">anonymous{MachineScheduler.cpp}::MachineScheduler::MachineScheduler</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinesink-cpp-/machinesinking/#a7eaa892247782f8364a7924e675e1ab7">anonymous{MachineSink.cpp}::MachineSinking::MachineSinking</a>, <a href="/web-llvm/docs/api/classes/llvm/machineuniformityanalysispass/#a7300a04eb4b356cf9e17ce6f39093bdf">llvm::MachineUniformityAnalysisPass::MachineUniformityAnalysisPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineuniformityanalysis-cpp-/machineuniformityinfoprinterpass/#ad63294f7de037b74b82bd851407cbedb">anonymous{MachineUniformityAnalysis.cpp}::MachineUniformityInfoPrinterPass::MachineUniformityInfoPrinterPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifierlegacypass/#a19c383e3cb270e114976a9444818b6d6">anonymous{MachineVerifier.cpp}::MachineVerifierLegacyPass::MachineVerifierLegacyPass</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependencewrapperpass/#ada101917bddd2804c090bfbe8e21c6b6">llvm::MemoryDependenceWrapperPass::MemoryDependenceWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssawrapperpass/#ae3df661a4d028ba1a08c8b243c721663">llvm::MemorySSAWrapperPass::MemorySSAWrapperPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-mergeicmps-cpp-/mergeicmpslegacypass/#aed7a8b56afc902a82c037b504739aa88">anonymous{MergeICmps.cpp}::MergeICmpsLegacyPass::MergeICmpsLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsbranchexpansion-cpp-/mipsbranchexpansion/#a8592b6883e51c73ec1902172497656c3">anonymous{MipsBranchExpansion.cpp}::MipsBranchExpansion::MipsBranchExpansion</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/mipsdelayslotfiller/#a3b8e20cb5354225f3c488f4eaac4ea1d">anonymous{MipsDelaySlotFiller.cpp}::MipsDelaySlotFiller::MipsDelaySlotFiller</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsmulmulbugpass-cpp-/mipsmulmulbugfix/#a106145d694f37e511f80626cee35d69e">anonymous{MipsMulMulBugPass.cpp}::MipsMulMulBugFix::MipsMulMulBugFix</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsprelegalizercombiner-cpp-/mipsprelegalizercombiner/#ab9f8a202eaa453ef53e0b24c3a9debad">anonymous{MipsPreLegalizerCombiner.cpp}::MipsPreLegalizerCombiner::MipsPreLegalizerCombiner</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindexwrapperpass/#a61bb7e79981424e60981a25c7a22d844">llvm::ModuleSummaryIndexWrapperPass::ModuleSummaryIndexWrapperPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/moduloscheduletest/#a645424bccb86403ae8d229c885b8a8f2">anonymous{ModuloSchedule.cpp}::ModuloScheduleTest::ModuloScheduleTest</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvegatherscatterlowering-cpp-/mvegatherscatterlowering/#a0fbaeb54c278599385655aeca42f6acf">anonymous{MVEGatherScatterLowering.cpp}::MVEGatherScatterLowering::MVEGatherScatterLowering</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvelaneinterleavingpass-cpp-/mvelaneinterleaving/#ac18d5a39229ff0461edf73f2274a6e14">anonymous{MVELaneInterleavingPass.cpp}::MVELaneInterleaving::MVELaneInterleaving</a>, <a href="/web-llvm/docs/api/classes/anonymous-naryreassociate-cpp-/naryreassociatelegacypass/#a9db9a18092fe2ba90c234142c1e76058">anonymous{NaryReassociate.cpp}::NaryReassociateLegacyPass::NaryReassociateLegacyPass</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxaawrapperpass/#a3369657625676bf10b6bc9fecf041e98">llvm::NVPTXAAWrapperPass::NVPTXAAWrapperPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxpeephole-cpp-/nvptxpeephole/#ae6991baba15636e0d06e77924c78b5c1">anonymous{NVPTXPeephole.cpp}::NVPTXPeephole::NVPTXPeephole</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxproxyregerasure-cpp-/nvptxproxyregerasure/#a5ee1a9866d31abc445fdc92cb2460b9c">anonymous{NVPTXProxyRegErasure.cpp}::NVPTXProxyRegErasure::NVPTXProxyRegErasure</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvvmintrrange-cpp-/nvvmintrrange/#aabcd7f17ce4ac381bbc7c547807be4d1">anonymous{NVVMIntrRange.cpp}::NVVMIntrRange::NVVMIntrRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvvmreflect-cpp-/nvvmreflect/#a3e47db6cc0723c3ada6cbba3dbf7649f">anonymous{NVVMReflect.cpp}::NVVMReflect::NVVMReflect</a>, <a href="/web-llvm/docs/api/classes/anonymous-objcarccontract-cpp-/objcarccontractlegacypass/#afea41e86dd661e52fa1d0501803fe879">anonymous{ObjCARCContract.cpp}::ObjCARCContractLegacyPass::ObjCARCContractLegacyPass</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitterwrapperpass/#a60c1f821770851c72aa81a4fe661c474">llvm::OptimizationRemarkEmitterWrapperPass::OptimizationRemarkEmitterWrapperPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-optimizephis-cpp-/optimizephislegacy/#ae06a32bb4eef2eecd58d645c9ff80b53">anonymous{OptimizePHIs.cpp}::OptimizePHIsLegacy::OptimizePHIsLegacy</a>, <a href="/web-llvm/docs/api/classes/anonymous-partiallyinlinelibcalls-cpp-/partiallyinlinelibcallslegacypass/#a9475dc6c9f3c14ba4e6fa5b68cce3f88">anonymous{PartiallyInlineLibCalls.cpp}::PartiallyInlineLibCallsLegacyPass::PartiallyInlineLibCallsLegacyPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-patchablefunction-cpp-/patchablefunction/#a160acb3644af7b7797b80065b2c83915">anonymous{PatchableFunction.cpp}::PatchableFunction::PatchableFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizerlegacy/#afe0e00ac63da6e8954b0a7da656720dd">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizerLegacy::PeepholeOptimizerLegacy</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a9e8f07c48260d553871a27e9f0a98252">anonymous{PrologEpilogInserter.cpp}::PEI::PEI</a>, <a href="/web-llvm/docs/api/classes/anonymous-phielimination-cpp-/phielimination/#afbc58aee0e01cef5aa50eb3a79109eb2">anonymous{PHIElimination.cpp}::PHIElimination::PHIElimination</a>, <a href="/web-llvm/docs/api/classes/llvm/phivalueswrapperpass/#a0df069d6a59cb3f956ec38bf4715e9af">llvm::PhiValuesWrapperPass::PhiValuesWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/physicalregisterusageinfowrapperlegacy/#acb2dceef7517a511b8273960a4f685ba">llvm::PhysicalRegisterUsageInfoWrapperLegacy::PhysicalRegisterUsageInfoWrapperLegacy</a>, <a href="/web-llvm/docs/api/classes/anonymous-placesafepoints-cpp-/placebackedgesafepointslegacypass/#ad4fe890aa81f74897049f012831850f2">anonymous{PlaceSafepoints.cpp}::PlaceBackedgeSafepointsLegacyPass::PlaceBackedgeSafepointsLegacyPass</a>, <a href="/web-llvm/docs/api/structs/llvm/postdominatortreewrapperpass/#a6cd2b8ee4eb9aa4e6f3eb35bcc34625b">llvm::PostDominatorTreeWrapperPass::PostDominatorTreeWrapperPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-domprinter-cpp-/postdomonlyviewerwrapperpass/#ae7893486019ad40a008acf6afcdd8c96">anonymous{DomPrinter.cpp}::PostDomOnlyViewerWrapperPass::PostDomOnlyViewerWrapperPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-domprinter-cpp-/postdomviewerwrapperpass/#a7bd13dc24c57c383d9daa7b23b829f1b">anonymous{DomPrinter.cpp}::PostDomViewerWrapperPass::PostDomViewerWrapperPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-entryexitinstrumenter-cpp-/postinlineentryexitinstrumenter/#aab67b890dd35db83c9e8d68623dc050b">anonymous{EntryExitInstrumenter.cpp}::PostInlineEntryExitInstrumenter::PostInlineEntryExitInstrumenter</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler/#a95ac78157333c863b9fb682756477f6e">anonymous{MachineScheduler.cpp}::PostMachineScheduler::PostMachineScheduler</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcboolrettoint-cpp-/ppcboolrettoint/#a087491e26aa7ad2a405f04ba6cbb153d">anonymous{PPCBoolRetToInt.cpp}::PPCBoolRetToInt::PPCBoolRetToInt</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#add8333a5e76125bbe69af183e99c00eb">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::PPCBranchCoalescing</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcbranchselector-cpp-/ppcbsel/#a90f6b07dd459c4103545d88bb7dc6567">anonymous{PPCBranchSelector.cpp}::PPCBSel::PPCBSel</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcctrloops-cpp-/ppcctrloops/#a3fef253a8a63739b6fcf4704d9aa3735">anonymous{PPCCTRLoops.cpp}::PPCCTRLoops::PPCCTRLoops</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcctrloopsverify-cpp-/ppcctrloopsverify/#a8012bdb0bdbe3b6a067551553a678e26">anonymous{PPCCTRLoopsVerify.cpp}::PPCCTRLoopsVerify::PPCCTRLoopsVerify</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ad9c33ece6c51bcb4178dd310cf979e34">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::PPCEarlyReturn</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcexpandatomicpseudoinsts-cpp-/ppcexpandatomicpseudo/#a8351170d3d679a86b00975b7cd314616">anonymous{PPCExpandAtomicPseudoInsts.cpp}::PPCExpandAtomicPseudo::PPCExpandAtomicPseudo</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcloopinstrformprep-cpp-/ppcloopinstrformprep/#a635dff4b525cccd46d367555c76cbd9b">anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep::PPCLoopInstrFormPrep</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcloopinstrformprep-cpp-/ppcloopinstrformprep/#ab7e4f499c94d07a9782f75740906ffd5">anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep::PPCLoopInstrFormPrep</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcmipeephole-cpp-/ppcmipeephole/#a43f69cfe93eb86d8c3304099b3a2ed9b">anonymous{PPCMIPeephole.cpp}::PPCMIPeephole::PPCMIPeephole</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a8d824242683d3b51c9f9761b36a30fc5">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::PPCPreEmitPeephole</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcreducecrlogicals-cpp-/ppcreducecrlogicals/#acc6d156736ee3429f4f50adb9be8aff6">anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::PPCReduceCRLogicals</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppctlsdynamiccall-cpp-/ppctlsdynamiccall/#a18250259d0184844ededba7d7790956a">anonymous{PPCTLSDynamicCall.cpp}::PPCTLSDynamicCall::PPCTLSDynamicCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppctocregdeps-cpp-/ppctocregdeps/#a4683cb4071581d1c2c6b190f22898118">anonymous{PPCTOCRegDeps.cpp}::PPCTOCRegDeps::PPCTOCRegDeps</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxcopy-cpp-/ppcvsxcopy/#af4362a7da28f6b430385218f2a76567b">anonymous{PPCVSXCopy.cpp}::PPCVSXCopy::PPCVSXCopy</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#a35b6e0b609d10b792d3f5d32703351d2">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::PPCVSXFMAMutate</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxswapremoval-cpp-/ppcvsxswapremoval/#a995f297afe857f56230b7b831e8637fc">anonymous{PPCVSXSwapRemoval.cpp}::PPCVSXSwapRemoval::PPCVSXSwapRemoval</a>, <a href="/web-llvm/docs/api/classes/anonymous-processimplicitdefs-cpp-/processimplicitdefs/#ac8009a14f031b7893512b0786c31cbb3">anonymous{ProcessImplicitDefs.cpp}::ProcessImplicitDefs::ProcessImplicitDefs</a>, <a href="/web-llvm/docs/api/structs/anonymous-mem2reg-cpp-/promotelegacypass/#a080ea0501fdca287bf3c915cffa7f7c6">anonymous{Mem2Reg.cpp}::PromoteLegacyPass::PromoteLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-pseudoprobeinserter-cpp-/pseudoprobeinserter/#a359415b3860961c80057b2eeea29dbea">anonymous{PseudoProbeInserter.cpp}::PseudoProbeInserter::PseudoProbeInserter</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600emitclausemarkers-cpp-/r600emitclausemarkers/#a4403e748fc3a53b6b09e3c9aeb824a07">anonymous{R600EmitClauseMarkers.cpp}::R600EmitClauseMarkers::R600EmitClauseMarkers</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a998f23f119e9621929d4b4733038330c">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::R600MachineCFGStructurizer</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#a8f0413c573fa106fd0977f9992a0b9e4">llvm::ReachingDefAnalysis::ReachingDefAnalysis</a>, <a href="/web-llvm/docs/api/classes/anonymous-reassociate-cpp-/reassociatelegacypass/#aeb9bf29ce3de417b98e0f9cb64ec3d64">anonymous{Reassociate.cpp}::ReassociateLegacyPass::ReassociateLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/regallocpbqp/#a4bbb9bb35c92791c952082d242e04c7e">anonymous{RegAllocPBQP.cpp}::RegAllocPBQP::RegAllocPBQP</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocscoring/#a771a12d918fb59d0432509518d4b6e83">llvm::RegAllocScoring::RegAllocScoring</a>, <a href="/web-llvm/docs/api/classes/llvm/regioninfopass/#a78b5c4f45e7dd177d056c548f8a71cec">llvm::RegionInfoPass::RegionInfoPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-regionprinter-cpp-/regiononlyprinter/#a247c12d1dd17b2cfb3ef91d59c209e8d">anonymous{RegionPrinter.cpp}::RegionOnlyPrinter::RegionOnlyPrinter</a>, <a href="/web-llvm/docs/api/structs/anonymous-regionprinter-cpp-/regiononlyviewer/#afc4e1d6a2e67ed8c45bf320eeb390880">anonymous{RegionPrinter.cpp}::RegionOnlyViewer::RegionOnlyViewer</a>, <a href="/web-llvm/docs/api/structs/anonymous-regionprinter-cpp-/regionprinter/#ae303d148500fba145bb2f487d8fa53c7">anonymous{RegionPrinter.cpp}::RegionPrinter::RegionPrinter</a>, <a href="/web-llvm/docs/api/structs/anonymous-regionprinter-cpp-/regionviewer/#a4427efb671e81d89e83666c40885dc27">anonymous{RegionPrinter.cpp}::RegionViewer::RegionViewer</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/registercoalescer/#a0969ad06eb530c7fc3a7d2b8b9911fa6">anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::RegisterCoalescer</a>, <a href="/web-llvm/docs/api/structs/llvm/registerpass/#aee30bf48a272c4267cd3606e047aa3e8">llvm::RegisterPass&lt; passName &gt;::RegisterPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfocollector-cpp-/regusageinfocollectorlegacy/#a5e6bca2c19f5be8bfd93cb8467acc5ed">anonymous{RegUsageInfoCollector.cpp}::RegUsageInfoCollectorLegacy::RegUsageInfoCollectorLegacy</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfopropagate-cpp-/regusageinfopropagationlegacy/#a7b11f8ce2a3ed7f2ad3d19ecf4742ef2">anonymous{RegUsageInfoPropagate.cpp}::RegUsageInfoPropagationLegacy::RegUsageInfoPropagationLegacy</a>, <a href="/web-llvm/docs/api/classes/removeloadsintofakeuses/#aeb722ba0332ea05d508a8582e2875a58">RemoveLoadsIntoFakeUses::RemoveLoadsIntoFakeUses</a>, <a href="/web-llvm/docs/api/structs/llvm/replacewithvecliblegacy/#a07753ec2fb462f782b9ecf4e460b342c">llvm::ReplaceWithVeclibLegacy::ReplaceWithVeclibLegacy</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvexpandatomicpseudoinsts-cpp-/riscvexpandatomicpseudo/#aa31d932b7f84943816d86732c7b85b29">anonymous{RISCVExpandAtomicPseudoInsts.cpp}::RISCVExpandAtomicPseudo::RISCVExpandAtomicPseudo</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvredundantcopyelimination-cpp-/riscvredundantcopyelimination/#ab2be982a385bd686f6a3776f86198334">anonymous{RISCVRedundantCopyElimination.cpp}::RISCVRedundantCopyElimination::RISCVRedundantCopyElimination</a>, <a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/safepointirverifier/#a5beee4a1a85167028539ae678e3b9d8c">anonymous{SafepointIRVerifier.cpp}::SafepointIRVerifier::SafepointIRVerifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-safestack-cpp-/safestacklegacypass/#af8d2a8aa4635273569f36a3f63044028">anonymous{SafeStack.cpp}::SafeStackLegacyPass::SafeStackLegacyPass</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolutionwrapperpass/#ae0563fcc4ee63bdd27aab57cb276c97c">llvm::ScalarEvolutionWrapperPass::ScalarEvolutionWrapperPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizemaskedmemintrin-cpp-/scalarizemaskedmemintrinlegacypass/#a3eafccc900168f9e6667c6d5b59e9f92">anonymous{ScalarizeMaskedMemIntrin.cpp}::ScalarizeMaskedMemIntrinLegacyPass::ScalarizeMaskedMemIntrinLegacyPass</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaawrapperpass/#ab156487dc35f177a63da34868c4df521">llvm::SCEVAAWrapperPass::SCEVAAWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/scopednoaliasaawrapperpass/#aec26c94177acd080ae67e2ed043e50ea">llvm::ScopedNoAliasAAWrapperPass::ScopedNoAliasAAWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#aeac54a65abd3a93279e58b0f474028fc">llvm::SelectionDAGISel::SelectionDAGISel</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisellegacy/#ae01b4f3ca138ba73e5f36833f838fbd5">llvm::SelectionDAGISelLegacy::SelectionDAGISelLegacy</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimize/#ac289adfe7b0a2c35a772bafdb784d333">anonymous{SelectOptimize.cpp}::SelectOptimize::SelectOptimize</a>, <a href="/web-llvm/docs/api/classes/anonymous-separateconstoffsetfromgep-cpp-/separateconstoffsetfromgeplegacypass/#a961511794036e31655c909fb9331fb7d">anonymous{SeparateConstOffsetFromGEP.cpp}::SeparateConstOffsetFromGEPLegacyPass::SeparateConstOffsetFromGEPLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-shadowstackgclowering-cpp-/shadowstackgclowering/#a68cdefa5fcc8655adbb0282da04b56cf">anonymous{ShadowStackGCLowering.cpp}::ShadowStackGCLowering::ShadowStackGCLowering</a>, <a href="/web-llvm/docs/api/classes/anonymous-shrinkwrap-cpp-/shrinkwrap/#a17de0c0936c0f365ccbd2deb62e4ca6f">anonymous{ShrinkWrap.cpp}::ShrinkWrap::ShrinkWrap</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixvgprcopies-cpp-/sifixvgprcopieslegacy/#aa1ebf5990ce797ed77dbc34574cf0bf2">anonymous{SIFixVGPRCopies.cpp}::SIFixVGPRCopiesLegacy::SIFixVGPRCopiesLegacy</a>, <a href="/web-llvm/docs/api/classes/anonymous-siformmemoryclauses-cpp-/siformmemoryclauses/#a78b6bff5dc54c32aff0d6d6a4bd6b814">anonymous{SIFormMemoryClauses.cpp}::SIFormMemoryClauses::SIFormMemoryClauses</a>, <a href="/web-llvm/docs/api/classes/siloweri1copieslegacy/#ada33372b016f73df30410df087f48532">SILowerI1CopiesLegacy::SILowerI1CopiesLegacy</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowerwwmcopies-cpp-/silowerwwmcopieslegacy/#af202512daca8d8c8a86c75c5a693c052">anonymous{SILowerWWMCopies.cpp}::SILowerWWMCopiesLegacy::SILowerWWMCopiesLegacy</a>, <a href="/web-llvm/docs/api/classes/anonymous-sink-cpp-/sinkinglegacypass/#a36fab2ed1d410cd914dc0156e7a9fb39">anonymous{Sink.cpp}::SinkingLegacyPass::SinkingLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizeexecmasking-cpp-/sioptimizeexecmaskinglegacy/#ab2a0b456bec7c738a3b57d07b97beee4">anonymous{SIOptimizeExecMasking.cpp}::SIOptimizeExecMaskingLegacy::SIOptimizeExecMaskingLegacy</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizeexecmaskingprera-cpp-/sioptimizeexecmaskingprera/#ae69d0c3c5269c91d8f1656bdca082836">anonymous{SIOptimizeExecMaskingPreRA.cpp}::SIOptimizeExecMaskingPreRA::SIOptimizeExecMaskingPreRA</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipostrabundler-cpp-/sipostrabundler/#af6ac5e28df9a98dbb61f6a55dc2fd7f5">anonymous{SIPostRABundler.cpp}::SIPostRABundler::SIPostRABundler</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipreemitpeephole-cpp-/sipreemitpeephole/#af2b225e068787a77422b747cf190914e">anonymous{SIPreEmitPeephole.cpp}::SIPreEmitPeephole::SIPreEmitPeephole</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexeswrapperpass/#a1c0cfec1fdb11887f5d4565247388164">llvm::SlotIndexesWrapperPass::SlotIndexesWrapperPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-smeabipass-cpp-/smeabi/#accca3fc250217cabab067305ac4e9e0a">anonymous{SMEABIPass.cpp}::SMEABI::SMEABI</a>, <a href="/web-llvm/docs/api/structs/anonymous-smepeepholeopt-cpp-/smepeepholeopt/#a49d9a7df2d3b7c97a73312a045c37d2b">anonymous{SMEPeepholeOpt.cpp}::SMEPeepholeOpt::SMEPeepholeOpt</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvemitintrinsics-cpp-/spirvemitintrinsics/#a232fc49250d105385822a549d6f0a444">anonymous{SPIRVEmitIntrinsics.cpp}::SPIRVEmitIntrinsics::SPIRVEmitIntrinsics</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvemitintrinsics-cpp-/spirvemitintrinsics/#afbc342215e95a7c7468dee361ddfab30">anonymous{SPIRVEmitIntrinsics.cpp}::SPIRVEmitIntrinsics::SPIRVEmitIntrinsics</a>, <a href="/web-llvm/docs/api/structs/llvm/spirvemitnonsemanticdi/#a70ad09d5eeee3e5cfb03d3cf793ea098">llvm::SPIRVEmitNonSemanticDI::SPIRVEmitNonSemanticDI</a>, <a href="/web-llvm/docs/api/structs/llvm/spirvemitnonsemanticdi/#a9019892bd75a0ddcb318d1d89dbf7ae9">llvm::SPIRVEmitNonSemanticDI::SPIRVEmitNonSemanticDI</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#a58dcf74500ebec372461f0eea22c0c12">llvm::SPIRVMergeRegionExitTargets::SPIRVMergeRegionExitTargets</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvpostlegalizer-cpp-/spirvpostlegalizer/#aa85542cc4b7dc9fb353a528f2691bf77">anonymous{SPIRVPostLegalizer.cpp}::SPIRVPostLegalizer::SPIRVPostLegalizer</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvprelegalizer-cpp-/spirvprelegalizer/#aadcf1be335eea00af94bdfc2099a677d">anonymous{SPIRVPreLegalizer.cpp}::SPIRVPreLegalizer::SPIRVPreLegalizer</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvpreparefunctions-cpp-/spirvpreparefunctions/#a702cb48ea2b6459a60866c3c779d1978">anonymous{SPIRVPrepareFunctions.cpp}::SPIRVPrepareFunctions::SPIRVPrepareFunctions</a>, <a href="/web-llvm/docs/api/structs/anonymous-spirvregularizer-cpp-/spirvregularizer/#afc96d81c4b2ba8a3e77680438999aa40">anonymous{SPIRVRegularizer.cpp}::SPIRVRegularizer::SPIRVRegularizer</a>, <a href="/web-llvm/docs/api/classes/spirvstripconvergentintrinsics/#ab56bc91051eb49579c4a98c7fe441d0e">SPIRVStripConvergentIntrinsics::SPIRVStripConvergentIntrinsics</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvstructurizer/#a20865863fd3df100ca001e32a0974a05">llvm::SPIRVStructurizer::SPIRVStructurizer</a>, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/sroalegacypass/#a520fcf881f371ac3bae328637f513164">anonymous{SROA.cpp}::SROALegacyPass::SROALegacyPass</a>, <a href="/web-llvm/docs/api/classes/llvm/stackprotector/#a8cc1e7c310c0c735d1c7bde05f9c9e19">llvm::StackProtector::StackProtector</a>, <a href="/web-llvm/docs/api/classes/llvm/stacksafetyglobalinfowrapperpass/#a4e3bf1fdae6f057b11f4f0e675720756">llvm::StackSafetyGlobalInfoWrapperPass::StackSafetyGlobalInfoWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/stacksafetyinfowrapperpass/#adf913280b6425fda0f30353b028d6f18">llvm::StackSafetyInfoWrapperPass::StackSafetyInfoWrapperPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-stackslotcoloring-cpp-/stackslotcoloring/#ae9512b1c46a8951dc6ee4dcff5f1b9ed">anonymous{StackSlotColoring.cpp}::StackSlotColoring::StackSlotColoring</a>, <a href="/web-llvm/docs/api/classes/staticdatasplitter/#a118bc93deee62d93d3d7a8422de792cb">StaticDataSplitter::StaticDataSplitter</a>, <a href="/web-llvm/docs/api/classes/anonymous-straightlinestrengthreduce-cpp-/straightlinestrengthreducelegacypass/#a2766e208be75fbfee4b7ec73e8892570">anonymous{StraightLineStrengthReduce.cpp}::StraightLineStrengthReduceLegacyPass::StraightLineStrengthReduceLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-structurizecfg-cpp-/structurizecfglegacypass/#a06e9447b0c70f1a7ac8289a0e4e75ce7">anonymous{StructurizeCFG.cpp}::StructurizeCFGLegacyPass::StructurizeCFGLegacyPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-sveintrinsicopts-cpp-/sveintrinsicopts/#ab1097f33cee9c890c85be6409d5cee3f">anonymous{SVEIntrinsicOpts.cpp}::SVEIntrinsicOpts::SVEIntrinsicOpts</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzcopyphysregs-cpp-/systemzcopyphysregs/#a1944c0b863c04afdc57192c86ae9ea79">anonymous{SystemZCopyPhysRegs.cpp}::SystemZCopyPhysRegs::SystemZCopyPhysRegs</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzelimcompare-cpp-/systemzelimcompare/#a20d91d50ee3ed73e47f73e4ea32e84ed">anonymous{SystemZElimCompare.cpp}::SystemZElimCompare::SystemZElimCompare</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzldcleanup-cpp-/systemzldcleanup/#a00721ef1df46649dcadbd1dd823e0dc5">anonymous{SystemZLDCleanup.cpp}::SystemZLDCleanup::SystemZLDCleanup</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzlongbranch-cpp-/systemzlongbranch/#aa45f0249e5f699048e88c43c41740c6e">anonymous{SystemZLongBranch.cpp}::SystemZLongBranch::SystemZLongBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzpostrewrite-cpp-/systemzpostrewrite/#a0bb9241c2004e846c42e42b0d92da1c0">anonymous{SystemZPostRewrite.cpp}::SystemZPostRewrite::SystemZPostRewrite</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzshorteninst-cpp-/systemzshorteninst/#af74363ecb5107d472737f829efdc1208">anonymous{SystemZShortenInst.cpp}::SystemZShortenInst::SystemZShortenInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemztdc-cpp-/systemztdcpass/#a7d46fbab6050782583a249a306efed51">anonymous{SystemZTDC.cpp}::SystemZTDCPass::SystemZTDCPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-tailrecursionelimination-cpp-/tailcallelim/#a9f772c65353fc47b952d865625fbcca0">anonymous{TailRecursionElimination.cpp}::TailCallElim::TailCallElim</a>, <a href="/web-llvm/docs/api/classes/anonymous-tailduplication-cpp-/tailduplicatelegacy/#a934a50ae973ad1b9e394a7b85e5fdf76">anonymous{TailDuplication.cpp}::TailDuplicateLegacy::TailDuplicateLegacy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfowrapperpass/#a2ae0a0b09c330d78f1d650178412e58a">llvm::TargetLibraryInfoWrapperPass::TargetLibraryInfoWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfowrapperpass/#a58dfbf8551af5272f647a034ce22298d">llvm::TargetLibraryInfoWrapperPass::TargetLibraryInfoWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfowrapperpass/#a58b8697c66817e86591c490018680a75">llvm::TargetLibraryInfoWrapperPass::TargetLibraryInfoWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#abfe879f7efa8851adee88ab786516d59">llvm::TargetPassConfig::TargetPassConfig</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfowrapperpass/#a1a5eed6801231fa436393e02c7066c71">llvm::TargetTransformInfoWrapperPass::TargetTransformInfoWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfowrapperpass/#af0991b0af26d95c5b45174673eb3fab5">llvm::TargetTransformInfoWrapperPass::TargetTransformInfoWrapperPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-twoaddressinstructionpass-cpp-/twoaddressinstructionlegacypass/#a173a9980ad43325da19b4cfee29ff34a">anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionLegacyPass::TwoAddressInstructionLegacyPass</a>, <a href="/web-llvm/docs/api/classes/llvm/typebasedaawrapperpass/#aa5ab2a4e07366e5401f893adb92e3472">llvm::TypeBasedAAWrapperPass::TypeBasedAAWrapperPass</a>, <a href="/web-llvm/docs/api/classes/llvm/uniformityinfowrapperpass/#ae81170fd0cf990f448567a09b24ebb91">llvm::UniformityInfoWrapperPass::UniformityInfoWrapperPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-unifyloopexits-cpp-/unifyloopexitslegacypass/#ad2c6666f9150c2a42fd6d58dde6fd3b9">anonymous{UnifyLoopExits.cpp}::UnifyLoopExitsLegacyPass::UnifyLoopExitsLegacyPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineinstrbundle-cpp-/unpackmachinebundles/#ad832ae8055e7b4cd7e2e4c0c8db06da3">anonymous{MachineInstrBundle.cpp}::UnpackMachineBundles::UnpackMachineBundles</a>, <a href="/web-llvm/docs/api/classes/anonymous-unreachableblockelim-cpp-/unreachableblockelimlegacypass/#affc7d19bf24cecdba8f17f704746c159">anonymous{UnreachableBlockElim.cpp}::UnreachableBlockElimLegacyPass::UnreachableBlockElimLegacyPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-verifier-cpp-/verifierlegacypass/#a2674765390593577fbf4f1b423d8d4c6">anonymous{Verifier.cpp}::VerifierLegacyPass::VerifierLegacyPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-verifier-cpp-/verifierlegacypass/#a99b4bbb82aa55a4946f6ce2ea88e351b">anonymous{Verifier.cpp}::VerifierLegacyPass::VerifierLegacyPass</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyexceptioninfo/#a01e8781117a022f78c5e81e26d7553c1">llvm::WebAssemblyExceptionInfo::WebAssemblyExceptionInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriterpass-cpp-/writebitcodepass/#a6a1643691e10efd583838a32b7453a15">anonymous{BitcodeWriterPass.cpp}::WriteBitcodePass::WriteBitcodePass</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriterpass-cpp-/writebitcodepass/#af2553864ea402a3ff377a93180b2b563">anonymous{BitcodeWriterPass.cpp}::WriteBitcodePass::WriteBitcodePass</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilwriterpass-cpp-/writedxilpass/#aa6f4f55f0a962c29ed5b33bee378c107">anonymous{DXILWriterPass.cpp}::WriteDXILPass::WriteDXILPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilwriterpass-cpp-/writedxilpass/#a6c3ab59232ddae85d4312becedfccc15">anonymous{DXILWriterPass.cpp}::WriteDXILPass::WriteDXILPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsicslegacypass/#a134c48bbee2b48763ecb43f1f355199a">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsicsLegacyPass::X86LowerAMXIntrinsicsLegacyPass</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcorelowerthreadlocal-cpp-/xcorelowerthreadlocal/#af8774020138076a6d3c51700819c0209">anonymous{XCoreLowerThreadLocal.cpp}::XCoreLowerThreadLocal::XCoreLowerThreadLocal</a> and <a href="/web-llvm/docs/api/structs/anonymous-xrayinstrumentation-cpp-/xrayinstrumentation/#aa3f3000e18c45ceec69b888b0f994176">anonymous{XRayInstrumentation.cpp}::XRayInstrumentation::XRayInstrumentation</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">PassRegistry.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/passregistry-cpp">PassRegistry.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
