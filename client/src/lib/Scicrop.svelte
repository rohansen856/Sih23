<script lang="ts">
    import Action from "./Action.svelte";
    import File2 from "./File2.svelte";
    import Logtitle from "./Logtitle.svelte";
</script>

<div class="flex flex-row min-h-[70%] w-screen items-center justify-evenly left-5">
    <Logtitle job={"Scientist"} />
    <div class="flex items-center gap-10 h-[60svh] w-full justify-right left-2">
        <div class="flex flex-col gap-6 h-full  justify-between w-1/3 ">
            
            <!-- <Action svg={"reviewed.svg"} text={"Disease Name"} />
            <Action svg={"eye.svg"} text={"Description"} />
            <Action svg={""} text={"Disease Prevention"}/>
            <Action svg={""} text={"Disease Spread Area"}/>
            <Action svg={""} text={"Disease Intensity"}/> -->
        
            <input class="h-2/3 px-4 items-center bg-black rounded-[1rem] border-2 border-gray-300" type="text" name="Descrpition">
            <input class="h-2/3 px-4 items-center bg-black rounded-[1rem] border-2 border-gray-300" type="text" name="Descrpition">
            <input class="h-2/3 px-4 items-center bg-black rounded-[1rem] border-2 border-gray-300" type="text" name="Descrpition">
            <input class="h-2/3 px-4 items-center bg-black rounded-[1rem] border-2 border-gray-300" type="text" name="Descrpition">
            <input class="h-2/3 px-4 items-center bg-black rounded-[1rem] border-2 border-gray-300" type="text" name="Descrpition">
            
               
        </div>
    </div>
</div>