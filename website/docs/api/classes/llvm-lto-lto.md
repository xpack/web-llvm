---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/lto/lto
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LTO` Class Reference

<p>This class implements a resolution-based interface to LLVM's <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> functionality. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::lto::LTO { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">llvm/LTO/LTO.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f60c0e71db604ad4a32f3d351fd188e">ModuleMapType</a> = <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LTOKind { <a href="#a543ba3f4e6777febf274a87ea5ac9bd7">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unified <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> modes. <a href="#a543ba3f4e6777febf274a87ea5ac9bd7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a018a3788daddbb88cb4308d0a0e715">LTO</a> (Config Conf, ThinBackend Backend={}, unsigned ParallelCodeGenParallelismLevel=1, LTOKind LTOMode=LTOK_Default)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> object. <a href="#a0a018a3788daddbb88cb4308d0a0e715">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59554a4c5ca04b6d82e78d46a518be04">~LTO</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c3e8ed752bc7ef92ccb9edbd4bb014a">add</a> (std::unique_ptr&lt; InputFile &gt; Obj, ArrayRef&lt; SymbolResolution &gt; Res)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an input file to the <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> link, using the provided symbol resolutions. <a href="#a0c3e8ed752bc7ef92ccb9edbd4bb014a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0010e13022065d0cb4a16df7547a232">getMaxTasks</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an upper bound on the number of tasks that the client may expect. <a href="#ac0010e13022065d0cb4a16df7547a232">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada5eca1803d5afcb1005ea05ffc62636">run</a> (AddStreamFn AddStream, FileCache Cache={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Runs the <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> pipeline. <a href="#ada5eca1803d5afcb1005ea05ffc62636">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d5eaa05fdf3c1e1d36cd91c4d4cf59f">releaseGlobalResolutionsMemory</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f8b683055b34650112c3df6ac09afe5">addModuleToGlobalRes</a> (ArrayRef&lt; InputFile::Symbol &gt; Syms, ArrayRef&lt; SymbolResolution &gt; Res, unsigned Partition, bool InSummary)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27aa46b81cbda8004ab1a9664c72a4ba">addModule</a> (InputFile &amp;Input, unsigned ModI, const SymbolResolution *&amp;ResI, const SymbolResolution *ResE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/lto/lto/regularltostate/addedmodule">RegularLTOState::AddedModule</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8d6edfab9c561f9d0465f5f02fca1ce">addRegularLTO</a> (BitcodeModule BM, ArrayRef&lt; InputFile::Symbol &gt; Syms, const SymbolResolution *&amp;ResI, const SymbolResolution *ResE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab876974b269a096668ed38884cca974">linkRegularLTO</a> (RegularLTOState::AddedModule Mod, bool LivenessFromIndex)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40426eca51c8b07722c0295348921fa1">addThinLTO</a> (BitcodeModule BM, ArrayRef&lt; InputFile::Symbol &gt; Syms, const SymbolResolution *&amp;ResI, const SymbolResolution *ResE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fac96b8cb48fc62319ef288c0f35a95">runRegularLTO</a> (AddStreamFn AddStream)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b1e21aff4b2868dcad26000e10bd01d">runThinLTO</a> (AddStreamFn AddStream, FileCache Cache, const DenseSet&lt; GlobalValue::GUID &gt; &amp;GUIDPreservedSymbols)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79f17fc7cb1ad6c1c1d745b6bccff91f">checkPartiallySplit</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8c7a47e005bef362626cab95a1f533a">InputFile</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a312580c6274344cba1b260c2da7cf20e">Conf</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d95862cddd4435d8d47dbaa6bf080a3">RegularLTO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b1567d041192ece0b2efbe821654187">ThinLTO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">llvm::BumpPtrAllocator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6031c1b9100c3523497dfd335aaa013e">Alloc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/stringsaver">llvm::StringSaver</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a600ea230e38e1325723034b1e3623783">GlobalResolutionSymbolSaver</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/densemap">llvm::DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, GlobalResolution &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3336b509dd8c0377673a74dbf548ab85">GlobalResolutions</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91aac69b4b0d49d0506d4ad4e85f28ba">CalledGetMaxTasks</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a543ba3f4e6777febf274a87ea5ac9bd7">LTOKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4b96cdfc29ffd11cf6b800f70d4429a">LTOMode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bc5a269fed2a3f298024287417fcced">EnableSplitLTOUnit</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6b7615b073ced129938f9e5c16693f2">DynamicExportSymbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/tooloutputfile">ToolOutputFile</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a3991874cc588ee0322718da991272">DiagnosticOutputFile</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16f1688d08d2485bde377198865fc209">getRuntimeLibcallSymbols</a> (const Triple &amp;TT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Static method that returns a list of libcall symbols that can be generated by <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> but might not be visible from bitcode symbol table. <a href="#a16f1688d08d2485bde377198865fc209">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class implements a resolution-based interface to LLVM's <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> functionality.</p>


<p>It supports regular <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a>, parallel <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> code generation and ThinLTO. You can use it from a linker in the following way:</p>


<ul class="doxyList ">
<li>Set hooks and code generation options (see <a href="/web-llvm/docs/api/structs/llvm/lto/config">lto::Config</a> struct defined in <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>), and use the <a href="/web-llvm/docs/api/structs/llvm/lto/config">lto::Config</a> object to create an <a href="/web-llvm/docs/api/classes/llvm/lto/lto">lto::LTO</a> object.</li>
<li>Create <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">lto::InputFile</a> objects using <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile/#a1aa10be5e2a432c4ca74d5f70c0cd77c">lto::InputFile::create()</a>, then use the symbols() function to enumerate its symbols and compute a resolution for each symbol (see <a href="/web-llvm/docs/api/structs/llvm/lto/symbolresolution">SymbolResolution</a> below).</li>
<li>After the linker has visited each input file (and each regular object file) and computed a resolution for each symbol, take each <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">lto::InputFile</a> and pass it and an array of symbol resolutions to the <a href="#a0c3e8ed752bc7ef92ccb9edbd4bb014a">add()</a> function.</li>
<li>Call the <a href="#ac0010e13022065d0cb4a16df7547a232">getMaxTasks()</a> function to get an upper bound on the number of native object files that <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> may add to the link.</li>
<li>Call the <a href="#ada5eca1803d5afcb1005ea05ffc62636">run()</a> function. This function will use the supplied AddStream and Cache functions to add up to <a href="#ac0010e13022065d0cb4a16df7547a232">getMaxTasks()</a> native object files to the link.</li>
</ul>

<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ModuleMapType {#a4f60c0e71db604ad4a32f3d351fd188e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::lto::LTO::ModuleMapType =  MapVector&lt;StringRef, BitcodeModule&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### LTOKind {#a543ba3f4e6777febf274a87ea5ac9bd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::lto::LTO::LTOKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unified <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> modes.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTOK_Default<a id="a543ba3f4e6777febf274a87ea5ac9bd7a7f9c9642d0db28894d5090e409170a51"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> mode without Unified <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a>. The default mode</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTOK_UnifiedRegular<a id="a543ba3f4e6777febf274a87ea5ac9bd7a3bf35a26245c7fda5c396fa75d60f233"></a></td>
<td class="doxyEnumItemDescription">Regular <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a>, with Unified <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> enabled</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTOK_UnifiedThin<a id="a543ba3f4e6777febf274a87ea5ac9bd7ab5910a71a2d4f525028db5da72317ab9"></a></td>
<td class="doxyEnumItemDescription">ThinLTO, with Unified <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> enabled</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LTO() {#a0a018a3788daddbb88cb4308d0a0e715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LTO::LTO (<a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> Conf, <a href="/web-llvm/docs/api/structs/llvm/lto/thinbackend">ThinBackend</a> Backend={}, unsigned ParallelCodeGenParallelismLevel=1, <a href="#a543ba3f4e6777febf274a87ea5ac9bd7">LTOKind</a> LTOMode=<a href="#a543ba3f4e6777febf274a87ea5ac9bd7a7f9c9642d0db28894d5090e409170a51">LTOK_Default</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> object.</p>


<p>A default constructed <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> object has a reasonable production configuration, but you can customize it by passing arguments to this constructor. FIXME: We do currently require the DiagHandler field to be set in Conf. Until that is fixed, a <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> argument is required.</p>


<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 607 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad2ec9538a004e1c820511dd7d55441f5">llvm::LTOKeepSymbolCopies</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LTO() {#a59554a4c5ca04b6d82e78d46a518be04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LTO::~LTO ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a0c3e8ed752bc7ef92ccb9edbd4bb014a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LTO::add (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">InputFile</a> &gt; Obj, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/lto/symbolresolution">SymbolResolution</a> &gt; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an input file to the <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> link, using the provided symbol resolutions.</p>


<p>The symbol resolutions must appear in the enumeration order given by <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile/#a4ff6ebe6ed80ef8ec41cc716216d05f4">InputFile::symbols()</a>.</p>


<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 728 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a6df1c201fe73a270f67a7c153c42c0bea89d9995963600df8c6854372881cbbb7">llvm::lto::Config::ELF</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#aea6d215256ae43bc9149bf41f2cc7694">llvm::Triple::isOSBinFormatELF</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#a2b96fb8bf782a1b498a82682ab8e74c9">writeToResolutionFile</a>.</p>

</div>
</div>

### getMaxTasks() {#ac0010e13022065d0cb4a16df7547a232}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LTO::getMaxTasks ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an upper bound on the number of tasks that the client may expect.</p>


<p>This may only be called after all IR object files have been added. For a full description of tasks see <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/ltobackend-h">LTOBackend.h</a>.</p>


<p>Declaration at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 1110 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

### run() {#ada5eca1803d5afcb1005ea05ffc62636}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LTO::run (<a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a> AddStream, <a href="/web-llvm/docs/api/structs/llvm/filecache">FileCache</a> Cache={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Runs the <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> pipeline.</p>


<p>This function calls the supplied AddStream function to add native object files to the link.</p>


<p>The Cache parameter is optional. If supplied, it will be used to cache native object files and add them to the link.</p>


<p>The client will receive at most one callback (via either AddStream or Cache) for each task identifier.</p>


<p>Declaration at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 1161 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee23fa24e474fb6e443445dd3545adf9">llvm::computeDeadSymbolsWithConstProp</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3e999e4bb7297d284f931638721840e5">llvm::GlobalValue::dropLLVMManglingEscape</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/symbolresolution/#a46d7d11866406ec8debc4b5929006fe7">llvm::lto::SymbolResolution::ExportDynamic</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a71ee7e63264e4997a3340a781d44832e">llvm::GlobalValue::getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac505d74d262ee1e64d87b07121199e36abafd7322c6e97d25b6299b5d6fe8920b">llvm::No</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/symbolresolution/#a61e14815eb907619ac67d15a4cf569c9">llvm::lto::SymbolResolution::Prevailing</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec1a19ebf309a206257e212c33f045a1">llvm::PrintStatisticsJSON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a7df2e6bd8a987ca6e4e4ced678ecbfcf">llvm::lto::setupStatsFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e71e9f801d8c3d999ee7a7f3cd8b1c3">llvm::SupportsHotColdNew</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac505d74d262ee1e64d87b07121199e36a88183b946cc5f0e8c96b2e66e1c74a7e">llvm::Unknown</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac505d74d262ee1e64d87b07121199e36a93cba07454f06a4a960172bbd6e2a435">llvm::Yes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addModule() {#a27aa46b81cbda8004ab1a9664c72a4ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LTO::addModule (<a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">InputFile</a> &amp; Input, unsigned ModI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/symbolresolution">SymbolResolution</a> *&amp; ResI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/symbolresolution">SymbolResolution</a> * ResE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 750 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

### addModuleToGlobalRes() {#a0f8b683055b34650112c3df6ac09afe5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LTO::addModuleToGlobalRes (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/lto/inputfile/symbol">InputFile::Symbol</a> &gt; Syms, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/lto/symbolresolution">SymbolResolution</a> &gt; Res, unsigned Partition, bool InSummary)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 626 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

### addRegularLTO() {#ab8d6edfab9c561f9d0465f5f02fca1ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; LTO::RegularLTOState::AddedModule &gt; LTO::addRegularLTO (<a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> BM, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/lto/inputfile/symbol">InputFile::Symbol</a> &gt; Syms, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/symbolresolution">SymbolResolution</a> *&amp; ResI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/symbolresolution">SymbolResolution</a> * ResE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 839 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

### addThinLTO() {#a40426eca51c8b07722c0295348921fa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LTO::addThinLTO (<a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> BM, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/lto/inputfile/symbol">InputFile::Symbol</a> &gt; Syms, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/symbolresolution">SymbolResolution</a> *&amp; ResI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/symbolresolution">SymbolResolution</a> * ResE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 1031 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

### checkPartiallySplit() {#a79f17fc7cb1ad6c1c1d745b6bccff91f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LTO::checkPartiallySplit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 1119 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

### linkRegularLTO() {#aab876974b269a096668ed38884cca974}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LTO::linkRegularLTO (<a href="/web-llvm/docs/api/structs/llvm/lto/lto/regularltostate/addedmodule">RegularLTOState::AddedModule</a> Mod, bool LivenessFromIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 993 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

### releaseGlobalResolutionsMemory() {#a9d5eaa05fdf3c1e1d36cd91c4d4cf59f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LTO::releaseGlobalResolutionsMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 500 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

### runRegularLTO() {#a3fac96b8cb48fc62319ef288c0f35a95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LTO::runRegularLTO (<a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a> AddStream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 522 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 1250 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

### runThinLTO() {#a5b1e21aff4b2868dcad26000e10bd01d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LTO::runThinLTO (<a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a> AddStream, <a href="/web-llvm/docs/api/structs/llvm/filecache">FileCache</a> Cache, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; GUIDPreservedSymbols)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 1842 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Alloc {#a6031c1b9100c3523497dfd335aaa013e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;llvm::BumpPtrAllocator&gt; llvm::lto::LTO::Alloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### CalledGetMaxTasks {#a91aac69b4b0d49d0506d4ad4e85f28ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::LTO::CalledGetMaxTasks = false</td>
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



<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### Conf {#a312580c6274344cba1b260c2da7cf20e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Config llvm::lto::LTO::Conf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### DiagnosticOutputFile {#a24a3991874cc588ee0322718da991272}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ToolOutputFile&gt; llvm::lto::LTO::DiagnosticOutputFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### DynamicExportSymbols {#aa6b7615b073ced129938f9e5c16693f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;GlobalValue::GUID&gt; llvm::lto::LTO::DynamicExportSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### EnableSplitLTOUnit {#a1bc5a269fed2a3f298024287417fcced}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::lto::LTO::EnableSplitLTOUnit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### GlobalResolutions {#a3336b509dd8c0377673a74dbf548ab85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;llvm::DenseMap&lt;StringRef, GlobalResolution&gt; &gt; llvm::lto::LTO::GlobalResolutions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### GlobalResolutionSymbolSaver {#a600ea230e38e1325723034b1e3623783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;llvm::StringSaver&gt; llvm::lto::LTO::GlobalResolutionSymbolSaver</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### InputFile {#aa8c7a47e005bef362626cab95a1f533a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::lto::LTO::InputFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### LTOMode {#aa4b96cdfc29ffd11cf6b800f70d4429a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LTOKind llvm::lto::LTO::LTOMode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### RegularLTO {#a0d95862cddd4435d8d47dbaa6bf080a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct llvm::lto::LTO::RegularLTOState llvm::lto::LTO::RegularLTO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### ThinLTO {#a9b1567d041192ece0b2efbe821654187}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct llvm::lto::LTO::ThinLTOState llvm::lto::LTO::ThinLTO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getRuntimeLibcallSymbols() {#a16f1688d08d2485bde377198865fc209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; const char * &gt; LTO::getRuntimeLibcallSymbols (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT)</td>
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

<p>Static method that returns a list of libcall symbols that can be generated by <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> but might not be visible from bitcode symbol table.</p>

<p>Declaration at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 1382 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d13fd05401d8eb0c97b9864a0eb6028">llvm::copy_if</a> and <a href="/web-llvm/docs/api/structs/llvm/rtlib/runtimelibcallsinfo/#afc8703e1774b4164e9c64e76074a3a1b">llvm::RTLIB::RuntimeLibcallsInfo::getLibcallNames</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
