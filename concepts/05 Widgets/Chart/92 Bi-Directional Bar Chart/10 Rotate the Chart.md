Bars in the **Stacked Bar** series are vertical by default. Change them to horizontal by setting the [rotated](/api-reference/20%20Data%20Visualization%20Widgets/dxChart/1%20Configuration/rotated.md '/Documentation/ApiReference/Data_Visualization_Widgets/dxChart/Configuration/#rotated') option to **true**.

---
##### jQuery

    <!--JavaScript-->$(function() {
        $("#chartContainer").dxChart({
            // ...
            rotated: true
        });
    });

##### Angular

    <!--HTML--><dx-chart ...
        [rotated]="true">
    </dx-chart>

##### Vue

    <!-- tab: App.vue -->
    <template> 
        <DxChart ...
            :rotated="true">
        </DxChart>
    </template>

    <script>
    import DxChart from 'devextreme-vue/chart';

    export default {
        components: {
            DxChart
        }
    }
    </script>

##### React

    <!-- tab: App.js -->
    import React from 'react';
    import Chart from 'devextreme-react/chart';

    class App extends React.Component {
        render() {
            return (
                <Chart ...
                    rotated={true}>
                </Chart>
            );
        }
    }

---

#####See Also#####
- [Rotate and Invert the Chart](/concepts/05%20Widgets/Chart/90%20Rotate%20and%20Invert%20the%20Chart.md '/Documentation/Guide/Widgets/Chart/Rotate_and_Invert_the_Chart/')
