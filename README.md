## EMMA SONG

‹template›
43
<div class="card edit-detail">
44
<header class="card-header">
45
<p class="card-header-title"›{{ editingproduct.name }}</p›
46
</header>
47
<div class="card-content">
48
49
50
‹div class= "content">
<div class="field" v-if="editingProduct.id"›
‹label class="label" for="id">id</label>
51
52
<input
class="input"
name="id"
53
54
placeholder="99999"
55
56
57
58
readonly
type="text"
v-model="editingProduct.id"
/>
59
</div›
60
<div class="field">
61
‹label class="label" for="name"›name</label›
62
<input
