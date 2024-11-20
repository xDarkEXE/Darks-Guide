<script>
    import * as Card from "$lib/components/ui/card";

    import { HomeOutline, ChevronDoubleRightOutline } from "flowbite-svelte-icons";
    import { Button } from "flowbite-svelte"
</script>

<section class="flex items-center justify-center h-screen">
    <div class="">
        <Card.Root class="xl:w-[900px] grow flex flex-col"> <!-- Main Command Card -->
            <Card.Header>
                <Card.Title>Left 4 Dead Console Commands</Card.Title>
                <Card.Description>Section 2.1 | Noclip</Card.Description>
            </Card.Header>
            <Card.Content class="grow">
                <h1 class="text-2xl"><b>Noclip</b></h1>
                <p>
                    Want ot go to the sky or go out of the map? Then use these commands.<br><br>
                    <code>noclip</code><br>
                    This disables collision and physics, which allows you to fly through walls
                    and in the air around the map. Now you can get a good picture<br><br>
                    <code>sv_noclipspeed</code><br>
                    This command allows you to change the spped at which you noclip. Be cautious
                    as to not set the speed too high, as you can get yourself lost outside of the map.
                </p>
            </Card.Content>
            <Card.Footer>
                <HomeOutline class="w-4 h-4 me-2" /><Button href="/Left4DeadCommands">Left 4 Dead</Button>
                <ChevronDoubleRightOutline class="w-5 h-5 mx-2 dark:text-white" /><Button href="/Left4DeadCommands/Cheats">Cheats</Button>
                <ChevronDoubleRightOutline class="w-5 h-5 mx-2 dark:text-white" /><Button href="/Left4DeadCommands/Cheats/Noclip">Noclip</Button>
            </Card.Footer>
        </Card.Root>
    </div>
</section>