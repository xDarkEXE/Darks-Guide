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
                <Card.Description>Section 2 | Annotated list of commands</Card.Description>
            </Card.Header>
            <Card.Content class="grow">
                <h1 class="text-2xl"><b>Annotated list of commands</b></h1>
                <hr>
                <p>
                    Knowing all the commands isn't quite as good as knowing what they do.
                    The following will describe what each command does and its default value.
                    <br>
                    <br>
                    Important things to know about your cheat consoles:<br>
                    - Some commands require you to be the game host (such as `sv_cheats`).<br><br>
                    - It is assumed that you have cheats enabled for the commands described in this section.<br><br>
                    - If you turn on cheats then turn them off, many settings are discarded!<br><br>
                    - The console can auto-complete commands, making it inefficient to type more than you need to;
                    just type a few letters and then hit the up/down arrows.<br><br>
                    - Commands can be chained. Example: `sv_cheats 1; z_spawn boomer; z_spawn hunter; z_spawn smoker; sv_cheats 0;`
                    enable cheats, spawn a bommer, hunter, smoker, then turn off cheats, all in that order.
                    - You can store your commands in the "autoexec.cfg" file you create in a text editor like "Notepad" or
                    "Notepad++" and put it in (steam install directory)/steamapps/common/left 4 dead/left4dead/cfg. While
                    it isn't necessary to store it in the autoexec file, doing so will alow automatic execution of commands
                    saved when your server runs. You can also execute a particular config file, for instance, "die.cfg", by
                    inputting "exec die" in the console.<br><br>
                    - If you are not sure of the correct spelling of a command, just type the first set of letters that you
                    know and press "Tab." A list will appear below that input field listing each command beginning with what
                    you have just typed. Press the "Tab" key to cycle through the commands listed.
                </p>
            </Card.Content>
            <Card.Footer>
                <HomeOutline class="w-4 h-4 me-2" /><Button href="/Left4DeadCommands">Left 4 Dead</Button>
                <ChevronDoubleRightOutline class="w-5 h-5 mx-2 dark:text-white" /><Button href="/Left4DeadCommands/Cheats/CheatHelp">Annotated list of commands</Button>
            </Card.Footer>
        </Card.Root>
    </div>
</section>