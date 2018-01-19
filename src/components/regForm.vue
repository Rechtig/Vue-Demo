<template>
	<div class="login-form">
		<div class="g-form">
			<div class="g-form-line" >
				<span class="g-form-label">用户名:</span>
				<div class="g-form-input">
					<input type="text" placeholder="请输入用户名">
				</div>
			</div>
			<div class="g-form-line">
				<div class="g-form-btn">
					<a class="button" @click="onLogin">登陆</a>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	export default{
		props:{
	        'isShow':'boolean'
		},
		data(){
			return{}
		},
		computed:{
			userErrors(){
				let errorText, status
				if(!/@/g.test(this.usernameModel)){
					status = false
					errorText = '不包含@'
				}else{
					status = true
					errorText = ''
				}
				if(!this.userFlag){
					errorText = ''
					this.userFlag = true
				}
				return{
					status,
					errorText
				}
			},
			passwordErrors(){
				let errorText,status
				if(!/^\w{1,6}$/g.test(passwordModel)){
					status = false
					errorText = '密码不是1-6位'
				}else{
					status = true
					errorText = ''
				}
				if(!this.passwordFlag){
					errorText = ''
					this.passwordFlag = true
				}
				return{
					status,
					errorText
				}
			}
	    },
		methods:{
	        onLogin(){
	        	
	        }
		}
	}
</script>

<style scoped>
	
</style>