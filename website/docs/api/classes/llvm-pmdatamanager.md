---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pmdatamanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PMDataManager` Class

<p><a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> provides the common place to manage the analysis data used by pass managers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PMDataManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">llvm/IR/LegacyPassManagers.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager">CGPassManager</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager">MPPassManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager">MPPassManager</a> manages ModulePasses and function pass managers. <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fppassmanager">FPPassManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/fppassmanager">FPPassManager</a> manages BBPassManagers and FunctionPasses. <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lppassmanager">LPPassManager</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/rgpassmanager">RGPassManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The pass manager to schedule RegionPasses. <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl">FunctionPassManagerImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl">FunctionPassManagerImpl</a> manages FPPassManagers. <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl">PassManagerImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl">PassManagerImpl</a> manages MPPassManagers. <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04fbd0afa6857fe697dd28e93bdfec07">PMDataManager</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95d6e0465dd450047ad442fc7bcec67a">~PMDataManager</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a123a60dab7b9fbe1126ea37c2ec384bd">getAsPass</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35ff10683333230676c1d3c4379b58b1">recordAvailableAnalysis</a> (Pass *P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Augment AvailableAnalysis by adding analysis made available by pass P. <a href="#a35ff10683333230676c1d3c4379b58b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86a4b032c64ea61c59d12929a76c9833">verifyPreservedAnalysis</a> (Pass *P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>verifyPreservedAnalysis – Verify analysis presreved by pass P. <a href="#a86a4b032c64ea61c59d12929a76c9833">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af740891e192aa63a0fbbfe317301cbdb">removeNotPreservedAnalysis</a> (Pass *P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove Analysis that is not preserved by the pass. <a href="#af740891e192aa63a0fbbfe317301cbdb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09ac67e36db813f2a3e69173f7638037">removeDeadPasses</a> (Pass *P, StringRef Msg, enum PassDebuggingString)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove dead passes used by P. <a href="#a09ac67e36db813f2a3e69173f7638037">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ded95b3d23d780dbaf94c287465f69a">freePass</a> (Pass *P, StringRef Msg, enum PassDebuggingString)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove P. <a href="#a9ded95b3d23d780dbaf94c287465f69a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7c7120f48a91e5972592b16ee7fd81b">add</a> (Pass *P, bool ProcessAnalysis=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add pass P into the PassVector. <a href="#ab7c7120f48a91e5972592b16ee7fd81b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a490078b030c2d08d36afe903601d86da">addLowerLevelRequiredPass</a> (Pass *P, Pass *RequiredPass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add RequiredPass into list of lower level passes required by pass P. <a href="#a490078b030c2d08d36afe903601d86da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1901e8348301cd56411b777ecde9cadd">getOnTheFlyPass</a> (Pass *P, AnalysisID PI, Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a49f833e36d81021facdf5f4dbd84de">initializeAnalysisInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize available analysis information. <a href="#a9a49f833e36d81021facdf5f4dbd84de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2fd2b9e450d0a3dc5255cc52151b7ff">preserveHigherLevelAnalysis</a> (Pass *P)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3081121743797ac69560ffa5f381ced">collectRequiredAndUsedAnalyses</a> (SmallVectorImpl&lt; Pass * &gt; &amp;UsedPasses, SmallVectorImpl&lt; AnalysisID &gt; &amp;ReqPassNotAvailable, Pass *P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populate UsedPasses with analysis pass that are used or required by pass P and are available. <a href="#ad3081121743797ac69560ffa5f381ced">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a813e1d4b6102a11cad9963778f889d4d">initializeAnalysisImpl</a> (Pass *P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All Required analyses should be available to the pass as it runs! <a href="#a813e1d4b6102a11cad9963778f889d4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36f417ced43a7724c39f10c67eb7d53d">findAnalysisPass</a> (AnalysisID AID, bool Direction)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the pass that implements Analysis AID. <a href="#a36f417ced43a7724c39f10c67eb7d53d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager">PMTopLevelManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49d2392d2b8e3a2792ea40a12a4be5a4">getTopLevelManager</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61adb3228a4dd2685aeb402e7a4c35d3">setTopLevelManager</a> (PMTopLevelManager *T)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a414502197da1d779b5bed1aa04e65804">getDepth</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d280b5b00775044d94b527cac5ef7bb">setDepth</a> (unsigned newDepth)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ced924c11b3eddbfccd9c186f38a389">dumpLastUses</a> (Pass *P, unsigned Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04147f055683107b057e2c6cb466dc8a">dumpPassArguments</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff93635e4ea28861beb90faece603b3d">dumpPassInfo</a> (Pass *P, enum PassDebuggingString S1, enum PassDebuggingString S2, StringRef Msg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a799e97f6f38435a58b8ecf6a85eb7399">dumpRequiredSet</a> (const Pass *P) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfe9cc105a283f4d7e4e56c6d4440adb">dumpPreservedSet</a> (const Pass *P) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af71955a48208ff25a6c8b5f6f2890417">dumpUsedSet</a> (const Pass *P) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa37440cfb2bd92a0b361cb2a6e1232e2">getNumContainedPasses</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebb">PassManagerType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa877f351376c696b385fdeba9b93a5f1">getPassManagerType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a>, <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8c6ff569cf219c05ed1af66c6d231b0">getAvailableAnalysis</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad469713fc40b5f0baba648041a68dfa7">populateInheritedAnalysis</a> (PMStack &amp;PMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a579d453037e2211a02d8f50a736eff46">initSizeRemarkInfo</a> (Module &amp;M, StringMap&lt; std::pair&lt; unsigned, unsigned &gt; &gt; &amp;FunctionToInstrCount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the initial size of the module if the user has specified that they want remarks for size. <a href="#a579d453037e2211a02d8f50a736eff46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3115ef36979b45874f244f374e79d98">emitInstrCountChangedRemark</a> (Pass *P, Module &amp;M, int64_t Delta, unsigned CountBefore, StringMap&lt; std::pair&lt; unsigned, unsigned &gt; &gt; &amp;FunctionToInstrCount, Function *F=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a remark signifying that the number of IR instructions in the module changed. <a href="#ab3115ef36979b45874f244f374e79d98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38a662fbda7962b4e36e614ac16062c9">isPassDebuggingExecutionsOrMore</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isPassDebuggingExecutionsOrMore - Return true if -debug-pass=Executions or higher is specified. <a href="#a38a662fbda7962b4e36e614ac16062c9">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b16f689a363c8ca84b3fbf1ef0f20f9">dumpAnalysisUsage</a> (StringRef Msg, const Pass *P, const AnalysisUsage::VectorType &amp;Set) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager">PMTopLevelManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa1883b3ebb15e2de80d6f08004a8528">TPM</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a433bcef3e3a89059a3510632b640525d">PassVector</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a>, <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a435cfa509724b08a99f37164f5e755a1">InheritedAnalysis</a>[PMT_Last]</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a>, <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ea0e1c2477e39c82dd993bf4f248547">AvailableAnalysis</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1703f59b046041d6a9a8478232a029f">HigherLevelAnalysis</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cc4c5efd971161655a0dcb1945ebf88">Depth</a> = 0</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> provides the common place to manage the analysis data used by pass managers.</p>

<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PMDataManager() {#a04fbd0afa6857fe697dd28e93bdfec07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PMDataManager::PMDataManager ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>Reference <a href="#a9a49f833e36d81021facdf5f4dbd84de">initializeAnalysisInfo</a>.</p>


<p>Referenced by <a href="#ab7c7120f48a91e5972592b16ee7fd81b">add</a>, <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager/#ae8841a51c6b06a2a29e8e51024e9bc19">anonymous{CallGraphSCCPass.cpp}::CGPassManager::doFinalization</a>, <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager/#a2330998b675c05167dc0a94a9f197599">anonymous{CallGraphSCCPass.cpp}::CGPassManager::doInitialization</a>, <a href="#a04147f055683107b057e2c6cb466dc8a">dumpPassArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager/#a0be65bf69e5ca2c5991ce27de19edfd2">anonymous{CallGraphSCCPass.cpp}::CGPassManager::getAsPMDataManager</a>, <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#aafd4ef7350f9c547bfc34170ebdc1ae8">anonymous{LegacyPassManager.cpp}::MPPassManager::getAsPMDataManager</a>, <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#ae801d35202c8e1bad28a073e68e96250">llvm::FPPassManager::getAsPMDataManager</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a3f743fd12b67ba3cb919e2dfbb90b2e2">llvm::legacy::FunctionPassManagerImpl::getAsPMDataManager</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl/#a8faf41effdf1dda0eaa99b29ef111534">llvm::legacy::PassManagerImpl::getAsPMDataManager</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#ac78b739f40fe028fb23063683a95e541">llvm::LPPassManager::getAsPMDataManager</a>, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a045021659125e4ab94763bf055c936c8">llvm::RGPassManager::getAsPMDataManager</a> and <a href="#ad469713fc40b5f0baba648041a68dfa7">populateInheritedAnalysis</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~PMDataManager() {#a95d6e0465dd450047ad442fc7bcec67a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PMDataManager::~PMDataManager ()</td>
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



<p>Declaration at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 1269 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a433bcef3e3a89059a3510632b640525d">PassVector</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#ab7c7120f48a91e5972592b16ee7fd81b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMDataManager::add (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P, bool ProcessAnalysis=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add pass P into the PassVector.</p>


<p>Update AvailableAnalysis appropriately if ProcessAnalysis is true.</p>


<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 993 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="#a490078b030c2d08d36afe903601d86da">addLowerLevelRequiredPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="#ad3081121743797ac69560ffa5f381ced">collectRequiredAndUsedAnalyses</a>, <a href="/web-llvm/docs/api/classes/llvm/passinfo/#af9ef9100efe3bf6e85f752bff9a14046">llvm::PassInfo::createPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#abbb93ba85eff4d25fd4c3919fddd779c">DM</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a123a60dab7b9fbe1126ea37c2ec384bd">getAsPass</a>, <a href="#a414502197da1d779b5bed1aa04e65804">getDepth</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a433bcef3e3a89059a3510632b640525d">PassVector</a>, <a href="#a04fbd0afa6857fe697dd28e93bdfec07">PMDataManager</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a35ff10683333230676c1d3c4379b58b1">recordAvailableAnalysis</a>, <a href="#af740891e192aa63a0fbbfe317301cbdb">removeNotPreservedAnalysis</a> and <a href="#aaa1883b3ebb15e2de80d6f08004a8528">TPM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callgraphsccpass/#af6897bd5a86b78fc12f93cdfb04c9e6a">llvm::CallGraphSCCPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a748922f143f2da9a13b0b15ff6a3dd22">llvm::FunctionPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a726cb7795e83c8e4fa0ee16af164f62b">llvm::LoopPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/modulepass/#ac1b24f1323a72168f8b9c8610da56949">llvm::ModulePass::assignPassManager</a> and <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a2e838f42384fc223a2768b68ecd12d7e">llvm::RegionPass::assignPassManager</a>.</p>

</div>
</div>

### addLowerLevelRequiredPass() {#a490078b030c2d08d36afe903601d86da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMDataManager::addLowerLevelRequiredPass (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P, <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * RequiredPass)</td>
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

<p>Add RequiredPass into list of lower level passes required by pass P.</p>


<p>RequiredPass is run on the fly by <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Manager when P requests it through getAnalysis interface.</p>


<p>RequiredPass is run on the fly by <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Manager when P requests it through getAnalysis interface. This should be handled by specific pass manager.</p>


<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 1241 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#ad729b39eacf070a9bca84533b3c743bf">llvm::Pass::getPassName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#aaa1883b3ebb15e2de80d6f08004a8528">TPM</a>.</p>


<p>Referenced by <a href="#ab7c7120f48a91e5972592b16ee7fd81b">add</a>.</p>

</div>
</div>

### collectRequiredAndUsedAnalyses() {#ad3081121743797ac69560ffa5f381ced}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMDataManager::collectRequiredAndUsedAnalyses (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * &gt; &amp; UP, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a> &gt; &amp; RP_NotAvail, <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Populate UsedPasses with analysis pass that are used or required by pass P and are available.</p>


<p>Populate UP with analysis pass that are used or required by pass P and are available.</p>


<p>Populate ReqPassNotAvailable with analysis pass that are required by pass P but are not available.</p>


<p>Populate RP_NotAvail with analysis pass that are required by pass P but are not available.</p>


<p>Declaration at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 1068 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="#a36f417ced43a7724c39f10c67eb7d53d">findAnalysisPass</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#a299caaa13ef3566bddb9781064aebdb9">llvm::AnalysisUsage::getRequiredSet</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ad0364d79e9c78f6781cbe243737f5908">llvm::AnalysisUsage::getUsedSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#aaa1883b3ebb15e2de80d6f08004a8528">TPM</a>.</p>


<p>Referenced by <a href="#ab7c7120f48a91e5972592b16ee7fd81b">add</a>.</p>

</div>
</div>

### dumpLastUses() {#a0ced924c11b3eddbfccd9c186f38a389}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMDataManager::dumpLastUses (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P, unsigned Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 1122 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp/#af2826de8d07a024768740aec3f6f99dc">PassDebugging</a> and <a href="#aaa1883b3ebb15e2de80d6f08004a8528">TPM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager/#a4efbb82e436e90c66cc02d1630c0c528">anonymous{CallGraphSCCPass.cpp}::CGPassManager::dumpPassStructure</a>, <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a7c9d902501ce3b0da29040e896cc4a9e">anonymous{LegacyPassManager.cpp}::MPPassManager::dumpPassStructure</a>, <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#aad38713efe44fd73c9bc1da06c0a6ca2">llvm::FPPassManager::dumpPassStructure</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a65a4ed6b290a5d717266585050528047">llvm::LPPassManager::dumpPassStructure</a> and <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a3b0d682de606b00fcd4c6de1748496af">llvm::RGPassManager::dumpPassStructure</a>.</p>

</div>
</div>

### dumpPassArguments() {#a04147f055683107b057e2c6cb466dc8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMDataManager::dumpPassArguments ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 1140 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a433bcef3e3a89059a3510632b640525d">PassVector</a>, <a href="#a04fbd0afa6857fe697dd28e93bdfec07">PMDataManager</a> and <a href="#aaa1883b3ebb15e2de80d6f08004a8528">TPM</a>.</p>

</div>
</div>

### dumpPassInfo() {#aff93635e4ea28861beb90faece603b3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMDataManager::dumpPassInfo (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P, enum <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51">PassDebuggingString</a> S1, enum <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51">PassDebuggingString</a> S2, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Msg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 1149 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51a3f3116bde1268f9e1cd78d9010e4ff26">llvm::EXECUTION_MSG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51a9609c00dded678647639606acf18e62d">llvm::FREEING_MSG</a>, <a href="#a414502197da1d779b5bed1aa04e65804">getDepth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51a72e482d46273910cd5a3a02b0f65647f">llvm::MODIFICATION_MSG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51a95cb7399d5b41b1ddd09c72c0ab53d1c">llvm::ON_CG_MSG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51a4772c843cba89638b5f424e728acadee">llvm::ON_FUNCTION_MSG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51a3e546b8cb5a3e5e11ad3895f0542dfc4">llvm::ON_LOOP_MSG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51a8c70bfed1eb1475d72b6473960678ad1">llvm::ON_MODULE_MSG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51a804f43dbed9325f261c320ab5bb1e73d">llvm::ON_REGION_MSG</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp/#af2826de8d07a024768740aec3f6f99dc">PassDebugging</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>.</p>


<p>Referenced by <a href="#a9ded95b3d23d780dbaf94c287465f69a">freePass</a>, <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a0dec4e6b40dec12d8c6a17040ee73021">llvm::FPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a3255b0b3ab79ad0d1b93ce3da675f240">llvm::LPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a8fcc78c1f34a2d1f636b5880db631439">llvm::RGPassManager::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a15f0d5cca56f2c4cc4f59bc85803233a">anonymous{LegacyPassManager.cpp}::MPPassManager::runOnModule</a>.</p>

</div>
</div>

### dumpPreservedSet() {#adfe9cc105a283f4d7e4e56c6d4440adb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMDataManager::dumpPreservedSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 1199 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af9c346823bed8d8787ced3ce5b0a2ced">llvm::AnalysisUsage::getPreservedSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp/#af2826de8d07a024768740aec3f6f99dc">PassDebugging</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a0dec4e6b40dec12d8c6a17040ee73021">llvm::FPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a3255b0b3ab79ad0d1b93ce3da675f240">llvm::LPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a8fcc78c1f34a2d1f636b5880db631439">llvm::RGPassManager::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a15f0d5cca56f2c4cc4f59bc85803233a">anonymous{LegacyPassManager.cpp}::MPPassManager::runOnModule</a>.</p>

</div>
</div>

### dumpRequiredSet() {#a799e97f6f38435a58b8ecf6a85eb7399}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMDataManager::dumpRequiredSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 1190 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#a299caaa13ef3566bddb9781064aebdb9">llvm::AnalysisUsage::getRequiredSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp/#af2826de8d07a024768740aec3f6f99dc">PassDebugging</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a0dec4e6b40dec12d8c6a17040ee73021">llvm::FPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a3255b0b3ab79ad0d1b93ce3da675f240">llvm::LPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a8fcc78c1f34a2d1f636b5880db631439">llvm::RGPassManager::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a15f0d5cca56f2c4cc4f59bc85803233a">anonymous{LegacyPassManager.cpp}::MPPassManager::runOnModule</a>.</p>

</div>
</div>

### dumpUsedSet() {#af71955a48208ff25a6c8b5f6f2890417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMDataManager::dumpUsedSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 1208 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ad0364d79e9c78f6781cbe243737f5908">llvm::AnalysisUsage::getUsedSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp/#af2826de8d07a024768740aec3f6f99dc">PassDebugging</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a0dec4e6b40dec12d8c6a17040ee73021">llvm::FPPassManager::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a15f0d5cca56f2c4cc4f59bc85803233a">anonymous{LegacyPassManager.cpp}::MPPassManager::runOnModule</a>.</p>

</div>
</div>

### emitInstrCountChangedRemark() {#ab3115ef36979b45874f244f374e79d98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMDataManager::emitInstrCountChangedRemark (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, int64_t Delta, unsigned CountBefore, <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::pair&lt; unsigned, unsigned &gt; &gt; &amp; FunctionToInstrCount, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a remark signifying that the number of IR instructions in the module changed.</p>


<p><span class="doxyComputerOutput">F</span> is optionally passed by passes which run on Functions, and thus always know whether or not a non-empty function is available.</p>


<p><span class="doxyComputerOutput">FunctionToInstrCount</span> maps the name of a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a></span> to a pair. The first member of the pair is the IR count of the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a></span> before running <span class="doxyComputerOutput">P</span>, and the second member is the IR count of the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a></span> after running <span class="doxyComputerOutput">P</span>.</p>


<p>Declaration at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a1d8eb3054fd49a89ff41bc22a48f87e7">llvm::Function::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a0dec4e6b40dec12d8c6a17040ee73021">llvm::FPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a3255b0b3ab79ad0d1b93ce3da675f240">llvm::LPPassManager::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a15f0d5cca56f2c4cc4f59bc85803233a">anonymous{LegacyPassManager.cpp}::MPPassManager::runOnModule</a>.</p>

</div>
</div>

### findAnalysisPass() {#a36f417ced43a7724c39f10c67eb7d53d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass * PMDataManager::findAnalysisPass (<a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a> AID, bool SearchParent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the pass that implements Analysis AID.</p>


<p>If desired pass is not found then return NULL.</p>


<p>Declaration at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 1106 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#aaa1883b3ebb15e2de80d6f08004a8528">TPM</a>.</p>


<p>Referenced by <a href="#ad3081121743797ac69560ffa5f381ced">collectRequiredAndUsedAnalyses</a>, <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a887a8078ca0523b9494da138a800bb65">anonymous{LegacyPassManager.cpp}::MPPassManager::getOnTheFlyPass</a>, <a href="#a813e1d4b6102a11cad9963778f889d4d">initializeAnalysisImpl</a> and <a href="#a86a4b032c64ea61c59d12929a76c9833">verifyPreservedAnalysis</a>.</p>

</div>
</div>

### freePass() {#a9ded95b3d23d780dbaf94c287465f69a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMDataManager::freePass (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Msg, enum DBG_STR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove P.</p>

<p>Declaration at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 975 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="#aff93635e4ea28861beb90faece603b3d">dumpPassInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51a9609c00dded678647639606acf18e62d">llvm::FREEING_MSG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67d0285e03a80731db23ba77d291942d">llvm::getPassTimer</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#a09ac67e36db813f2a3e69173f7638037">removeDeadPasses</a> and <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a3255b0b3ab79ad0d1b93ce3da675f240">llvm::LPPassManager::runOnFunction</a>.</p>

</div>
</div>

### getAsPass() {#a123a60dab7b9fbe1126ea37c2ec384bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Pass * llvm::PMDataManager::getAsPass ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#ab7c7120f48a91e5972592b16ee7fd81b">add</a>.</p>

</div>
</div>

### getAvailableAnalysis() {#ab8c6ff569cf219c05ed1af66c6d231b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; AnalysisID, Pass * &gt; * llvm::PMDataManager::getAvailableAnalysis ()</td>
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



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

</div>
</div>

### getDepth() {#a414502197da1d779b5bed1aa04e65804}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PMDataManager::getDepth ()</td>
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



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>Referenced by <a href="#ab7c7120f48a91e5972592b16ee7fd81b">add</a>, <a href="#aff93635e4ea28861beb90faece603b3d">dumpPassInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a9579e452cf1995463c7e29dfeae5cc2a">llvm::PMStack::push</a> and <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a5eab64f06a4196bd59b9b19251eefddb">llvm::PMTopLevelManager::setLastUser</a>.</p>

</div>
</div>

### getNumContainedPasses() {#aa37440cfb2bd92a0b361cb2a6e1232e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PMDataManager::getNumContainedPasses ()</td>
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



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>Reference <a href="#a433bcef3e3a89059a3510632b640525d">PassVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#af50df32b0a6280a411aaadd15ee8932d">llvm::FPPassManager::cleanup</a>, <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager/#ae8841a51c6b06a2a29e8e51024e9bc19">anonymous{CallGraphSCCPass.cpp}::CGPassManager::doFinalization</a>, <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a5d3dbe08c733714a84c9f79714007327">llvm::FPPassManager::doFinalization</a>, <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager/#a2330998b675c05167dc0a94a9f197599">anonymous{CallGraphSCCPass.cpp}::CGPassManager::doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a1ea063b9aef63a724f2f14b2e8d2be0e">llvm::FPPassManager::doInitialization</a>, <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager/#a4efbb82e436e90c66cc02d1630c0c528">anonymous{CallGraphSCCPass.cpp}::CGPassManager::dumpPassStructure</a>, <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a7c9d902501ce3b0da29040e896cc4a9e">anonymous{LegacyPassManager.cpp}::MPPassManager::dumpPassStructure</a>, <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#aad38713efe44fd73c9bc1da06c0a6ca2">llvm::FPPassManager::dumpPassStructure</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a65a4ed6b290a5d717266585050528047">llvm::LPPassManager::dumpPassStructure</a>, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a3b0d682de606b00fcd4c6de1748496af">llvm::RGPassManager::dumpPassStructure</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a35df5259dc1bc4f526a32a2d18cb3f59">llvm::legacy::FunctionPassManagerImpl::releaseMemoryOnTheFly</a>, <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a0dec4e6b40dec12d8c6a17040ee73021">llvm::FPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a3255b0b3ab79ad0d1b93ce3da675f240">llvm::LPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a8fcc78c1f34a2d1f636b5880db631439">llvm::RGPassManager::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a15f0d5cca56f2c4cc4f59bc85803233a">anonymous{LegacyPassManager.cpp}::MPPassManager::runOnModule</a>.</p>

</div>
</div>

### getOnTheFlyPass() {#a1901e8348301cd56411b777ecde9cadd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; Pass *, bool &gt; PMDataManager::getOnTheFlyPass (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P, <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a> PI, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Declaration at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 1263 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### getPassManagerType() {#aa877f351376c696b385fdeba9b93a5f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual PassManagerType llvm::PMDataManager::getPassManagerType ()</td>
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



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebba608a70bb40817f666f2d174f43d1c9d5">llvm::PMT_Unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callgraphsccpass/#af6897bd5a86b78fc12f93cdfb04c9e6a">llvm::CallGraphSCCPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a748922f143f2da9a13b0b15ff6a3dd22">llvm::FunctionPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a726cb7795e83c8e4fa0ee16af164f62b">llvm::LoopPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/modulepass/#ac1b24f1323a72168f8b9c8610da56949">llvm::ModulePass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a2e838f42384fc223a2768b68ecd12d7e">llvm::RegionPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager/#ae8841a51c6b06a2a29e8e51024e9bc19">anonymous{CallGraphSCCPass.cpp}::CGPassManager::doFinalization</a>, <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager/#a2330998b675c05167dc0a94a9f197599">anonymous{CallGraphSCCPass.cpp}::CGPassManager::doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a0d8f33dd4b6aa73a06a2f7dd50cb3d68">llvm::LoopPass::preparePassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a2713ee0f2a6f78c9084cd7fc55afb303">llvm::RegionPass::preparePassManager</a> and <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a9579e452cf1995463c7e29dfeae5cc2a">llvm::PMStack::push</a>.</p>

</div>
</div>

### getTopLevelManager() {#a49d2392d2b8e3a2792ea40a12a4be5a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PMTopLevelManager * llvm::PMDataManager::getTopLevelManager ()</td>
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



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>Reference <a href="#aaa1883b3ebb15e2de80d6f08004a8528">TPM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callgraphsccpass/#af6897bd5a86b78fc12f93cdfb04c9e6a">llvm::CallGraphSCCPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a748922f143f2da9a13b0b15ff6a3dd22">llvm::FunctionPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a726cb7795e83c8e4fa0ee16af164f62b">llvm::LoopPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a2e838f42384fc223a2768b68ecd12d7e">llvm::RegionPass::assignPassManager</a> and <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a9579e452cf1995463c7e29dfeae5cc2a">llvm::PMStack::push</a>.</p>

</div>
</div>

### initializeAnalysisImpl() {#a813e1d4b6102a11cad9963778f889d4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMDataManager::initializeAnalysisImpl (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All Required analyses should be available to the pass as it runs!</p>


<p>Here we fill in the AnalysisImpls member of the pass so that it can successfully use the getAnalysis() method to retrieve the implementations it needs.</p>


<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 1089 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisresolver/#a01d493bec362b20703d57138b6873382">llvm::AnalysisResolver::addAnalysisImplsPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a36f417ced43a7724c39f10c67eb7d53d">findAnalysisPass</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#a299caaa13ef3566bddb9781064aebdb9">llvm::AnalysisUsage::getRequiredSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#aaa1883b3ebb15e2de80d6f08004a8528">TPM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a0dec4e6b40dec12d8c6a17040ee73021">llvm::FPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a3255b0b3ab79ad0d1b93ce3da675f240">llvm::LPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a8fcc78c1f34a2d1f636b5880db631439">llvm::RGPassManager::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a15f0d5cca56f2c4cc4f59bc85803233a">anonymous{LegacyPassManager.cpp}::MPPassManager::runOnModule</a>.</p>

</div>
</div>

### initializeAnalysisInfo() {#a9a49f833e36d81021facdf5f4dbd84de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PMDataManager::initializeAnalysisInfo ()</td>
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

<p>Initialize available analysis information.</p>

<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>Reference <a href="#a435cfa509724b08a99f37164f5e755a1">InheritedAnalysis</a>.</p>


<p>Referenced by <a href="#a04fbd0afa6857fe697dd28e93bdfec07">PMDataManager</a> and <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a4953e532d6f86ceb1f38ee2503be46a0">llvm::PMStack::pop</a>.</p>

</div>
</div>

### initSizeRemarkInfo() {#a579d453037e2211a02d8f50a736eff46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned PMDataManager::initSizeRemarkInfo (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::pair&lt; unsigned, unsigned &gt; &gt; &amp; FunctionToInstrCount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the initial size of the module if the user has specified that they want remarks for size.</p>


<p>Returns 0 if the remark was not requested.</p>


<p>Declaration at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp/#acc16edf21eddec420cd4b27adb3111c6">InstrCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a0dec4e6b40dec12d8c6a17040ee73021">llvm::FPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a3255b0b3ab79ad0d1b93ce3da675f240">llvm::LPPassManager::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a15f0d5cca56f2c4cc4f59bc85803233a">anonymous{LegacyPassManager.cpp}::MPPassManager::runOnModule</a>.</p>

</div>
</div>

### populateInheritedAnalysis() {#ad469713fc40b5f0baba648041a68dfa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PMDataManager::populateInheritedAnalysis (<a href="/web-llvm/docs/api/classes/llvm/pmstack">PMStack</a> &amp; PMS)</td>
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



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>References <a href="#a435cfa509724b08a99f37164f5e755a1">InheritedAnalysis</a> and <a href="#a04fbd0afa6857fe697dd28e93bdfec07">PMDataManager</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a748922f143f2da9a13b0b15ff6a3dd22">llvm::FunctionPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a726cb7795e83c8e4fa0ee16af164f62b">llvm::LoopPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a2e838f42384fc223a2768b68ecd12d7e">llvm::RegionPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a0dec4e6b40dec12d8c6a17040ee73021">llvm::FPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a3255b0b3ab79ad0d1b93ce3da675f240">llvm::LPPassManager::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a8fcc78c1f34a2d1f636b5880db631439">llvm::RGPassManager::runOnFunction</a>.</p>

</div>
</div>

### preserveHigherLevelAnalysis() {#aa2fd2b9e450d0a3dc5255cc52151b7ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PMDataManager::preserveHigherLevelAnalysis (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 874 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af9c346823bed8d8787ced3ce5b0a2ced">llvm::AnalysisUsage::getPreservedSet</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af25c3e35aa8152adb82963b80be929c0">llvm::AnalysisUsage::getPreservesAll</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#aaa1883b3ebb15e2de80d6f08004a8528">TPM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/looppass/#a0d8f33dd4b6aa73a06a2f7dd50cb3d68">llvm::LoopPass::preparePassManager</a> and <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a2713ee0f2a6f78c9084cd7fc55afb303">llvm::RegionPass::preparePassManager</a>.</p>

</div>
</div>

### recordAvailableAnalysis() {#a35ff10683333230676c1d3c4379b58b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMDataManager::recordAvailableAnalysis (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Augment AvailableAnalysis by adding analysis made available by pass P.</p>


<p>Augement AvailableAnalysis by adding analysis made available by pass P.</p>


<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 866 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#ab7c7120f48a91e5972592b16ee7fd81b">add</a>, <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a0dec4e6b40dec12d8c6a17040ee73021">llvm::FPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a3255b0b3ab79ad0d1b93ce3da675f240">llvm::LPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a8fcc78c1f34a2d1f636b5880db631439">llvm::RGPassManager::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a15f0d5cca56f2c4cc4f59bc85803233a">anonymous{LegacyPassManager.cpp}::MPPassManager::runOnModule</a>.</p>

</div>
</div>

### removeDeadPasses() {#a09ac67e36db813f2a3e69173f7638037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMDataManager::removeDeadPasses (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Msg, enum DBG_STR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove dead passes used by P.</p>


<p>Remove analysis passes that are not used any longer.</p>


<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 954 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a9ded95b3d23d780dbaf94c287465f69a">freePass</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp/#af2826de8d07a024768740aec3f6f99dc">PassDebugging</a> and <a href="#aaa1883b3ebb15e2de80d6f08004a8528">TPM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a0dec4e6b40dec12d8c6a17040ee73021">llvm::FPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a3255b0b3ab79ad0d1b93ce3da675f240">llvm::LPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a8fcc78c1f34a2d1f636b5880db631439">llvm::RGPassManager::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a15f0d5cca56f2c4cc4f59bc85803233a">anonymous{LegacyPassManager.cpp}::MPPassManager::runOnModule</a>.</p>

</div>
</div>

### removeNotPreservedAnalysis() {#af740891e192aa63a0fbbfe317301cbdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMDataManager::removeNotPreservedAnalysis (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove Analysis that is not preserved by the pass.</p>


<p>Remove Analysis not preserved by <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> P.</p>


<p>Declaration at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 908 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#ad729b39eacf070a9bca84533b3c743bf">llvm::Pass::getPassName</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af9c346823bed8d8787ced3ce5b0a2ced">llvm::AnalysisUsage::getPreservedSet</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af25c3e35aa8152adb82963b80be929c0">llvm::AnalysisUsage::getPreservesAll</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a435cfa509724b08a99f37164f5e755a1">InheritedAnalysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp/#af2826de8d07a024768740aec3f6f99dc">PassDebugging</a> and <a href="#aaa1883b3ebb15e2de80d6f08004a8528">TPM</a>.</p>


<p>Referenced by <a href="#ab7c7120f48a91e5972592b16ee7fd81b">add</a>, <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a0dec4e6b40dec12d8c6a17040ee73021">llvm::FPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a3255b0b3ab79ad0d1b93ce3da675f240">llvm::LPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a8fcc78c1f34a2d1f636b5880db631439">llvm::RGPassManager::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a15f0d5cca56f2c4cc4f59bc85803233a">anonymous{LegacyPassManager.cpp}::MPPassManager::runOnModule</a>.</p>

</div>
</div>

### setDepth() {#a1d280b5b00775044d94b527cac5ef7bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PMDataManager::setDepth (unsigned newDepth)</td>
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



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a9579e452cf1995463c7e29dfeae5cc2a">llvm::PMStack::push</a>.</p>

</div>
</div>

### setTopLevelManager() {#a61adb3228a4dd2685aeb402e7a4c35d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PMDataManager::setTopLevelManager (<a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager">PMTopLevelManager</a> * T)</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#aaa1883b3ebb15e2de80d6f08004a8528">TPM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a452b3946fae687fe6ab129970b5f9c75">anonymous{LegacyPassManager.cpp}::MPPassManager::addLowerLevelRequiredPass</a>, <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#adc80432cc11960e6cf7fcae1a64c07a5">llvm::PMTopLevelManager::PMTopLevelManager</a> and <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a9579e452cf1995463c7e29dfeae5cc2a">llvm::PMStack::push</a>.</p>

</div>
</div>

### verifyPreservedAnalysis() {#a86a4b032c64ea61c59d12929a76c9833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMDataManager::verifyPreservedAnalysis (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>verifyPreservedAnalysis – Verify analysis presreved by pass P.</p>


<p>verifyPreservedAnalysis – Verify analysis preserved by pass P.</p>


<p>Declaration at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 890 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="#a36f417ced43a7724c39f10c67eb7d53d">findAnalysisPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67d0285e03a80731db23ba77d291942d">llvm::getPassTimer</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af9c346823bed8d8787ced3ce5b0a2ced">llvm::AnalysisUsage::getPreservedSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#aaa1883b3ebb15e2de80d6f08004a8528">TPM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a0dec4e6b40dec12d8c6a17040ee73021">llvm::FPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a3255b0b3ab79ad0d1b93ce3da675f240">llvm::LPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a8fcc78c1f34a2d1f636b5880db631439">llvm::RGPassManager::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a15f0d5cca56f2c4cc4f59bc85803233a">anonymous{LegacyPassManager.cpp}::MPPassManager::runOnModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### isPassDebuggingExecutionsOrMore() {#a38a662fbda7962b4e36e614ac16062c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PMDataManager::isPassDebuggingExecutionsOrMore ()</td>
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

<p>isPassDebuggingExecutionsOrMore - Return true if -debug-pass=Executions or higher is specified.</p>

<p>Declaration at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp/#af2826de8d07a024768740aec3f6f99dc">PassDebugging</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a8fcc78c1f34a2d1f636b5880db631439">llvm::RGPassManager::runOnFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### dumpAnalysisUsage() {#a3b16f689a363c8ca84b3fbf1ef0f20f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMDataManager::dumpAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Msg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#aca5945c84f7ab80d6fb87b09c633aff9">AnalysisUsage::VectorType</a> &amp; Set)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 1217 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### InheritedAnalysis {#a435cfa509724b08a99f37164f5e755a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;AnalysisID, Pass *&gt;* llvm::PMDataManager::InheritedAnalysis[PMT_Last]</td>
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



<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>Referenced by <a href="#a9a49f833e36d81021facdf5f4dbd84de">initializeAnalysisInfo</a>, <a href="#ad469713fc40b5f0baba648041a68dfa7">populateInheritedAnalysis</a> and <a href="#af740891e192aa63a0fbbfe317301cbdb">removeNotPreservedAnalysis</a>.</p>

</div>
</div>

### PassVector {#a433bcef3e3a89059a3510632b640525d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Pass *, 16&gt; llvm::PMDataManager::PassVector</td>
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



<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>Referenced by <a href="#ab7c7120f48a91e5972592b16ee7fd81b">add</a>, <a href="#a04147f055683107b057e2c6cb466dc8a">dumpPassArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager/#a4b1bfae8468f5272b17dbfa99b21d8cf">anonymous{CallGraphSCCPass.cpp}::CGPassManager::getContainedPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a304af141af26777cf00f13742ebb8bd8">anonymous{LegacyPassManager.cpp}::MPPassManager::getContainedPass</a>, <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a76beb9efcf5d12a8fbe116ee2b8f56f0">llvm::FPPassManager::getContainedPass</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#aec82063d9514c697c7a721f257740646">llvm::LPPassManager::getContainedPass</a>, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a41d8be8eb594fafcec7d5f06630783e5">llvm::RGPassManager::getContainedPass</a>, <a href="#aa37440cfb2bd92a0b361cb2a6e1232e2">getNumContainedPasses</a> and <a href="#a95d6e0465dd450047ad442fc7bcec67a">~PMDataManager</a>.</p>

</div>
</div>

### TPM {#aaa1883b3ebb15e2de80d6f08004a8528}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PMTopLevelManager* llvm::PMDataManager::TPM = nullptr</td>
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



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>Referenced by <a href="#ab7c7120f48a91e5972592b16ee7fd81b">add</a>, <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a452b3946fae687fe6ab129970b5f9c75">anonymous{LegacyPassManager.cpp}::MPPassManager::addLowerLevelRequiredPass</a>, <a href="#a490078b030c2d08d36afe903601d86da">addLowerLevelRequiredPass</a>, <a href="#ad3081121743797ac69560ffa5f381ced">collectRequiredAndUsedAnalyses</a>, <a href="#a0ced924c11b3eddbfccd9c186f38a389">dumpLastUses</a>, <a href="#a04147f055683107b057e2c6cb466dc8a">dumpPassArguments</a>, <a href="#a36f417ced43a7724c39f10c67eb7d53d">findAnalysisPass</a>, <a href="#a49d2392d2b8e3a2792ea40a12a4be5a4">getTopLevelManager</a>, <a href="#a813e1d4b6102a11cad9963778f889d4d">initializeAnalysisImpl</a>, <a href="#aa2fd2b9e450d0a3dc5255cc52151b7ff">preserveHigherLevelAnalysis</a>, <a href="#a09ac67e36db813f2a3e69173f7638037">removeDeadPasses</a>, <a href="#af740891e192aa63a0fbbfe317301cbdb">removeNotPreservedAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a0dec4e6b40dec12d8c6a17040ee73021">llvm::FPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a3255b0b3ab79ad0d1b93ce3da675f240">llvm::LPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a8fcc78c1f34a2d1f636b5880db631439">llvm::RGPassManager::runOnFunction</a>, <a href="#a61adb3228a4dd2685aeb402e7a4c35d3">setTopLevelManager</a> and <a href="#a86a4b032c64ea61c59d12929a76c9833">verifyPreservedAnalysis</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AvailableAnalysis {#a0ea0e1c2477e39c82dd993bf4f248547}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;AnalysisID, Pass*&gt; llvm::PMDataManager::AvailableAnalysis</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

</div>
</div>

### Depth {#a4cc4c5efd971161655a0dcb1945ebf88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PMDataManager::Depth = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

</div>
</div>

### HigherLevelAnalysis {#ad1703f59b046041d6a9a8478232a029f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Pass *, 16&gt; llvm::PMDataManager::HigherLevelAnalysis</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
