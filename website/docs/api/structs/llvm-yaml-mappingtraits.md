---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/mappingtraits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MappingTraits` Struct Template

<p>This class should be specialized by any type that needs to be converted to/from a YAML mapping. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class T&gt;
struct llvm::yaml::MappingTraits&lt;T&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">llvm/Support/YAMLTraits.h</a>"
</div>

## Description {#details}

<p>This class should be specialized by any type that needs to be converted to/from a YAML mapping.</p>


<p>For example:</p>



<pre><code>struct MappingTraits&lt;MyStruct&gt; {
  static void mapping(IO &amp;io, MyStruct &amp;s) {
    io.mapRequired("name", s.name);
    io.mapRequired("size", s.size);
    io.mapOptional("age",  s.age);
  }
};
</code></pre>


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
