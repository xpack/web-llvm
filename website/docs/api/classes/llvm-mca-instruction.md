---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/instruction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Instruction` Class

<p>An instruction propagated through the simulated instruction pipeline. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::mca::Instruction { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">llvm/MCA/Instruction.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase">InstructionBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for instructions consumed by the simulation pipeline. <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">InstrStage { <a href="#abbede16014c2eaa67d88569f823acd66">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a103822ba234afb132cfe9c91c1bc5173">Instruction</a> (const InstrDesc &amp;D, const unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7bf7b474892c43d9619f312bc7b1970">reset</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33a1f29b2ce7d35e495b48f5c5395701">getRCUTokenID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af68b0a1cbe3a03b2011acbf400ffec68">getLSUTokenID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb66d9fd67e0ee7d09dec5b097683144">setLSUTokenID</a> (unsigned LSUTok)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade5871926e9ec2af4e3f5151764ac934">getUsedBuffers</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd5daeee98c01e717560ca5c1515f89d">setUsedBuffers</a> (uint64_t Mask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9db8afb5bcefbf68add88c3f1afbadd">clearUsedBuffers</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a25c63d48e10b991c7e29f784503c72">getCyclesLeft</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad874289921c7bad356c315a1e45c3871">dispatch</a> (unsigned RCUTokenID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa48a9861f68bdba50e623e013b3d6c44">execute</a> (unsigned IID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9019dc8f7abc6c2466b1af1ee04b037">update</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34ce4db425156eb3d433ebadb501b1cc">updateDispatched</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab6642685168f41b152d9ba68c5bdcea">updatePending</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa69ad5cb6a05bd56277ae2b6dad9f1da">isInvalid</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07eee271c4520e38fdbf53c45e0b343f">isDispatched</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed04cdcdcafe3907e7cc831734e0c945">isPending</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bb47a248d88005ef524178ebfc9b47a">isReady</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c3e3c8d82c761fc3883620963ddd0a4">isExecuting</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12eb7cffeb144db46e8dfe35063a8d90">isExecuted</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b9b12df99aa31bcf97464d3b7a33266">isRetired</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fcf55600b7c6a8445759b4f84eb1fb3">isEliminated</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fba95a927f8e0478c912dd65a6caffb">forceExecuted</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8e4feddfcf01317e6cab09ea59c606c">setEliminated</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7417649c998bfedb839b3cbc4a59893">retire</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/criticaldependency">CriticalDependency</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a468c2e8d3dcf649cd77dbe600f0e98e5">getCriticalRegDep</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/criticaldependency">CriticalDependency</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a372235704862e29a92af4111aeb18783">getCriticalMemDep</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/criticaldependency">CriticalDependency</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cab34861a215282de90750a093e24e1">computeCriticalRegDep</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf73f8513fbaca0f859611c04bfebe5a">setCriticalMemDep</a> (const CriticalDependency &amp;MemDep)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d4b83da055e18ae82e51de0692ef9d6">getCriticalResourceMask</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a814fb55571cfb4880954cd744816c34a">setCriticalResourceMask</a> (uint64_t ResourceMask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0364e9431a5be0d2baa9462cbe169c21">cycleEvent</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum InstrStage</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c22d42503bc6e7ae6fa58c0e1f441d9">Stage</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c669fb85bf623421558bdec38e2f1a3">CyclesLeft</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63a6e5e381c637f6cb09500614782676">RCUTokenID</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a045bd8b1ffa18a338fa874fa8258357f">LSUTokenID</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b324d4b4a76b26a797757b59edf4682">UsedBuffers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mca/criticaldependency">CriticalDependency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a6a9b795b2857ff4b5847963bafa303">CriticalRegDep</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mca/criticaldependency">CriticalDependency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa80e5ecfdcfc3ed6f4e3bc189626608a">CriticalMemDep</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b95a0dee63d5dc7cf301b8198fba091">CriticalResourceMask</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43d12d68a1253d8ab8c7403d379b3d58">IsEliminated</a></td>
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

<p>An instruction propagated through the simulated instruction pipeline.</p>


<p>This class is used to monitor changes to the internal state of instructions that are sent to the various components of the simulated hardware pipeline.</p>


<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### InstrStage {#abbede16014c2eaa67d88569f823acd66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::mca::Instruction::InstrStage </td>
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
<td class="doxyEnumItemName">IS_INVALID<a id="abbede16014c2eaa67d88569f823acd66aadd449339864bbd81d0252deb751c24b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IS_DISPATCHED<a id="abbede16014c2eaa67d88569f823acd66a6cc0c0a70ecbfe887aef245857c4734e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IS_PENDING<a id="abbede16014c2eaa67d88569f823acd66a39b270bdcf4470cbd4b8917a5621ba38"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IS_READY<a id="abbede16014c2eaa67d88569f823acd66a288c6d493404b54b343294e0fbe32f6e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IS_EXECUTING<a id="abbede16014c2eaa67d88569f823acd66a6683295b569ab10417ea8bfadd779d04"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IS_EXECUTED<a id="abbede16014c2eaa67d88569f823acd66a986e32bca8cb97a3b20cfd3e9f229e03"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IS_RETIRED<a id="abbede16014c2eaa67d88569f823acd66aa6778d537e073a0f47cb3a0ee81fd7e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Instruction() {#a103822ba234afb132cfe9c91c1bc5173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::Instruction::Instruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/instrdesc">InstrDesc</a> &amp; D, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned Opcode)</td>
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



<p>Definition at line 647 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#adf2552c33aa372b913e27996a97f73b5">llvm::mca::InstructionBase::InstructionBase</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#af459dc58960b1471b00b72f450869f01">llvm::mca::UNKNOWN_CYCLES</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearUsedBuffers() {#ad9db8afb5bcefbf68add88c3f1afbadd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Instruction::clearUsedBuffers ()</td>
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



<p>Definition at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### computeCriticalRegDep() {#a8cab34861a215282de90750a093e24e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CriticalDependency &amp; llvm::mca::Instruction::computeCriticalRegDep ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 704 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mca/criticaldependency/#a9f6b748ac1f1635527f1d84130611353">llvm::mca::CriticalDependency::Cycles</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a4bd1b7f022ec64b74af6360bca400f13">llvm::mca::InstructionBase::getDefs</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a72ba6c0a31c2fe1ce24a1b7450928133">llvm::mca::InstructionBase::getUses</a>.</p>

</div>
</div>

### cycleEvent() {#a0364e9431a5be0d2baa9462cbe169c21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Instruction::cycleEvent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>, definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a4bd1b7f022ec64b74af6360bca400f13">llvm::mca::InstructionBase::getDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a72ba6c0a31c2fe1ce24a1b7450928133">llvm::mca::InstructionBase::getUses</a>, <a href="#a07eee271c4520e38fdbf53c45e0b343f">isDispatched</a>, <a href="#a5c3e3c8d82c761fc3883620963ddd0a4">isExecuting</a>, <a href="#aed04cdcdcafe3907e7cc831734e0c945">isPending</a>, <a href="#a8bb47a248d88005ef524178ebfc9b47a">isReady</a> and <a href="#ad9019dc8f7abc6c2466b1af1ee04b037">update</a>.</p>

</div>
</div>

### dispatch() {#ad874289921c7bad356c315a1e45c3871}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Instruction::dispatch (unsigned RCUTokenID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 668 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a34ce4db425156eb3d433ebadb501b1cc">updateDispatched</a> and <a href="#aab6642685168f41b152d9ba68c5bdcea">updatePending</a>.</p>

</div>
</div>

### execute() {#aa48a9861f68bdba50e623e013b3d6c44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Instruction::execute (unsigned IID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 672 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a4bd1b7f022ec64b74af6360bca400f13">llvm::mca::InstructionBase::getDefs</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a52274dff5e2c597b8c10d85cf5212f75">llvm::mca::InstructionBase::getLatency</a>.</p>

</div>
</div>

### forceExecuted() {#a5fba95a927f8e0478c912dd65a6caffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Instruction::forceExecuted ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 694 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>, definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getCriticalMemDep() {#a372235704862e29a92af4111aeb18783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CriticalDependency &amp; llvm::mca::Instruction::getCriticalMemDep ()</td>
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



<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### getCriticalRegDep() {#a468c2e8d3dcf649cd77dbe600f0e98e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CriticalDependency &amp; llvm::mca::Instruction::getCriticalRegDep ()</td>
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



<p>Definition at line 702 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### getCriticalResourceMask() {#a2d4b83da055e18ae82e51de0692ef9d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::Instruction::getCriticalResourceMask ()</td>
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



<p>Definition at line 709 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### getCyclesLeft() {#a7a25c63d48e10b991c7e29f784503c72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::mca::Instruction::getCyclesLeft ()</td>
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



<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup/#ac97627baabc9947fa54f74274809b9d5">llvm::mca::LSUnit::MemoryGroup::onInstructionIssued</a>.</p>

</div>
</div>

### getLSUTokenID() {#af68b0a1cbe3a03b2011acbf400ffec68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::Instruction::getLSUTokenID ()</td>
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



<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/#a8201f572ba1e14162d280b841cb461de">llvm::mca::LSUnit::onInstructionExecuted</a>.</p>

</div>
</div>

### getRCUTokenID() {#a33a1f29b2ce7d35e495b48f5c5395701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::Instruction::getRCUTokenID ()</td>
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



<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/retirestage/#a76d48aaace0410f399f254af62562d48">llvm::mca::RetireStage::execute</a>.</p>

</div>
</div>

### getUsedBuffers() {#ade5871926e9ec2af4e3f5151764ac934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::Instruction::getUsedBuffers ()</td>
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



<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler/#ab72375182cfa0b8e37b997b861e35208">llvm::mca::Scheduler::dispatch</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler/#a216ffefe6fe4a2b566a72228c0bd763d">llvm::mca::Scheduler::issueInstruction</a>.</p>

</div>
</div>

### isDispatched() {#a07eee271c4520e38fdbf53c45e0b343f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Instruction::isDispatched ()</td>
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



<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>


<p>Referenced by <a href="#a0364e9431a5be0d2baa9462cbe169c21">cycleEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler/#ab72375182cfa0b8e37b997b861e35208">llvm::mca::Scheduler::dispatch</a>, <a href="#ad9019dc8f7abc6c2466b1af1ee04b037">update</a> and <a href="#a34ce4db425156eb3d433ebadb501b1cc">updateDispatched</a>.</p>

</div>
</div>

### isEliminated() {#a0fcf55600b7c6a8445759b4f84eb1fb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Instruction::isEliminated ()</td>
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



<p>Definition at line 691 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a4df19f409f93dfad60c8af721603d452">llvm::mca::addRegisterReadWrite</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ab24e9ac7e416812424904af7a1da17c3">llvm::mca::verifyInstructionEliminated</a>.</p>

</div>
</div>

### isExecuted() {#a12eb7cffeb144db46e8dfe35063a8d90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Instruction::isExecuted ()</td>
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



<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#aff33426f5edf9f386718b122bae39f7b">llvm::mca::RegisterFile::onInstructionExecuted</a> and <a href="#ae7417649c998bfedb839b3cbc4a59893">retire</a>.</p>

</div>
</div>

### isExecuting() {#a5c3e3c8d82c761fc3883620963ddd0a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Instruction::isExecuting ()</td>
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



<p>Definition at line 688 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>


<p>Referenced by <a href="#a0364e9431a5be0d2baa9462cbe169c21">cycleEvent</a>.</p>

</div>
</div>

### isInvalid() {#aa69ad5cb6a05bd56277ae2b6dad9f1da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Instruction::isInvalid ()</td>
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



<p>Definition at line 684 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### isPending() {#aed04cdcdcafe3907e7cc831734e0c945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Instruction::isPending ()</td>
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



<p>Definition at line 686 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler/#a9651d447561aa0aea1b3171eee94152c">llvm::mca::Scheduler::analyzeDataDependencies</a>, <a href="#a0364e9431a5be0d2baa9462cbe169c21">cycleEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler/#ab72375182cfa0b8e37b997b861e35208">llvm::mca::Scheduler::dispatch</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/executestage/#ab745e03cf7c86d0b422cca9650a10175">llvm::mca::ExecuteStage::execute</a>, <a href="#ad9019dc8f7abc6c2466b1af1ee04b037">update</a> and <a href="#aab6642685168f41b152d9ba68c5bdcea">updatePending</a>.</p>

</div>
</div>

### isReady() {#a8bb47a248d88005ef524178ebfc9b47a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Instruction::isReady ()</td>
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



<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>


<p>Referenced by <a href="#a0364e9431a5be0d2baa9462cbe169c21">cycleEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler/#ab72375182cfa0b8e37b997b861e35208">llvm::mca::Scheduler::dispatch</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ab24e9ac7e416812424904af7a1da17c3">llvm::mca::verifyInstructionEliminated</a>.</p>

</div>
</div>

### isRetired() {#a7b9b12df99aa31bcf97464d3b7a33266}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Instruction::isRetired ()</td>
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



<p>Definition at line 690 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### reset() {#ae7bf7b474892c43d9619f312bc7b1970}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Instruction::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 653 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a53097b7d979de32c754dbd307626ebd9">llvm::mca::InstructionBase::clearOptimizableMove</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#af459dc58960b1471b00b72f450869f01">llvm::mca::UNKNOWN_CYCLES</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/instrbuilder/#afe394be08220c92f22489a0f952d39ee">llvm::mca::InstrBuilder::createInstruction</a>.</p>

</div>
</div>

### retire() {#ae7417649c998bfedb839b3cbc4a59893}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Instruction::retire ()</td>
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



<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a12eb7cffeb144db46e8dfe35063a8d90">isExecuted</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mca/retirecontrolunit/#af830bc0573e2b15a668a9ae57edcab3d">llvm::mca::RetireControlUnit::consumeCurrentToken</a>.</p>

</div>
</div>

### setCriticalMemDep() {#acf73f8513fbaca0f859611c04bfebe5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Instruction::setCriticalMemDep (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/criticaldependency">CriticalDependency</a> &amp; MemDep)</td>
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



<p>Definition at line 705 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### setCriticalResourceMask() {#a814fb55571cfb4880954cd744816c34a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Instruction::setCriticalResourceMask (uint64_t ResourceMask)</td>
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



<p>Definition at line 710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler/#a0113fd8e2f25ac69b90b9ac8ded672f6">llvm::mca::Scheduler::select</a>.</p>

</div>
</div>

### setEliminated() {#ac8e4feddfcf01317e6cab09ea59c606c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Instruction::setEliminated ()</td>
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



<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### setLSUTokenID() {#abb66d9fd67e0ee7d09dec5b097683144}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Instruction::setLSUTokenID (unsigned LSUTok)</td>
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



<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler/#ab72375182cfa0b8e37b997b861e35208">llvm::mca::Scheduler::dispatch</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/inorderissuestage/#a8de83f23b94fb81affc3528986eb9971">llvm::mca::InOrderIssueStage::execute</a>.</p>

</div>
</div>

### setUsedBuffers() {#acd5daeee98c01e717560ca5c1515f89d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Instruction::setUsedBuffers (uint64_t Mask)</td>
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



<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### update() {#ad9019dc8f7abc6c2466b1af1ee04b037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Instruction::update ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 680 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="#a07eee271c4520e38fdbf53c45e0b343f">isDispatched</a>, <a href="#aed04cdcdcafe3907e7cc831734e0c945">isPending</a>, <a href="#a34ce4db425156eb3d433ebadb501b1cc">updateDispatched</a> and <a href="#aab6642685168f41b152d9ba68c5bdcea">updatePending</a>.</p>


<p>Referenced by <a href="#a0364e9431a5be0d2baa9462cbe169c21">cycleEvent</a>.</p>

</div>
</div>

### updateDispatched() {#a34ce4db425156eb3d433ebadb501b1cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Instruction::updateDispatched ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a4bd1b7f022ec64b74af6360bca400f13">llvm::mca::InstructionBase::getDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a72ba6c0a31c2fe1ce24a1b7450928133">llvm::mca::InstructionBase::getUses</a> and <a href="#a07eee271c4520e38fdbf53c45e0b343f">isDispatched</a>.</p>


<p>Referenced by <a href="#ad874289921c7bad356c315a1e45c3871">dispatch</a> and <a href="#ad9019dc8f7abc6c2466b1af1ee04b037">update</a>.</p>

</div>
</div>

### updatePending() {#aab6642685168f41b152d9ba68c5bdcea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Instruction::updatePending ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 682 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a4bd1b7f022ec64b74af6360bca400f13">llvm::mca::InstructionBase::getDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a72ba6c0a31c2fe1ce24a1b7450928133">llvm::mca::InstructionBase::getUses</a> and <a href="#aed04cdcdcafe3907e7cc831734e0c945">isPending</a>.</p>


<p>Referenced by <a href="#ad874289921c7bad356c315a1e45c3871">dispatch</a> and <a href="#ad9019dc8f7abc6c2466b1af1ee04b037">update</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CriticalMemDep {#aa80e5ecfdcfc3ed6f4e3bc189626608a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CriticalDependency llvm::mca::Instruction::CriticalMemDep</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### CriticalRegDep {#a6a6a9b795b2857ff4b5847963bafa303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CriticalDependency llvm::mca::Instruction::CriticalRegDep</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 633 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### CriticalResourceMask {#a0b95a0dee63d5dc7cf301b8198fba091}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::Instruction::CriticalResourceMask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### CyclesLeft {#a5c669fb85bf623421558bdec38e2f1a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::mca::Instruction::CyclesLeft</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### IsEliminated {#a43d12d68a1253d8ab8c7403d379b3d58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Instruction::IsEliminated</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### LSUTokenID {#a045bd8b1ffa18a338fa874fa8258357f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::Instruction::LSUTokenID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### RCUTokenID {#a63a6e5e381c637f6cb09500614782676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::Instruction::RCUTokenID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### Stage {#a0c22d42503bc6e7ae6fa58c0e1f441d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum InstrStage llvm::mca::Instruction::Stage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### UsedBuffers {#a0b324d4b4a76b26a797757b59edf4682}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::Instruction::UsedBuffers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/instruction-h">Instruction.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mca/instruction-cpp">Instruction.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
