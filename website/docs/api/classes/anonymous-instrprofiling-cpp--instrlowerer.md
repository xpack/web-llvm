---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-instrprofiling-cpp-/instrlowerer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InstrLowerer` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{InstrProfiling.cpp}::InstrLowerer { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70e0b3b4e6c78926a887c81eba07c880">InstrLowerer</a> (Module &amp;M, const InstrProfOptions &amp;Options, std::function&lt; const TargetLibraryInfo &amp;(Function &amp;F)&gt; GetTLI, bool IsCS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4a213aa8265b5907de86f84b12b5f8a">lower</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad36e431da6952beb5182addab9d942fb">lowerIntrinsics</a> (Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower instrumentation intrinsics in the function. <a href="#ad36e431da6952beb5182addab9d942fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7997fea84c6748392bac8490f105ac9">promoteCounterLoadStores</a> (Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Register-promote counter loads and stores in loops. <a href="#ac7997fea84c6748392bac8490f105ac9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a799a2bd7dcce8f32dd29609275886242">isRuntimeCounterRelocationEnabled</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if relocating counters at runtime is enabled. <a href="#a799a2bd7dcce8f32dd29609275886242">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d6e62711b9f2e1e64c3520936c502fa">isCounterPromotionEnabled</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if profile counter update register promotion is enabled. <a href="#a1d6e62711b9f2e1e64c3520936c502fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a628f4147a7ae3d91d0607fbbaea86613">isSamplingEnabled</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if profile sampling is enabled. <a href="#a628f4147a7ae3d91d0607fbbaea86613">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b1f6e3e5c06b379e06529378809aa1c">computeNumValueSiteCounts</a> (InstrProfValueProfileInst *Ins)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Count the number of instrumented value sites for the function. <a href="#a8b1f6e3e5c06b379e06529378809aa1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35f2d648de372b9b8703d0420331fc8b">lowerValueProfileInst</a> (InstrProfValueProfileInst *Ins)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace instrprof.value.profile with a call to runtime library. <a href="#a35f2d648de372b9b8703d0420331fc8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade829cc0325cba12c686e569fd02957a">lowerCover</a> (InstrProfCoverInst *Inc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace instrprof.cover with a store instruction to the coverage byte. <a href="#ade829cc0325cba12c686e569fd02957a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3df5be2454d8d6f443684c445982655">lowerTimestamp</a> (InstrProfTimestampInst *TimestampInstruction)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace instrprof.timestamp with a call to INSTR_PROF_PROFILE_SET_TIMESTAMP. <a href="#ac3df5be2454d8d6f443684c445982655">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab227ea62e403bb599c46093491967d1a">lowerIncrement</a> (InstrProfIncrementInst *Inc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace instrprof.increment with an increment of the appropriate value. <a href="#ab227ea62e403bb599c46093491967d1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5ff17b8f750ec03d2cbbfb4621fe5e0">lowerCoverageData</a> (GlobalVariable *CoverageNamesVar)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Force emitting of name vars for unused functions. <a href="#ad5ff17b8f750ec03d2cbbfb4621fe5e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92df785755cb6748284df43831cf29cb">lowerMCDCTestVectorBitmapUpdate</a> (InstrProfMCDCTVBitmapUpdate *Ins)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace instrprof.mcdc.tvbitmask.update with a shift and or instruction using the index represented by the a temp value into a bitmap. <a href="#a92df785755cb6748284df43831cf29cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0162e7bab05c2afa8d887c19e33c972">getOrCreateBiasVar</a> (StringRef VarName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the Bias value for data to access mmap-ed area. <a href="#ab0162e7bab05c2afa8d887c19e33c972">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ef8cdfe6f111b4138ca454b8c819e8d">getCounterAddress</a> (InstrProfCntrInstBase *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the address of the counter value that this profiling instruction acts on. <a href="#a9ef8cdfe6f111b4138ca454b8c819e8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6087425b5ecd2da73568992f9a73a4a2">doSampling</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower the incremental instructions under profile sampling predicates. <a href="#a6087425b5ecd2da73568992f9a73a4a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b205c8016e28bc2a60fd22edabe4a3a">getOrCreateRegionCounters</a> (InstrProfCntrInstBase *Inc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the region counters for an increment, creating them if necessary. <a href="#a3b205c8016e28bc2a60fd22edabe4a3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84d1e440d1eb0c2725dec7e2d55e2e73">createRegionCounters</a> (InstrProfCntrInstBase *Inc, StringRef Name, GlobalValue::LinkageTypes Linkage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the region counters. <a href="#a84d1e440d1eb0c2725dec7e2d55e2e73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d4a926d78fb9718c39816200cfa8741">getBitmapAddress</a> (InstrProfMCDCTVBitmapUpdate *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the address of the test vector bitmap that this profiling instruction acts on. <a href="#a2d4a926d78fb9718c39816200cfa8741">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab929bb9b27d8e476c7cd2d6b76b273b8">getOrCreateRegionBitmaps</a> (InstrProfMCDCBitmapInstBase *Inc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the region bitmaps for an increment, creating them if necessary. <a href="#ab929bb9b27d8e476c7cd2d6b76b273b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a256b83fe44bf082d4481816fad515e86">createRegionBitmaps</a> (InstrProfMCDCBitmapInstBase *Inc, StringRef Name, GlobalValue::LinkageTypes Linkage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the MC/DC bitmap as a byte-aligned array of bytes associated with an MC/DC Decision region. <a href="#a256b83fe44bf082d4481816fad515e86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc1474cda0610e5ca8fef4c3b7c24a9e">maybeSetComdat</a> (GlobalVariable *GV, GlobalObject *GO, StringRef VarName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> property of GV, if required. <a href="#afc1474cda0610e5ca8fef4c3b7c24a9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a241e6641dd1adb6746078e20dcfc83">setupProfileSection</a> (InstrProfInstBase *Inc, InstrProfSectKind IPSK)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Setup the sections into which counters and bitmaps are allocated. <a href="#a6a241e6641dd1adb6746078e20dcfc83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6213a1a883846922267e814663b04da4">createDataVariable</a> (InstrProfCntrInstBase *Inc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create INSTR_PROF_DATA variable for counters and bitmaps. <a href="#a6213a1a883846922267e814663b04da4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21e8c13d629927954c6ce6c975bb0ad1">getOrCreateVTableProfData</a> (GlobalVariable *GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the counters for virtual table values, creating them if necessary. <a href="#a21e8c13d629927954c6ce6c975bb0ad1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a725234c766e309484f26c7208ed45a57">emitNameData</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the section with compressed function names. <a href="#a725234c766e309484f26c7208ed45a57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a266be74edacd65e2150cec2bb26aaf75">emitVTableNames</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the section with compressed vtable names. <a href="#a266be74edacd65e2150cec2bb26aaf75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cbda4e3b2ffc9243d44c2c90e432b09">emitVNodes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit value nodes section for value profiling. <a href="#a5cbda4e3b2ffc9243d44c2c90e432b09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3fe5f658d205c4e4bf4af1e9e26f6e6">emitRegistration</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit runtime registration functions for each profile data variable. <a href="#ab3fe5f658d205c4e4bf4af1e9e26f6e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7888047948b99762bf3ee34df1818d9d">emitRuntimeHook</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the necessary plumbing to pull in the runtime initialization. <a href="#a7888047948b99762bf3ee34df1818d9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac8a9ef6baf5a9153e54f21187f521c6">emitUses</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add uses of our data variables and runtime hook. <a href="#aac8a9ef6baf5a9153e54f21187f521c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a893c8990853f412a9f564b33c994870f">emitInitialization</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a static initializer for our data, on platforms that need it, and for any profile output file that was specified. <a href="#a893c8990853f412a9f564b33c994870f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79419a6e4d7a7bfc0a52f9e681ae0ab3">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrprofoptions">InstrProfOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a450e8374a45fb21b7a5f19234e8a4ea0">Options</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9042891bf603f81663332b84f8cb1d4d">TT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab29a776e042417e618a097b9e89ec6a9">IsCS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ca8361cebb433edf16e2b58d1b96bc2">GetTLI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9beefc053d5f6ddeb66d022631f15942">DataReferencedByCode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *, PerFunctionProfileData &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a684d235b67d9c8908da5a1b62603ff53">ProfileDataMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dfc0cffe4a3ead105f5c8acf79e12aa">VTableDataMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a841816563de23a1044e335252af5f623">FunctionToProfileBiasMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If runtime relocation is enabled, this maps functions to the load instruction that produces the profile relocation bias. <a href="#a841816563de23a1044e335252af5f623">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca93088d52f2d8d0493017cfa4fcccf7">CompilerUsedVars</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c3c5c2a9de66c3226b75e0c809057a8">UsedVars</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad98d1383124eacb9b6b67ed7950307ab">ReferencedNames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefc6ae67fc99faa662ed967498489b54">ReferencedVTables</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e503d9ad989fca0ac388a4bb5e2a7a0">NamesVar</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab59bb1f7c935e84dbd1ff3e65c143122">NamesSize</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-instrprofiling-cpp-/#a361b8ddbd271c831f936f4cca3bc7ec6">LoadStorePair</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b747bc9aec4db7c4232b1ef510c05b8">PromotionCandidates</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac331e04c1d78d86a4429bd4bf09c64f6">TotalCountersPromoted</a> = 0</td>
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


<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InstrLowerer() {#a70e0b3b4e6c78926a887c81eba07c880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InstrProfiling.cpp}::InstrLowerer::InstrLowerer (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrprofoptions">InstrProfOptions</a> &amp; Options, std::function&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>)&gt; GetTLI, bool IsCS)</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-instrprofiling-cpp-/#afb8afb94e818749e2f835faa7e974b5d">anonymous{InstrProfiling.cpp}::profDataReferencedByCode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### lower() {#aa4a213aa8265b5907de86f84b12b5f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrLowerer::lower ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#a3ca28a37cc6f2fdfc1a57471623dd411">containsProfilingIntrinsics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a277490f857b3fe53b950347a9148a447">llvm::createProfileSamplingVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af32878ec52dce0e4c46389f07efbc101">llvm::EnableVTableValueProfiling</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50d466b105ab8b79cf83a6b49cf54886">llvm::getCoverageUnusedNamesVarName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#a1685aa39a6ab802e9dd6f23244359092">needsRuntimeHookUnconditionally</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeNumValueSiteCounts() {#a8b1f6e3e5c06b379e06529378809aa1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrLowerer::computeNumValueSiteCounts (<a href="/web-llvm/docs/api/classes/llvm/instrprofvalueprofileinst">InstrProfValueProfileInst</a> * Ins)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Count the number of instrumented value sites for the function.</p>

<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### createDataVariable() {#a6213a1a883846922267e814663b04da4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrLowerer::createDataVariable (<a href="/web-llvm/docs/api/classes/llvm/instrprofcntrinstbase">InstrProfCntrInstBase</a> * Inc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create INSTR_PROF_DATA variable for counters and bitmaps.</p>

<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### createRegionBitmaps() {#a256b83fe44bf082d4481816fad515e86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * InstrLowerer::createRegionBitmaps (<a href="/web-llvm/docs/api/classes/llvm/instrprofmcdcbitmapinstbase">InstrProfMCDCBitmapInstBase</a> * Inc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> Linkage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the MC/DC bitmap as a byte-aligned array of bytes associated with an MC/DC Decision region.</p>


<p>The number of bytes required is indicated by the intrinsic used (type <a href="/web-llvm/docs/api/classes/llvm/instrprofmcdcbitmapinstbase">InstrProfMCDCBitmapInstBase</a>). This is called as part of setupProfileSection() and is conceptually very similar to what is done for profile data counters in createRegionCounters().</p>


<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### createRegionCounters() {#a84d1e440d1eb0c2725dec7e2d55e2e73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * InstrLowerer::createRegionCounters (<a href="/web-llvm/docs/api/classes/llvm/instrprofcntrinstbase">InstrProfCntrInstBase</a> * Inc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> Linkage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the region counters.</p>

<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### doSampling() {#a6087425b5ecd2da73568992f9a73a4a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrLowerer::doSampling (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower the incremental instructions under profile sampling predicates.</p>

<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### emitInitialization() {#a893c8990853f412a9f564b33c994870f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrLowerer::emitInitialization ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a static initializer for our data, on platforms that need it, and for any profile output file that was specified.</p>

<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### emitNameData() {#a725234c766e309484f26c7208ed45a57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrLowerer::emitNameData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the section with compressed function names.</p>

<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### emitRegistration() {#ab3fe5f658d205c4e4bf4af1e9e26f6e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrLowerer::emitRegistration ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit runtime registration functions for each profile data variable.</p>

<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### emitRuntimeHook() {#a7888047948b99762bf3ee34df1818d9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrLowerer::emitRuntimeHook ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the necessary plumbing to pull in the runtime initialization.</p>


<p>Returns true if a change was made.</p>


<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### emitUses() {#aac8a9ef6baf5a9153e54f21187f521c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrLowerer::emitUses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add uses of our data variables and runtime hook.</p>

<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### emitVNodes() {#a5cbda4e3b2ffc9243d44c2c90e432b09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrLowerer::emitVNodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit value nodes section for value profiling.</p>

<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### emitVTableNames() {#a266be74edacd65e2150cec2bb26aaf75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrLowerer::emitVTableNames ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the section with compressed vtable names.</p>

<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### getBitmapAddress() {#a2d4a926d78fb9718c39816200cfa8741}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * InstrLowerer::getBitmapAddress (<a href="/web-llvm/docs/api/classes/llvm/instrprofmcdctvbitmapupdate">InstrProfMCDCTVBitmapUpdate</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the address of the test vector bitmap that this profiling instruction acts on.</p>

<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### getCounterAddress() {#a9ef8cdfe6f111b4138ca454b8c819e8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * InstrLowerer::getCounterAddress (<a href="/web-llvm/docs/api/classes/llvm/instrprofcntrinstbase">InstrProfCntrInstBase</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the address of the counter value that this profiling instruction acts on.</p>

<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### getOrCreateBiasVar() {#ab0162e7bab05c2afa8d887c19e33c972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * InstrLowerer::getOrCreateBiasVar (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> VarName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the Bias value for data to access mmap-ed area.</p>


<p>Create it if it hasn't been seen.</p>


<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### getOrCreateRegionBitmaps() {#ab929bb9b27d8e476c7cd2d6b76b273b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * InstrLowerer::getOrCreateRegionBitmaps (<a href="/web-llvm/docs/api/classes/llvm/instrprofmcdcbitmapinstbase">InstrProfMCDCBitmapInstBase</a> * Inc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the region bitmaps for an increment, creating them if necessary.</p>


<p>If the bitmap array doesn't yet exist, the profile data variables referring to them will also be created.</p>


<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### getOrCreateRegionCounters() {#a3b205c8016e28bc2a60fd22edabe4a3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * InstrLowerer::getOrCreateRegionCounters (<a href="/web-llvm/docs/api/classes/llvm/instrprofcntrinstbase">InstrProfCntrInstBase</a> * Inc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the region counters for an increment, creating them if necessary.</p>


<p>If the counter array doesn't yet exist, the profile data variables referring to them will also be created.</p>


<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### getOrCreateVTableProfData() {#a21e8c13d629927954c6ce6c975bb0ad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrLowerer::getOrCreateVTableProfData (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the counters for virtual table values, creating them if necessary.</p>

<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### isCounterPromotionEnabled() {#a1d6e62711b9f2e1e64c3520936c502fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrLowerer::isCounterPromotionEnabled ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if profile counter update register promotion is enabled.</p>

<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### isRuntimeCounterRelocationEnabled() {#a799a2bd7dcce8f32dd29609275886242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrLowerer::isRuntimeCounterRelocationEnabled ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if relocating counters at runtime is enabled.</p>

<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### isSamplingEnabled() {#a628f4147a7ae3d91d0607fbbaea86613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrLowerer::isSamplingEnabled ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if profile sampling is enabled.</p>

<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### lowerCover() {#ade829cc0325cba12c686e569fd02957a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrLowerer::lowerCover (<a href="/web-llvm/docs/api/classes/llvm/instrprofcoverinst">InstrProfCoverInst</a> * Inc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace instrprof.cover with a store instruction to the coverage byte.</p>

<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### lowerCoverageData() {#ad5ff17b8f750ec03d2cbbfb4621fe5e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrLowerer::lowerCoverageData (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * CoverageNamesVar)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Force emitting of name vars for unused functions.</p>

<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### lowerIncrement() {#ab227ea62e403bb599c46093491967d1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrLowerer::lowerIncrement (<a href="/web-llvm/docs/api/classes/llvm/instrprofincrementinst">InstrProfIncrementInst</a> * Inc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace instrprof.increment with an increment of the appropriate value.</p>

<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### lowerIntrinsics() {#ad36e431da6952beb5182addab9d942fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrLowerer::lowerIntrinsics (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower instrumentation intrinsics in the function.</p>


<p>Returns true if there any lowering.</p>


<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### lowerMCDCTestVectorBitmapUpdate() {#a92df785755cb6748284df43831cf29cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrLowerer::lowerMCDCTestVectorBitmapUpdate (<a href="/web-llvm/docs/api/classes/llvm/instrprofmcdctvbitmapupdate">InstrProfMCDCTVBitmapUpdate</a> * Ins)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace instrprof.mcdc.tvbitmask.update with a shift and or instruction using the index represented by the a temp value into a bitmap.</p>

<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### lowerTimestamp() {#ac3df5be2454d8d6f443684c445982655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrLowerer::lowerTimestamp (<a href="/web-llvm/docs/api/classes/llvm/instrproftimestampinst">InstrProfTimestampInst</a> * TimestampInstruction)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace instrprof.timestamp with a call to INSTR_PROF_PROFILE_SET_TIMESTAMP.</p>

<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### lowerValueProfileInst() {#a35f2d648de372b9b8703d0420331fc8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrLowerer::lowerValueProfileInst (<a href="/web-llvm/docs/api/classes/llvm/instrprofvalueprofileinst">InstrProfValueProfileInst</a> * Ins)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace instrprof.value.profile with a call to runtime library.</p>

<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### maybeSetComdat() {#afc1474cda0610e5ca8fef4c3b7c24a9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrLowerer::maybeSetComdat (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV, <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> VarName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> property of GV, if required.</p>

<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### promoteCounterLoadStores() {#ac7997fea84c6748392bac8490f105ac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrLowerer::promoteCounterLoadStores (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Register-promote counter loads and stores in loops.</p>

<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### setupProfileSection() {#a6a241e6641dd1adb6746078e20dcfc83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * InstrLowerer::setupProfileSection (<a href="/web-llvm/docs/api/classes/llvm/instrprofinstbase">InstrProfInstBase</a> * Inc, <a href="/web-llvm/docs/api/namespaces/llvm/#a767d93f77e49e029ce90cf8169e7632a">InstrProfSectKind</a> IPSK)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Setup the sections into which counters and bitmaps are allocated.</p>

<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CompilerUsedVars {#aca93088d52f2d8d0493017cfa4fcccf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;GlobalValue *&gt; anonymous{InstrProfiling.cpp}::InstrLowerer::CompilerUsedVars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### DataReferencedByCode {#a9beefc053d5f6ddeb66d022631f15942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool anonymous{InstrProfiling.cpp}::InstrLowerer::DataReferencedByCode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### FunctionToProfileBiasMap {#a841816563de23a1044e335252af5f623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Function *, LoadInst *&gt; anonymous{InstrProfiling.cpp}::InstrLowerer::FunctionToProfileBiasMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If runtime relocation is enabled, this maps functions to the load instruction that produces the profile relocation bias.</p>

<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### GetTLI {#a2ca8361cebb433edf16e2b58d1b96bc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;const TargetLibraryInfo &amp;(Function &amp;F)&gt; anonymous{InstrProfiling.cpp}::InstrLowerer::GetTLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### IsCS {#ab29a776e042417e618a097b9e89ec6a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool anonymous{InstrProfiling.cpp}::InstrLowerer::IsCS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### M {#a79419a6e4d7a7bfc0a52f9e681ae0ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module&amp; anonymous{InstrProfiling.cpp}::InstrLowerer::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### NamesSize {#ab59bb1f7c935e84dbd1ff3e65c143122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{InstrProfiling.cpp}::InstrLowerer::NamesSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### NamesVar {#a5e503d9ad989fca0ac388a4bb5e2a7a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable* anonymous{InstrProfiling.cpp}::InstrLowerer::NamesVar = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### Options {#a450e8374a45fb21b7a5f19234e8a4ea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrProfOptions anonymous{InstrProfiling.cpp}::InstrLowerer::Options</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### ProfileDataMap {#a684d235b67d9c8908da5a1b62603ff53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;GlobalVariable *, PerFunctionProfileData&gt; anonymous{InstrProfiling.cpp}::InstrLowerer::ProfileDataMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### PromotionCandidates {#a8b747bc9aec4db7c4232b1ef510c05b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;LoadStorePair&gt; anonymous{InstrProfiling.cpp}::InstrLowerer::PromotionCandidates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### ReferencedNames {#ad98d1383124eacb9b6b67ed7950307ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;GlobalVariable *&gt; anonymous{InstrProfiling.cpp}::InstrLowerer::ReferencedNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### ReferencedVTables {#aefc6ae67fc99faa662ed967498489b54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;GlobalVariable *&gt; anonymous{InstrProfiling.cpp}::InstrLowerer::ReferencedVTables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### TotalCountersPromoted {#ac331e04c1d78d86a4429bd4bf09c64f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{InstrProfiling.cpp}::InstrLowerer::TotalCountersPromoted = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### TT {#a9042891bf603f81663332b84f8cb1d4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Triple anonymous{InstrProfiling.cpp}::InstrLowerer::TT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### UsedVars {#a0c3c5c2a9de66c3226b75e0c809057a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;GlobalValue *&gt; anonymous{InstrProfiling.cpp}::InstrLowerer::UsedVars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### VTableDataMap {#a2dfc0cffe4a3ead105f5c8acf79e12aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;GlobalVariable *, GlobalVariable *&gt; anonymous{InstrProfiling.cpp}::InstrLowerer::VTableDataMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
