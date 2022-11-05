<script setup>
const post = await fetch(`https://gbfs.divvybikes.com/gbfs/en/station_status.json`)
const res = await post.json();
</script>

<template>
    <h2>Station name</h2>
    <p>location</p>
    <p>infos</p>
</template>