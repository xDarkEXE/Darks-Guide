<script>
    import * as Card from "$lib/components/ui/card";

    import { HomeOutline, ChevronDoubleRightOutline } from "flowbite-svelte-icons";
    import { Button, GradientButton } from "flowbite-svelte"
</script>

<section class="flex items-center justify-center h-screen">
    <div class="">
        <Card.Root class="xl:w-[510px] grow flex flex-col"> <!-- Main Wiki Card -->
            <Card.Header>
                <Card.Title>The Director</Card.Title>
                <Card.Description></Card.Description>
            </Card.Header>
            <Card.Content class="grow">
                <p>
                    <b>The Director</b> (sometimes referred to as <b>The AI Director</b>, or simply as <b>AID</b>) is the artificial intelligence of
                    Left 4 Dead that features a dynamic system for game dramatics, pacing, and difficulty
                </p>
            </Card.Content>
            <Card.Footer>
                <HomeOutline class="w-4 h-4 me-2" />In:<Button class="text-green-700 ms-2" href="/Left4DeadWiki">Game Mechanics</Button>
            </Card.Footer>
        </Card.Root>
    </div>
</section>