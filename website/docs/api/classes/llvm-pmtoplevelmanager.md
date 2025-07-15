---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pmtoplevelmanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PMTopLevelManager` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager">PMTopLevelManager</a> manages LastUser info and collects common APIs used by top level pass managers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PMTopLevelManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">llvm/IR/LegacyPassManagers.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc80432cc11960e6cf7fcae1a64c07a5">PMTopLevelManager</a> (PMDataManager *PMDM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize top level manager. Create first pass manager. <a href="#adc80432cc11960e6cf7fcae1a64c07a5">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f398de037a18cdec4f7b21b7fb68f8c">~PMTopLevelManager</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destructor. <a href="#a5f398de037a18cdec4f7b21b7fb68f8c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fb719fc8062d116b93091d9c9addd43">schedulePass</a> (Pass *P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Schedule pass P for execution. <a href="#a5fb719fc8062d116b93091d9c9addd43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eab64f06a4196bd59b9b19251eefddb">setLastUser</a> (ArrayRef&lt; Pass * &gt; AnalysisPasses, Pass *P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set pass P as the last user of the given analysis passes. <a href="#a5eab64f06a4196bd59b9b19251eefddb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae14832740da89a471e377bb12e10969c">collectLastUses</a> (SmallVectorImpl&lt; Pass * &gt; &amp;LastUses, Pass *P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect passes whose last user is P. <a href="#ae14832740da89a471e377bb12e10969c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a941f554aafc09331b7f599a04d85dbe7">findAnalysisPass</a> (AnalysisID AID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the pass that implements Analysis AID. <a href="#a941f554aafc09331b7f599a04d85dbe7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43fed8d1dfacc9362ed5b08f841782f8">findAnalysisPassInfo</a> (AnalysisID AID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> for an analysis. <a href="#a43fed8d1dfacc9362ed5b08f841782f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2b6f31b009d485e411860e7547055c4">findAnalysisUsage</a> (Pass *P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find analysis usage information for the pass P. <a href="#aa2b6f31b009d485e411860e7547055c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3233c9a18e7b82a59db53af066d5af58">addImmutablePass</a> (ImmutablePass *P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add immutable pass and initialize it. <a href="#a3233c9a18e7b82a59db53af066d5af58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/immutablepass">ImmutablePass</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8b44da91c0acd3bd2263f5f1c071696">getImmutablePasses</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb7ec36e2caf7a586e2be1e015929804">addPassManager</a> (PMDataManager *Manager)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a022d0f8afbecd48458168e3a419d2048">addIndirectPassManager</a> (PMDataManager *Manager)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa58716ef5ab4c044f1f90f257bf91e6a">dumpPasses</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bcf6682702cbde1eeeb006b7e49cf62">dumpArguments</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3b4cd4b801ce3601afffa97acc8991d">getNumContainedManagers</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad54000cb15d4de5f1cccee55f29e6ab1">initializeAllAnalysisInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4d26e8879a2062e2d8129db00812fd1">getAsPMDataManager</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a565a4c914e22ce9dad3114f9025d61fd">getTopLevelPassManagerType</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pmstack">PMStack</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2156f58ba16adbf970667ecd0d44ca7">activeStack</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62f1c43ba247efb9b876c45fe2356eea">PassManagers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of pass managers. <a href="#a62f1c43ba247efb9b876c45fe2356eea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e3f4d099129bf2be05f3932d5bf4805">IndirectPassManagers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of pass managers that are not directly maintained by this pass manager. <a href="#a3e3f4d099129bf2be05f3932d5bf4805">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *, <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2991f1a586d6214c421a870d1a812d8f">LastUser</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *, 8 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad75178184a1aabec905e157f8dae3044">InversedLastUser</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/immutablepass">ImmutablePass</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af71ca886817b120185d228c72572fba8">ImmutablePasses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Immutable passes are managed by top level manager. <a href="#af71ca886817b120185d228c72572fba8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a>, <a href="/web-llvm/docs/api/classes/llvm/immutablepass">ImmutablePass</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeee5f88104f458cbaf8a96491c0124e">ImmutablePassMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to immutable passes. <a href="#aaeee5f88104f458cbaf8a96491c0124e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; AUFoldingSetNode &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0b942a35f89d358766a1b12dfbe9902">UniqueAnalysisUsages</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; AUFoldingSetNode &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6b1d4e6e8f429210dc82f4b7edb346c">AUFoldingSetNodeAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *, <a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe3014707efa0bdacc1cfcecd5d5c4d6">AnUsageMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0750f50b09663e4c404254ee3422dfdb">AnalysisPassInfos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> objects found via analysis IDs and in this top level manager. <a href="#a0750f50b09663e4c404254ee3422dfdb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager">PMTopLevelManager</a> manages LastUser info and collects common APIs used by top level pass managers.</p>

<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### PMTopLevelManager() {#adc80432cc11960e6cf7fcae1a64c07a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PMTopLevelManager::PMTopLevelManager (<a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> * PMDM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize top level manager. Create first pass manager.</p>

<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="#ac2156f58ba16adbf970667ecd0d44ca7">activeStack</a>, <a href="#acb7ec36e2caf7a586e2be1e015929804">addPassManager</a> and <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a61adb3228a4dd2685aeb402e7a4c35d3">llvm::PMDataManager::setTopLevelManager</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a316f684869eb05f6ea093331e0fa05ae">llvm::legacy::FunctionPassManagerImpl::FunctionPassManagerImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl/#a99fe001798819fa40f548ade3fde03df">llvm::legacy::PassManagerImpl::PassManagerImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~PMTopLevelManager() {#a5f398de037a18cdec4f7b21b7fb68f8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PMTopLevelManager::~PMTopLevelManager ()</td>
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

<p>Destructor.</p>

<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 854 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a62f1c43ba247efb9b876c45fe2356eea">PassManagers</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addImmutablePass() {#a3233c9a18e7b82a59db53af066d5af58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMTopLevelManager::addImmutablePass (<a href="/web-llvm/docs/api/classes/llvm/immutablepass">ImmutablePass</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add immutable pass and initialize it.</p>

<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 799 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a5fb719fc8062d116b93091d9c9addd43">schedulePass</a>.</p>

</div>
</div>

### addIndirectPassManager() {#a022d0f8afbecd48458168e3a419d2048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PMTopLevelManager::addIndirectPassManager (<a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> * Manager)</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callgraphsccpass/#af6897bd5a86b78fc12f93cdfb04c9e6a">llvm::CallGraphSCCPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a748922f143f2da9a13b0b15ff6a3dd22">llvm::FunctionPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a726cb7795e83c8e4fa0ee16af164f62b">llvm::LoopPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a2e838f42384fc223a2768b68ecd12d7e">llvm::RegionPass::assignPassManager</a> and <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a9579e452cf1995463c7e29dfeae5cc2a">llvm::PMStack::push</a>.</p>

</div>
</div>

### addPassManager() {#acb7ec36e2caf7a586e2be1e015929804}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PMTopLevelManager::addPassManager (<a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> * Manager)</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>Reference <a href="#a62f1c43ba247efb9b876c45fe2356eea">PassManagers</a>.</p>


<p>Referenced by <a href="#adc80432cc11960e6cf7fcae1a64c07a5">PMTopLevelManager</a>.</p>

</div>
</div>

### collectLastUses() {#ae14832740da89a471e377bb12e10969c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMTopLevelManager::collectLastUses (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * &gt; &amp; LastUses, <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect passes whose last user is P.</p>

<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 615 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### dumpArguments() {#a9bcf6682702cbde1eeeb006b7e49cf62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMTopLevelManager::dumpArguments ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 828 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a1161e5a4e753384aaba3a8e4533c4261">Arguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a43fed8d1dfacc9362ed5b08f841782f8">findAnalysisPassInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp/#af2826de8d07a024768740aec3f6f99dc">PassDebugging</a> and <a href="#a62f1c43ba247efb9b876c45fe2356eea">PassManagers</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a3629e481a2aaf6f1f0bebcc4439185e8">llvm::legacy::FunctionPassManagerImpl::doInitialization</a> and <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl/#a87ae04b5379a8cdfe46595e2b00a182d">llvm::legacy::PassManagerImpl::run</a>.</p>

</div>
</div>

### dumpPasses() {#aa58716ef5ab4c044f1f90f257bf91e6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMTopLevelManager::dumpPasses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 811 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pass/#ad2f0576ef7c9c4af40e35001c81f4922">llvm::Pass::dumpPassStructure</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp/#af2826de8d07a024768740aec3f6f99dc">PassDebugging</a> and <a href="#a62f1c43ba247efb9b876c45fe2356eea">PassManagers</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a3629e481a2aaf6f1f0bebcc4439185e8">llvm::legacy::FunctionPassManagerImpl::doInitialization</a> and <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl/#a87ae04b5379a8cdfe46595e2b00a182d">llvm::legacy::PassManagerImpl::run</a>.</p>

</div>
</div>

### findAnalysisPass() {#a941f554aafc09331b7f599a04d85dbe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass * PMTopLevelManager::findAnalysisPass (<a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a> AID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the pass that implements Analysis AID.</p>


<p>Search immutable passes and all pass managers. If desired pass is not found then return NULL.</p>


<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 769 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a62f1c43ba247efb9b876c45fe2356eea">PassManagers</a>.</p>


<p>Referenced by <a href="#a5fb719fc8062d116b93091d9c9addd43">schedulePass</a> and <a href="#a5eab64f06a4196bd59b9b19251eefddb">setLastUser</a>.</p>

</div>
</div>

### findAnalysisPassInfo() {#a43fed8d1dfacc9362ed5b08f841782f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PassInfo * PMTopLevelManager::findAnalysisPassInfo (<a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a> AID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve the <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> for an analysis.</p>

<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 788 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp/#a8fd5fd11f1d85fee7e28a197e915aa0d">getPassInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a58f089b4fc400d1bfb6f2e6d21a00dbb">llvm::PassRegistry::getPassInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>.</p>


<p>Referenced by <a href="#a9bcf6682702cbde1eeeb006b7e49cf62">dumpArguments</a> and <a href="#a5fb719fc8062d116b93091d9c9addd43">schedulePass</a>.</p>

</div>
</div>

### findAnalysisUsage() {#aa2b6f31b009d485e411860e7547055c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisUsage * PMTopLevelManager::findAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find analysis usage information for the pass P.</p>

<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a5fb719fc8062d116b93091d9c9addd43">schedulePass</a> and <a href="#a5eab64f06a4196bd59b9b19251eefddb">setLastUser</a>.</p>

</div>
</div>

### getImmutablePasses() {#ad8b44da91c0acd3bd2263f5f1c071696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; ImmutablePass * &gt; &amp; llvm::PMTopLevelManager::getImmutablePasses ()</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a9e96a5db4aa64e696dfee55356b7f048">llvm::legacy::FunctionPassManagerImpl::doFinalization</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a3629e481a2aaf6f1f0bebcc4439185e8">llvm::legacy::FunctionPassManagerImpl::doInitialization</a> and <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl/#a87ae04b5379a8cdfe46595e2b00a182d">llvm::legacy::PassManagerImpl::run</a>.</p>

</div>
</div>

### schedulePass() {#a5fb719fc8062d116b93091d9c9addd43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMTopLevelManager::schedulePass (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Schedule pass P for execution.</p>


<p>Make sure that passes required by P are run before P is run. Update analysis info maintained by the manager. Remove dead passes. This is a recursive function.</p>


<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 661 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="#ac2156f58ba16adbf970667ecd0d44ca7">activeStack</a>, <a href="#a3233c9a18e7b82a59db53af066d5af58">addImmutablePass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a798ee7d328442bd53b66267635788770">llvm::Pass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/passinfo/#af9ef9100efe3bf6e85f752bff9a14046">llvm::PassInfo::createPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#abbb93ba85eff4d25fd4c3919fddd779c">DM</a>, <a href="#a941f554aafc09331b7f599a04d85dbe7">findAnalysisPass</a>, <a href="#a43fed8d1dfacc9362ed5b08f841782f8">findAnalysisPassInfo</a>, <a href="#aa2b6f31b009d485e411860e7547055c4">findAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/passinfo/#aa87dd67a6b8cac7c29fc520f5475882e">llvm::PassInfo::getPassArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#ad729b39eacf070a9bca84533b3c743bf">llvm::Pass::getPassName</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a05cd3cab5ce2e13c7636ef21adef6e8d">llvm::Pass::getPotentialPassManagerType</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#a299caaa13ef3566bddb9781064aebdb9">llvm::AnalysisUsage::getRequiredSet</a>, <a href="/web-llvm/docs/api/classes/llvm/passinfo/#a6f599935d3a65631f812392f94bb5775">llvm::PassInfo::isAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a5fb719fc8062d116b93091d9c9addd43">schedulePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad9249f0a4443bb33fb0789525d29cf01">llvm::shouldPrintAfterPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad5c2fb6b85448597174b4289f8678110">llvm::shouldPrintBeforePass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a11484d56af409b65a713965e27296130">llvm::legacy::FunctionPassManagerImpl::add</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl/#a34d27e9f9118eddcf4ee25bd89991eb4">llvm::legacy::PassManagerImpl::add</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphsccpass/#af6897bd5a86b78fc12f93cdfb04c9e6a">llvm::CallGraphSCCPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a726cb7795e83c8e4fa0ee16af164f62b">llvm::LoopPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a2e838f42384fc223a2768b68ecd12d7e">llvm::RegionPass::assignPassManager</a> and <a href="#a5fb719fc8062d116b93091d9c9addd43">schedulePass</a>.</p>

</div>
</div>

### setLastUser() {#a5eab64f06a4196bd59b9b19251eefddb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMTopLevelManager::setLastUser (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * &gt; AnalysisPasses, <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set pass P as the last user of the given analysis passes.</p>

<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a941f554aafc09331b7f599a04d85dbe7">findAnalysisPass</a>, <a href="#aa2b6f31b009d485e411860e7547055c4">findAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a414502197da1d779b5bed1aa04e65804">llvm::PMDataManager::getDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisresolver/#a2cfbfb9f4e4110382ff2c188a902668a">llvm::AnalysisResolver::getPMDataManager</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#aab8bb94b2d54bff44ec50eade145bd08">llvm::AnalysisUsage::getRequiredTransitiveSet</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a969c082f66671df288441bbad9ca87db">llvm::Pass::getResolver</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a5eab64f06a4196bd59b9b19251eefddb">setLastUser</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a452b3946fae687fe6ab129970b5f9c75">anonymous{LegacyPassManager.cpp}::MPPassManager::addLowerLevelRequiredPass</a> and <a href="#a5eab64f06a4196bd59b9b19251eefddb">setLastUser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getNumContainedManagers() {#ad3b4cd4b801ce3601afffa97acc8991d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PMTopLevelManager::getNumContainedManagers ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>Reference <a href="#a62f1c43ba247efb9b876c45fe2356eea">PassManagers</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a9e96a5db4aa64e696dfee55356b7f048">llvm::legacy::FunctionPassManagerImpl::doFinalization</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a3629e481a2aaf6f1f0bebcc4439185e8">llvm::legacy::FunctionPassManagerImpl::doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a51fe2c5d2b9e0f4ff108e476907a85a2">llvm::legacy::FunctionPassManagerImpl::dumpPassStructure</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a35df5259dc1bc4f526a32a2d18cb3f59">llvm::legacy::FunctionPassManagerImpl::releaseMemoryOnTheFly</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a6db182b17b61e8b4053a79e7f15b03b5">llvm::legacy::FunctionPassManagerImpl::run</a> and <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl/#a87ae04b5379a8cdfe46595e2b00a182d">llvm::legacy::PassManagerImpl::run</a>.</p>

</div>
</div>

### initializeAllAnalysisInfo() {#ad54000cb15d4de5f1cccee55f29e6ab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMTopLevelManager::initializeAllAnalysisInfo ()</td>
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



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 844 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>Reference <a href="#a62f1c43ba247efb9b876c45fe2356eea">PassManagers</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a6db182b17b61e8b4053a79e7f15b03b5">llvm::legacy::FunctionPassManagerImpl::run</a> and <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl/#a87ae04b5379a8cdfe46595e2b00a182d">llvm::legacy::PassManagerImpl::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getAsPMDataManager() {#af4d26e8879a2062e2d8129db00812fd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual PMDataManager * llvm::PMTopLevelManager::getAsPMDataManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

</div>
</div>

### getTopLevelPassManagerType() {#a565a4c914e22ce9dad3114f9025d61fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual PassManagerType llvm::PMTopLevelManager::getTopLevelPassManagerType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### activeStack {#ac2156f58ba16adbf970667ecd0d44ca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PMStack llvm::PMTopLevelManager::activeStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>Referenced by <a href="#adc80432cc11960e6cf7fcae1a64c07a5">PMTopLevelManager</a> and <a href="#a5fb719fc8062d116b93091d9c9addd43">schedulePass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### PassManagers {#a62f1c43ba247efb9b876c45fe2356eea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;PMDataManager *, 8&gt; llvm::PMTopLevelManager::PassManagers</td>
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

<p>Collection of pass managers.</p>

<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>Referenced by <a href="#acb7ec36e2caf7a586e2be1e015929804">addPassManager</a>, <a href="#a9bcf6682702cbde1eeeb006b7e49cf62">dumpArguments</a>, <a href="#aa58716ef5ab4c044f1f90f257bf91e6a">dumpPasses</a>, <a href="#a941f554aafc09331b7f599a04d85dbe7">findAnalysisPass</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a257ad4665a2a3c1c521dbbdc5f9c5882">llvm::legacy::FunctionPassManagerImpl::getContainedManager</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl/#aa361fb3ab0c9da9975f3df18f57e2d5a">llvm::legacy::PassManagerImpl::getContainedManager</a>, <a href="#ad3b4cd4b801ce3601afffa97acc8991d">getNumContainedManagers</a>, <a href="#ad54000cb15d4de5f1cccee55f29e6ab1">initializeAllAnalysisInfo</a> and <a href="#a5f398de037a18cdec4f7b21b7fb68f8c">~PMTopLevelManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AnalysisPassInfos {#a0750f50b09663e4c404254ee3422dfdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;AnalysisID, const PassInfo *&gt; llvm::PMTopLevelManager::AnalysisPassInfos</td>
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

<p>Collection of <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> objects found via analysis IDs and in this top level manager.</p>


<p>This is used to memoize queries to the pass registry. FIXME: This is an egregious hack because querying the pass registry is either slow or racy.</p>


<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

</div>
</div>

### AnUsageMap {#afe3014707efa0bdacc1cfcecd5d5c4d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Pass *, AnalysisUsage*&gt; llvm::PMTopLevelManager::AnUsageMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

</div>
</div>

### AUFoldingSetNodeAllocator {#ad6b1d4e6e8f429210dc82f4b7edb346c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;AUFoldingSetNode&gt; llvm::PMTopLevelManager::AUFoldingSetNodeAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

</div>
</div>

### ImmutablePasses {#af71ca886817b120185d228c72572fba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;ImmutablePass *, 16&gt; llvm::PMTopLevelManager::ImmutablePasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Immutable passes are managed by top level manager.</p>

<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

</div>
</div>

### ImmutablePassMap {#aaeee5f88104f458cbaf8a96491c0124e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;AnalysisID, ImmutablePass *, 8&gt; llvm::PMTopLevelManager::ImmutablePassMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to immutable passes.</p>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

</div>
</div>

### IndirectPassManagers {#a3e3f4d099129bf2be05f3932d5bf4805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;PMDataManager *, 8&gt; llvm::PMTopLevelManager::IndirectPassManagers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collection of pass managers that are not directly maintained by this pass manager.</p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

</div>
</div>

### InversedLastUser {#ad75178184a1aabec905e157f8dae3044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Pass *, SmallPtrSet&lt;Pass *, 8&gt; &gt; llvm::PMTopLevelManager::InversedLastUser</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

</div>
</div>

### LastUser {#a2991f1a586d6214c421a870d1a812d8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Pass *, Pass *&gt; llvm::PMTopLevelManager::LastUser</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

</div>
</div>

### UniqueAnalysisUsages {#ac0b942a35f89d358766a1b12dfbe9902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;AUFoldingSetNode&gt; llvm::PMTopLevelManager::UniqueAnalysisUsages</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
