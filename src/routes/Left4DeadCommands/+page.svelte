<script>
    import * as Card from "$lib/components/ui/card";

    import { HomeOutline, ChevronDoubleRightOutline } from "flowbite-svelte-icons";
    import { Button, GradientButton } from "flowbite-svelte"
</script>

<section class="flex items-center justify-center h-screen">
    <div class="mx-12">
        <Card.Root class="xl:w-[542px] grow flex flex-col"> <!-- Game Info Card -->
            <Card.Header>
                <Card.Title>What is Left 4 Dead?</Card.Title>
                <Card.Description>October 24, 2004</Card.Description>
            </Card.Header>
            <Card.Content class="grow">
                <p>
                    <b>Left 4 Dead</b> (abbreviated <b>L4D</b>) is a singleplayer and multiplayer cooperative survival
                    horror FPS game developed by Valve Corporation and Turtle Rock Studios. The game was built using Source
                    engine and is available on PC and Xbox 360. During early development, its working title was "Terror Strike."
                    <br>
                    <br>
                    The game puts four human playable or AI-controlled Survivors of an apocalyptic pandemic against Hordes of
                    the Infected. Regular Infected are controlled by the game AI, while human players can control up to four
                    mutated Special Infected with special abilities in Versus mode. The goal of Left 4 Dead for the Survivors
                    is to help each other make it through a level to safety. Infected players must cooperate to stop them.
                </p>
            </Card.Content>
            <Card.Footer>
            <p>Information about the game</p>
            </Card.Footer>
        </Card.Root>
    </div>

    <div class="">
        <Card.Root class="xl:w-[1080px] grow flex flex-col"> <!-- Main Command Card -->
            <Card.Header>
                <Card.Title>Left 4 Dead Console Commands</Card.Title>
                <Card.Description>Console Commands for the Left 4 Dead Games</Card.Description>
            </Card.Header>
            <Card.Content class="grow">
                <h1 class="text-2xl">Console commands</h1>
                <p>
                    <b>The console</b> is a feature of many games that can be used to change certain elements of
                    a game. In Left 4 Dead and Left 4 Dead 2, it can be activated in the Options menu
                    (go to "Keyboard/Mouse", then Enable the "Allow Developer Console" option) and then displayed
                    by pressing the tilde (~) jey. Valve features a quick-type feature in their consoles that
                    allows rapid entry of commands
                    <br>
                    <br>
                    Note that the key used to access the developer console may be different on non-U.S. keyboard layouts;
                    for example, a standard UK keyboard layout uses the tilde key (left of the "1" key and below Escape)
                    <br>
                    <br>
                    You may edit the config file within your game directory directly. Located under:<br>
                    (Left 4 Dead Installation Directory> -> left4dead -> cfg -> config.cfg)<br>
                    Just open the file with a text-editor of your choice and adjust it to your needs.
                </p>
            </Card.Content>
            <Card.Footer>
                <HomeOutline class="w-4 h-4 me-2" /><Button href="/Left4DeadCommands">Left 4 Dead</Button>
                <ChevronDoubleRightOutline class="w-5 h-5 mx-2 dark:text-white" />Camp
            </Card.Footer>
        </Card.Root>
    </div>
</section>