<script>
    import * as Card from "$lib/components/ui/card";

    import { HomeOutline, ChevronDoubleRightOutline } from "flowbite-svelte-icons";
    import { Button, GradientButton, Video } from "flowbite-svelte";
</script>

<section class="flex items-center justify-center h-screen">
    <div class="">
        <Card.Root class="xl:w-[480px] grow flex flex-col"> <!-- Main Command Card -->
            <Card.Header>
                <Card.Title>Minecraft Wiki</Card.Title>
                <Card.Description></Card.Description>
            </Card.Header>
            <Card.Content class="grow">
                <center>
                    <p>Current Games</p>
                </center>
                <p>
                    Minecraft is a 3D sandbox game developed by Mojang Studios where players<br>
                    interact with a fully modifiable three-dimensional environment made of blocks and<br>
                    entities
                </p>
            </Card.Content>
            <Card.Footer>
                <HomeOutline class="w-4 h-4 me-2" /><Button href="/MinecraftWiki">Minecraft</Button>
                <!-- <ChevronDoubleRightOutline class="w-5 h-5 mx-2 dark:text-white" />Camp -->
            </Card.Footer>
        </Card.Root>
    </div>
</section>