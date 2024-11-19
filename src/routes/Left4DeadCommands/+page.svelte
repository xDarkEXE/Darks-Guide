<script>
    import * as Card from "$lib/components/ui/card";

    import { HomeOutline, ChevronDoubleRightOutline } from "flowbite-svelte-icons";
    import { Button, GradientButton } from "flowbite-svelte"
</script>

<section class="flex items-center justify-center h-screen">
    <div class="mx-12">
        <Card.Root class="xl:w-[542px] grow flex flex-col"> <!-- Game Info Card -->
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
        <Card.Root class="xl:w-[480px] grow flex flex-col"> <!-- Main Command Card -->
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
</section>