<script>
    import { Checkbox } from 'flowbite-svelte';
</script>

<style>
    h6 {
        text-align: center;
        font-weight: bold;
        font-size: 24px;
    }
    h2{
        text-align: center;
    }
    
    .container {
        display: grid;
        grid-template-columns: repeat(3, 1fr); 
        grid-gap: 10px; 
        align-items: center;
        justify-items: center;
    }

    .center-container {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        height: 100vh;
    }
</style>

<div class="center-container">
    <h6 class="centered-text">Populate Fake Data</h6>
    <div class="centered-text">Generate fake data, or build your API query here.</div>
    <div class="container">
        <Checkbox>Names</Checkbox>
        <Checkbox>SSNs</Checkbox>
        <Checkbox>License Plates</Checkbox>

        <Checkbox>Emails</Checkbox>
        <Checkbox>Corporate Emails</Checkbox>
        <Checkbox>Phone Number</Checkbox>

        <Checkbox>Addresses</Checkbox>
        <Checkbox>Cities</Checkbox>
        <Checkbox>Companies</Checkbox>

        <Checkbox>Dates</Checkbox>
        <Checkbox>Jobs</Checkbox>
        <Checkbox>Websitex</Checkbox>

        Data Points <b>(e.g. 1 - 2000)</b>
    </div>
</div>
