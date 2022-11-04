<template>
  <main font-sans p="x-4 y-10" text="center gray-700 dark:gray-200">
    <div text="center" style="width: 420px;height: 60px;background-color: red;display: inline-block;overflow: hidden;">
      <div style="margin-bottom: 55px;position:relative;animation:mymove 8s infinite;height: 10px;width:300px;background-color:black;transform: rotate(-60deg);" />
      <div style="margin-bottom: 55px;position:relative;animation:mymove 8s infinite;height: 10px;width:300px;background-color:black;transform: rotate(-60deg);" />
      <div style="margin-bottom: 55px;position:relative;animation:mymove 8s infinite;height: 10px;width:300px;background-color:black;transform: rotate(-60deg);" />
      <div style="margin-bottom: 55px;position:relative;animation:mymove 8s infinite;height: 10px;width:300px;background-color:black;transform: rotate(-60deg);" />
    </div>
    <div font-extrabold style="font-size: 220px;color:red;animation: 1s blink 3 steps(1);">
      出擊
    </div>
    <div text="center" style="width: 420px;height: 60px;background-color: red;display: inline-block;" />
  </main>
</template>

<style>
  @keyframes mymove
  {
    0% {right:-200px;}
    100% {right:200px;}
  }

  @keyframes blink {
  50% { color: transparent; }
  }
</style>
