<template>
<admin-view-layout>
    <b-container slot="admin-view-content">
        <b-row>
            <b-col cols="12">
                <power-management></power-management>
            </b-col>
        </b-row>
    </b-container>
</admin-view-layout>
</template>

<script>
import AdminViewLayout from '@/components/admin/AdminViewLayout.vue'

import PowerManagement from '@/components/admin/PowerManagement.vue'

export default {
    components: {
        'admin-view-layout': AdminViewLayout,
        'power-management': PowerManagement
    }
}
</script>