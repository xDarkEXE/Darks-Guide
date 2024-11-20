<script>
    import * as Card from "$lib/components/ui/card";

    import { HomeOutline, ChevronDoubleRightOutline } from "flowbite-svelte-icons";
    import { Button } from "flowbite-svelte"
</script>

<section class="flex items-center justify-center h-screen">
    <div class="">
        <Card.Root class="xl:w-[900px] grow flex flex-col"> <!-- Main Command Card -->
            <Card.Header>
                <Card.Title>Left 4 Dead Console Workaround</Card.Title>
                <Card.Description>A keyboard workaround for non-U.S. keyboard layouts</Card.Description>
            </Card.Header>
            <Card.Content class="grow">
                <h1 class="text-2xl"><b>Console workaround</b></h1>
                <p>
                    Another workaround for non-U.S. keyboard layouts -- Finnish in particular -- is to switch to a U.S
                    keyboard layout. start the game, opening the console and typing `bind X "toggleconsole"`, where X
                    is whichever key you wish to bind the command to, then switching back to your own language. if you
                    can't open the console by changing the keyboard layout, right click on Left 4 Dead 2 in your Steam
                    Library, click properties, click "Set Launch Options" then type `-console` in the field. Binding
                    `toggleconsole` to a key bypasses the Steam Cloud overwriting custom settings made, and allows you
                    to pick a key on a familiar keyboard layout. The console key chosen might not work in the lobby
                    or start menu, but it should work in-game
                </p>
            </Card.Content>
            <Card.Footer>
                <HomeOutline class="w-4 h-4 me-2" /><Button href="/Left4DeadCommands">Left 4 Dead</Button>
                <ChevronDoubleRightOutline class="w-5 h-5 mx-2 dark:text-white" /><Button href="/Left4DeadCommands/Workaround">Workaround</Button>
            </Card.Footer>
        </Card.Root>
    </div>
</section>