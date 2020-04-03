# vscode-snippets

## Vue
- 
  - Command `vtc`
  - Snippet
    ```vue
    <template>
        <div></div>
    </template>

    <script lang="ts">
    import { createComponent } from "@vue/composition-api"

    export default createComponent({
        name: "",
        setup() {
            return {}
        }
    })
    </script>
    ```
