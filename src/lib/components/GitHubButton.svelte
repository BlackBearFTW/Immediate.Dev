<script lang="ts">
    import { Button } from '@svelteness/kit-docs';
    import { Github } from 'lucide-svelte';

    export let text: string = 'GitHub';
    export let link: string = 'https://github.com/ImmediatePlatform';
</script>

<Button type="raised" href={link} target="_blank">
    <div class="flex items-center justify-center gap-2">
        <Github />
        {text}
    </div>
</Button>
