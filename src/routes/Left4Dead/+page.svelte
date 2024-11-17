<script>
    import * as Card from "$lib/components/ui/card";

    import { HomeOutline, ChevronDoubleRightOutline } from "flowbite-svelte-icons";
    import { Button } from "flowbite-svelte"
</script>

<section class="flex items-center justify-center h-screen">
    <div class="">
        <Card.Root class="xl:w-[480px] grow flex flex-col"> <!-- Main Guide Card -->
            <Card.Header>
                <Card.Title>Left 4 Dead Game Guide</Card.Title>
                <Card.Description></Card.Description>
            </Card.Header>
            <Card.Content class="grow">
                <p>sdkjhgkjsdg</p>
            </Card.Content>
            <Card.Footer>
                <HomeOutline class="w-4 h-4 me-2" /><Button href="/Left4Dead">Left 4 Dead</Button>
                <ChevronDoubleRightOutline class="w-5 h-5 mx-2 dark:text-white" />Camp
            </Card.Footer>
        </Card.Root>
    </div>

    <div class="ms-12">
        <Card.Root class="xl:w-[542px] grow flex flex-col"> <!-- Main Guide Card -->
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
                <ChevronDoubleRightOutline class="w-4 h-4 me-2 dark:text-white" /><Button href="/Left4Dead">Blog Posts</Button>
            </Card.Footer>
        </Card.Root>
    </div>
</section>