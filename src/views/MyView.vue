

    <script>
import RawHtmlData from '../components/myComponents/RawHtmlData.vue';
import SingleComponent from '../components/myComponents/SingleComponent.vue';
import ComputedProps from '../components/myComponents/computed-properties/ComputedProps.vue';
import DirectiveVFor from '../components/myComponents/directives/DirectiveVFor.vue';
import DirectiveVIf from '../components/myComponents/directives/DirectiveVIf.vue';
import DirectiveVModel from '../components/myComponents/directives/DirectiveVModel.vue';
import DirectiveVShow from '../components/myComponents/directives/DirectiveVShow.vue';
import ParentComponent from '../components/myComponents/props/ParentComponent.vue';

        export default { components: { SingleComponent, RawHtmlData, DirectiveVShow, DirectiveVIf, DirectiveVModel, DirectiveVFor, ComputedProps, ParentComponent } };
    </script>

<template> 
    <div>
        <h1>My Single Page from FemCoders</h1>
        <!--<h3>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Neque repudiandae nulla pariatur et laborum consectetur cum tempora facilis suscipit deserunt quia maxime harum, enim ab inventore aspernatur aperiam maiores quisquam?</h3> !-->
        -----------------------------------
        <RawHtmlData />
        ---------------------------------
        <SingleComponent />
        ---------------------------------
        <DirectiveVShow />
        ---------------------------------
        <DirectiveVIf /> 
        <DirectiveVModel />
        ---------------------------------
        <DirectiveVFor/>
        ---------------------------------
        <ComputedProps />
        ---------------------------------
        <ParentComponent />
        
    </div>
</template>

<style lang="css" scoped>
    h1{
        color: red;
    }
</style>