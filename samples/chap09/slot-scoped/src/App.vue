<script setup lang="ts">
import OneSection from "./components/OneSection.vue";
</script>

<template>
	<section>
		<OneSection>
			<!-- <template v-slot:default="slotProps"> -->
			<template v-slot="slotProps">
				<dl>
					<dt>εε</dt>
					<dd>{{slotProps.memberInfo.name}}</dd>
					<!-- <dd>{{slotProps.memberName}}</dd> -->
					<dt>ηΆζ³</dt>
					<dd>{{slotProps.memberInfo.state}}</dd>
					<!-- <dd>{{slotProps.memberState}}</dd> -->
				</dl>
			</template>
		</OneSection>
		<!-- <OneSection/> -->
	</section>
</template>
