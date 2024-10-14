<script>
    import Header from "./UI/Header.svelte";

    const meetups = [
        {
            id: 'm1',
            title: 'Coding Bootcamp',
            subtitle: 'Learn to code in 2 hours',
            description: 'In this meetup, we will have some experts that teach you how to code',
            address: '27th Nerd Road, 32523 New York',
            contactEmail: 'code@test.com'
        },
        {
            id: 'm2',
            title: 'Swim',
            subtitle: 'Learn to Swim',
            description: 'In this meetup, we will have some experts that teach you how to swim',
            address: '27th Nerd Road, 32523 New York',
            contactEmail: 'code@test.com'
        }


        ]
</script>

<Header/>
{#each  meetups as meetup}
    
{/each}

    
