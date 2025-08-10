---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/trailingobjects/fixedsizestorage
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `FixedSizeStorage` Struct Template

<p>A type where its <a href="/web-llvm/docs/api/structs/llvm/trailingobjects/fixedsizestorage/with-counts">with_counts</a> template member has a ::type member suitable for use as uninitialized storage for an object with the given trailing object counts. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename... Tys&gt;
struct llvm::TrailingObjects::FixedSizeStorage&lt;Tys&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">llvm/Support/TrailingObjects.h</a>"
</div>

## Description {#details}

<p>A type where its <a href="/web-llvm/docs/api/structs/llvm/trailingobjects/fixedsizestorage/with-counts">with_counts</a> template member has a ::type member suitable for use as uninitialized storage for an object with the given trailing object counts.</p>


<p>The template arguments are similar to those of additionalSizeToAlloc.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> with <a href="/web-llvm/docs/api/classes/llvm/trailingobjects/fixedsizestorageowner">FixedSizeStorageOwner</a>, e.g.:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">MyObj::FixedSizeStorage&lt;void *&gt;::with_counts&lt;1u&gt;::type myStackObjStorage;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">MyObj::FixedSizeStorageOwner</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    myStackObjOwner(</span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> ((</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> *)&amp;myStackObjStorage) MyObj);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">MyObj *</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> myStackObjPtr = myStackObjOwner.get();</span></span></div>

</div>


<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
