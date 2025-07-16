---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/vfabi
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `VFABI` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::VFABI { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/vfinfo">VFInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46c9ccb087f925d00317f16577410a13">tryDemangleForVFABI</a> (StringRef MangledName, const FunctionType *FTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> to construct a <a href="/web-llvm/docs/api/structs/llvm/vfinfo">VFInfo</a> out of a mangled names in the following format: <a href="#a46c9ccb087f925d00317f16577410a13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39">VFParamKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf19acac548dca3c8f263ceb6a860b57">getVFParamKindFromString</a> (const StringRef Token)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39">VFParamKind</a></span> from a string token. <a href="#aaf19acac548dca3c8f263ceb6a860b57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8adf44ad04562ff150b0e8e352a38d46">getVectorVariantNames</a> (const CallInst &amp;CI, SmallVectorImpl&lt; std::string &gt; &amp;VariantMappings)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populates a set of strings representing the Vector <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> ABI variants associated to the <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> CI. <a href="#a8adf44ad04562ff150b0e8e352a38d46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ae16889db439f8fbb234fe3de672d11">createFunctionType</a> (const VFInfo &amp;Info, const FunctionType *ScalarFTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> by applying vector function information to the type of a matching scalar function. <a href="#a7ae16889db439f8fbb234fe3de672d11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ad2ee389fa99a4c02f610183530735c">setVectorVariantNames</a> (CallInst *CI, ArrayRef&lt; std::string &gt; VariantMappings)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Overwrite the Vector <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> ABI variants attribute with the names provide in <span class="doxyComputerOutput">VariantMappings</span>. <a href="#a9ad2ee389fa99a4c02f610183530735c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr char <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>  *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af33ac7943ba16e891cd1b6e307029301">_LLVM_</a> = "_LLVM_"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM Internal <a href="/web-llvm/docs/api/namespaces/llvm/vfabi">VFABI</a> ISA token for vector functions. <a href="#af33ac7943ba16e891cd1b6e307029301">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr char <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>  *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b4aafd885099e61903f0a29e638a8b1">_LLVM_Scalarize_</a> = "_LLVM_Scalarize_"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prefix for internal name redirection for vector function that tells the compiler to scalarize the call using the scalar name of the function. <a href="#a3b4aafd885099e61903f0a29e638a8b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr char <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>  *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11875601ee512fa1f5cf6b6354c8def9">MappingsAttrName</a> = "vector-<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a>-abi-variant"</td>
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


<div class="doxySectionDef">

## Functions

### createFunctionType() {#a7ae16889db439f8fbb234fe3de672d11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType * llvm::VFABI::createFunctionType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/vfinfo">VFInfo</a> &amp; Info, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * ScalarFTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constructs a <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> by applying vector function information to the type of a matching scalar function.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Info</td>
<td class="doxyParamItemDescription"><p>gets the vectorization factor (VF) and the <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39">VFParamKind</a> of the parameters.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ScalarFTy</td>
<td class="doxyParamItemDescription"><p>gets the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> information of parameters, as it is not stored in <span class="doxyComputerOutput">Info</span>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a pointer to a newly created vector <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a></p></dd>
</dl>


<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>, definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a1e415dc42f391c1d0cfcc1c28c00b2f4">llvm::FunctionType::getParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#ad65790aa94dd4678a1d339d8304e1965">llvm::FunctionType::getReturnType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39adf3e3249ad10ccf5bf901eb83c105cc3">llvm::GlobalPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a88a03ab08f38a4de18c6fd653af33b80">llvm::toVectorizedTy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">llvm::Vector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#aaf2fe2b910650ab4ea0eeaca5922dce8">addVariantDeclaration</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a27cad9bebff39ed9ba603074dda1335e">replaceWithCallToVeclib</a>.</p>

</div>
</div>

### getVectorVariantNames() {#a8adf44ad04562ff150b0e8e352a38d46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VFABI::getVectorVariantNames (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; CI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::string &gt; &amp; VariantMappings)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Populates a set of strings representing the Vector <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> ABI variants associated to the <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> CI.</p>


<p>If the CI does not contain the vector-function-abi-variant attribute, we return without populating VariantMappings, i.e. callers of getVectorVariantNames need not check for the presence of the attribute (see <a href="/web-llvm/docs/api/classes/llvm/injecttlimappings">InjectTLIMappings</a>).</p>


<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>, definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a9e46a3a4bf99f8dcea9cb9efb4d977a3">llvm::CallBase::getFnAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a209a615a3a32241323420cca24b5520a">llvm::Module::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac3c35bd078a268a207f607d0f57dadba">llvm::CallBase::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4ba3a5be6c0e9b9e8a525de055836733">llvm::Instruction::getModule</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a968930aea9d9efa8d46dd890fce75643">llvm::Attribute::getValueAsString</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a11875601ee512fa1f5cf6b6354c8def9">MappingsAttrName</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a> and <a href="#a46c9ccb087f925d00317f16577410a13">tryDemangleForVFABI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#a8bde7bea5a6d6a50fd5b6d03d746e05b">addMappingsFromTLI</a>.</p>

</div>
</div>

### getVFParamKindFromString() {#aaf19acac548dca3c8f263ceb6a860b57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VFParamKind llvm::VFABI::getVFParamKindFromString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Token)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39">VFParamKind</a></span> from a string token.</p>

<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>, definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a16454c62ab71c641dedda0971980c9d5">llvm::OMP_Linear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39aaec63779faad458a0dc8cbd703de79cd">llvm::OMP_LinearPos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a1177c82a038df4f925f122e45c6da0fa">llvm::OMP_LinearRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39ab411a051b5361e5fecaebbc0c09c5a32">llvm::OMP_LinearRefPos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39acb8cf9f2514a0c9c419bbe481cd6043c">llvm::OMP_LinearUVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a3cb8b4a8b5f2ae8ebd7564386cf178c4">llvm::OMP_LinearUValPos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a33c412d71677159e382a0a8cd9408d8a">llvm::OMP_LinearVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39ab5212d79459110e59ba16ff486f4a75a">llvm::OMP_LinearValPos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39acbf35bbdad5d09f9072d0e83e78e90e4">llvm::OMP_Uniform</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a88183b946cc5f0e8c96b2e66e1c74a7e">llvm::Unknown</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">llvm::Vector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a856e22af4413a5ea9df66d623f35b824">anonymous{VFABIDemangler.cpp}::tryParseCompileTimeLinearToken</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a4c267f75d0c944ac84dff96f8a4779f3">anonymous{VFABIDemangler.cpp}::tryParseLinearTokenWithRuntimeStep</a>.</p>

</div>
</div>

### setVectorVariantNames() {#a9ad2ee389fa99a4c02f610183530735c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VFABI::setVectorVariantNames (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::string &gt; VariantMappings)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Overwrite the Vector <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> ABI variants attribute with the names provide in <span class="doxyComputerOutput">VariantMappings</span>.</p>

<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>, definition at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#a0f72a62efd0912aba72c6818c720023c">llvm::CallBase::addFnAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac3c35bd078a268a207f607d0f57dadba">llvm::CallBase::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4ba3a5be6c0e9b9e8a525de055836733">llvm::Instruction::getModule</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a11875601ee512fa1f5cf6b6354c8def9">MappingsAttrName</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; InternalLen &gt;::str</a> and <a href="#a46c9ccb087f925d00317f16577410a13">tryDemangleForVFABI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#a8bde7bea5a6d6a50fd5b6d03d746e05b">addMappingsFromTLI</a>.</p>

</div>
</div>

### tryDemangleForVFABI() {#a46c9ccb087f925d00317f16577410a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; VFInfo &gt; llvm::VFABI::tryDemangleForVFABI (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> MangledName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * FTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> to construct a <a href="/web-llvm/docs/api/structs/llvm/vfinfo">VFInfo</a> out of a mangled names in the following format:</p>


<p>&lt;VFABI_name&gt;{(&lt;redirection&gt;)}</p>


<p>where &lt;VFABI_name&gt; is the name of the vector function, mangled according to the rules described in the Vector <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> ABI of the target vector extension (or &lt;isa&gt; from now on). The &lt;VFABI_name&gt; is in the following format:</p>


<p><em>ZGV&lt;isa&gt;&lt;mask&gt;&lt;vlen&gt;&lt;parameters&gt;</em>&lt;scalarname&gt;[(&lt;redirection&gt;)]</p>


<p>This methods support demangling rules for the following &lt;isa&gt;:</p>


<ul class="doxyList ">
<li><a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a>: <a href="https://developer.arm.com/docs/101129/latest">https://developer.arm.com/docs/101129/latest</a></li>
<li>x86 (libmvec): <a href="https://sourceware.org/glibc/wiki/libmvec">https://sourceware.org/glibc/wiki/libmvec</a> and <a href="https://sourceware.org/glibc/wiki/libmvec?action=AttachFile&do=view&target=VectorABI.txt">https://sourceware.org/glibc/wiki/libmvec?action=AttachFile&amp;do=view&amp;target=VectorABI.txt</a></li>
</ul>

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MangledName</td>
<td class="doxyParamItemDescription"><p>-&gt; input string in the format <em>ZGV&lt;isa&gt;&lt;mask&gt;&lt;vlen&gt;&lt;parameters&gt;</em>&lt;scalarname&gt;[(&lt;redirection&gt;)].</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FTy</td>
<td class="doxyParamItemDescription"><p>-&gt; <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> of the scalar function which we're trying to find a vectorized variant for. This is required to determine the vectorization factor for scalable vectors, since the mangled name doesn't encode that; it needs to be derived from the widest element types of vector arguments or return values.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>, definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a14180977794bfc2a37dbffeef3ca20de">llvm::StringRef::consume_back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a610bcac0ac7e242f391a34b91889dfa5a902b0d55fddef6f8d651fe1035b7d4bd">anonymous{VFABIDemangler.cpp}::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a104d6154321899b53e40455e71d8e83a">llvm::FunctionType::getNumParams</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a0a09a1144b3dbb1ddc00f0ced5030522">anonymous{VFABIDemangler.cpp}::getScalableECFromSignature</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39adf3e3249ad10ccf5bf901eb83c105cc3">llvm::GlobalPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169ca66a0128ad08b2053e4809e07fe05728c">llvm::LLVM</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8265efd805e4ce0c9d3c18e78194324c">llvm::StringRef::ltrim</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a610bcac0ac7e242f391a34b91889dfa5ae0aa021e21dddbd6d8cecec71e9cf564">anonymous{VFABIDemangler.cpp}::OK</a>, <a href="/web-llvm/docs/api/structs/llvm/vfparameter/#a8c8f86edc9db58476d6b16903cd403ac">llvm::VFParameter::ParamKind</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a34a27457ad5d68f631c788807c4ff52c">llvm::StringRef::take_while</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a1381cfa5d5d20b2c0de03ce8f211c1cf">anonymous{VFABIDemangler.cpp}::tryParseAlign</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a1e256b3e261a7e37851be3f91173e6c0">anonymous{VFABIDemangler.cpp}::tryParseISA</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a3af3ce355fb0d93f751694070efc4c1d">anonymous{VFABIDemangler.cpp}::tryParseMask</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a71eadd5ab74bdb057ebcc6b916924f78">anonymous{VFABIDemangler.cpp}::tryParseParameter</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a14373b1995a870811ec0b24e8c7bb274">anonymous{VFABIDemangler.cpp}::tryParseVLEN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#aaf2fe2b910650ab4ea0eeaca5922dce8">addVariantDeclaration</a>, <a href="#a8adf44ad04562ff150b0e8e352a38d46">getVectorVariantNames</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a27cad9bebff39ed9ba603074dda1335e">replaceWithCallToVeclib</a> and <a href="#a9ad2ee389fa99a4c02f610183530735c">setVectorVariantNames</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### \_LLVM\_ {#af33ac7943ba16e891cd1b6e307029301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char const* llvm::VFABI::_LLVM_ = "_LLVM_"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM Internal <a href="/web-llvm/docs/api/namespaces/llvm/vfabi">VFABI</a> ISA token for vector functions.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a1e256b3e261a7e37851be3f91173e6c0">anonymous{VFABIDemangler.cpp}::tryParseISA</a>.</p>

</div>
</div>

### \_LLVM\_Scalarize\_ {#a3b4aafd885099e61903f0a29e638a8b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char const* llvm::VFABI::_LLVM_Scalarize_ = "_LLVM_Scalarize_"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prefix for internal name redirection for vector function that tells the compiler to scalarize the call using the scalar name of the function.</p>


<p>For example, a mangled name like <span class="doxyComputerOutput">_ZGV_LLVM_N2v_foo(_LLVM_Scalarize_foo)</span> would tell the vectorizer to vectorize the scalar call <span class="doxyComputerOutput">foo</span>, and to scalarize it once vectorization is done.</p>


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>

</div>
</div>

### MappingsAttrName {#a11875601ee512fa1f5cf6b6354c8def9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char const* llvm::VFABI::MappingsAttrName = "vector-<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a>-abi-variant"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<p>Referenced by <a href="#a8adf44ad04562ff150b0e8e352a38d46">getVectorVariantNames</a> and <a href="#a9ad2ee389fa99a4c02f610183530735c">setVectorVariantNames</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
