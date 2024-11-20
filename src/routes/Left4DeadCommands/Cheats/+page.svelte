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
                <Card.Description>Section 1 | Cheats</Card.Description>
            </Card.Header>
            <Card.Content class="grow">
                <h1 class="text-2xl"><b>Cheats</b></h1>
                <hr>
                <p>
                    the `sv_cheats` console variable is a prerequisite command to many of the game-altering
                    commands found in the Left 4 Dead series (including other Valve games, such as Half-Life).
                    In the Left 4 Dead series, by settings sv_cheats to 1, most commands are then recognized
                    by the game. It is with `sv_cheats 1` that most of the exploits were found by users in the
                    demo during its pre-order era.
                    <br>
                    <br>
                    Enabling cheats disallows unlocking achievements. This includes Grind Achievements, which are
                    achievements based on your lifetime performance (i.e killing 5,359 Zombies in Crash Course) and
                    any other Achievement that uses a counter-based system to acquire (i.e. Collect 10 Boomer Bile
                    off Dead CEDA Agents) as well, so any Infected killed with cheats enabled will not count towards
                    Zombie Genocides or any similar achievement.<br>
                    Even when turned off, achievements are <b>still disabled</b>. Only restarting the particular game
                    will allow achievemnts. Achievements can still be earned through an online game as long as cheats were
                    never enabled on that server.
                    <br>
                    <br>
                    Unfortunately, enabling cheats in <b>Left 4 Dead 2</b> is more complicated than in the previous game.
                    Cheats must be enabled in the main menu, before starting a game, and even then you must use the `map`
                    command to load a game with cheats enabled - starting a local server via any of the lobbies will
                    disable cheats.
                </p>
            </Card.Content>
            <Card.Footer>
                <HomeOutline class="w-4 h-4 me-2" /><Button href="/Left4DeadCommands">Left 4 Dead</Button>
                <ChevronDoubleRightOutline class="w-5 h-5 mx-2 dark:text-white" /><Button href="/Left4DeadCommands/Cheats">Cheats</Button>
            </Card.Footer>
        </Card.Root>
    </div>
</section>