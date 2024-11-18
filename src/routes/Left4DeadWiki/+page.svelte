<script>
    import * as Card from "$lib/components/ui/card";

    import { HomeOutline, ChevronDoubleRightOutline } from "flowbite-svelte-icons";
    import { Button, GradientButton } from "flowbite-svelte"
</script>

<section class="flex items-center justify-center h-screen">
    <div class="mx-12">
        <Card.Root class="xl:w-[542px] grow flex flex-col"> <!-- Steam Update Card -->
            <Card.Header>
                <Card.Title>Left 4 Dead Steam Update</Card.Title>
                <Card.Description>October 24, 2024</Card.Description>
            </Card.Header>
            <Card.Content class="grow">
                <p>
                    An update has been released for Left 4 Dead 2<br>
                        - Fixed several crash and remote code execution exploits.<br>
                        - Fixed a crash on some NVIDIA graphics card when shader detail is set to High.
                        <br>
                        <br>
                    Take a look at the new Update <a class="text-green-700" href="https://store.steampowered.com/news/app/550/view/4538032056440979617?l=english">here</a>.
                </p>
            </Card.Content>
            <Card.Footer>
                <ChevronDoubleRightOutline class="w-4 h-4 me-2 dark:text-white" /><Button href="/Left4DeadWiki">Blog Posts</Button>
            </Card.Footer>
        </Card.Root>
    </div>

    <div class="">
        <Card.Root class="xl:w-[480px] grow flex flex-col"> <!-- Main Wiki Card -->
            <Card.Header>
                <Card.Title>Left 4 Dead Wiki</Card.Title>
                <Card.Description></Card.Description>
            </Card.Header>
            <Card.Content class="grow">
                <center>
                    <p><b>Content</b></p>
                    <Button href="/Left4DeadWiki/The_Director">The Director</Button>
                    <Button href="/Left4DeadWiki/Gameplay_Modes">Gameplay Modes</Button>
                    <Button href="/Left4DeadWiki/Left_4_Dead">Left 4 Dead</Button>
                    <Button href="/Left4DeadWiki/Left_4_Dead_2">Left 4 Dead 2</Button>
                </center>
            </Card.Content>
            <Card.Footer>
                <HomeOutline class="w-4 h-4 me-2" /><Button href="/Left4DeadWiki">Left 4 Dead</Button>
                <ChevronDoubleRightOutline class="w-5 h-5 mx-2 dark:text-white" />Camp
            </Card.Footer>
        </Card.Root>
    </div>

    <div class="ms-12">
        <Card.Root class="xl:w-[542px] grow flex flex-col"> <!-- Blog Post Card -->
            <Card.Header>
                <Card.Title>Left 4 Dead Blog Post</Card.Title>
                <Card.Description>September 17, 2020 | The Last Stand (Free Weekend)</Card.Description>
            </Card.Header>
            <Card.Content class="grow">
                <p>
                    <b>Left 4 Dead 2: The Last Stand Community Update</b> 
                    is shipping September 24th, and we're celebrating with a <b>free weekend!</b><br>
                    Grab your friends and tackle the zombie horde in over twenty new 
                    survival arenas, four new scavenge arenas, and a campaign based on The 
                    Lighthouse survival map. New achievements, melee weapons, 
                    animations, dialog, competitive balance adjustments, and other surprises 
                    round out this official update for Left 4 Dead 2 created by the community, 
                    for the community.<br>
                    Take a look at the new trailer <a class="text-green-700" href="https://www.youtube.com/watch?v=bjnhx8Ip2Y8">here</a>.
                </p>
            </Card.Content>
            <Card.Footer>
                <ChevronDoubleRightOutline class="w-4 h-4 me-2 dark:text-white" /><Button href="/Left4DeadWiki">Blog Posts</Button>
            </Card.Footer>
        </Card.Root>
    </div>
</section>