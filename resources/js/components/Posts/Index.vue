<template>
    <div>
        <table class="table">
            <thead>
            <tr>
                <th>Title</th>
                <th>Post text</th>
                <th>Created date</th>
                <th>Actions</th>
            </tr>
            </thead>
            <tbody>
            <tr>
                <td>Something</td>
                <td>Longer Text</td>
                <td>2020-11-18</td>
                <td></td>
            </tr>
            <tr>
                <td>Something</td>
                <td>Longer Text</td>
                <td>2020-11-23</td>
                <td></td>
            </tr>
            <tr>
                <td>Something</td>
                <td>Longer Text</td>
                <td>2020-11-28</td>
                <td></td>
            </tr>
            </tbody>
        </table>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
