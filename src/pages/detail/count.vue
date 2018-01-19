<template>
	<div class="sales-board">
		<div class="sales-board-intro">
			<h2>数据统计</h2>
			<p>史资料、科学实验、检验、统计等所获得的和用于科学研究、技术设计、查证、决策等的数值加以统计为解决方案做前期准备。</p>
	    </div>
	    <div class="sales-board-form">
			<div class="sales-board-line">
	            <div class="sales-board-line-left">
	                产品类型：
	            </div>
	            <div class="sales-board-line-right">
	                <v-chooser :selections="buyTypes"></v-chooser>
	            </div>
	        </div>
	        <div class="sales-board-line">
	            <div class="sales-board-line-left">
	                适用地区：
	            </div>
	            <div class="sales-board-line-right">
	                <v-selection :selections="districts"></v-selection>
	            </div>
	        </div>
	        <div class="sales-board-line">
	            <div class="sales-board-line-left">
	                有效时间：
	            </div>
	            <div class="sales-board-line-right">
	                半年
	            </div>
	        </div>
	        <div class="sales-board-line">
	            <div class="sales-board-line-left">
	                总价：
	            </div>
	            <div class="sales-board-line-right">
	                500 元
	            </div>
	        </div>
	        <div class="sales-board-line">
	            <div class="sales-board-line-left">
	                &nbsp;
	            </div>
	            <div class="sales-board-line-right">
	                <div class="button">
	                	立即购买
	                </div>
	            </div>
	        </div>
		</div>
		<div class="sales-board-des">
			<h2>产品说明</h2>
			<p>广告活动按照广告计划执行，到完成广告创作并形成广告作品之后，经过广告主的最后审核同意，即可送到预定的媒介发布刊播。这项工作一般由媒介部门的有关专业人员负责，他们的任务就是专门负责与有关媒介单位接洽，安排有关广告的发播事宜，并对发播质量实施监督。</p>

			<table class="sales-board-tabel">
				<tbody>
					<tr class="ui-table-row">
						<td class="col-first">
							<div class="intro-pic">
								<label>安全安保</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>办公文教</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>彩票</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>车辆物流</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>成人用品</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>出版媒体</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>电脑硬件</label>
							</div>
						</td>
					</tr>
					<tr class="ui-table-row">
						<td class="col-first">
							<div class="intro-pic">
								<label>电子电工</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>房地产建筑装修</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>分类平台</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>服装鞋帽</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>箱包饰品</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>化工原料制品</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>机械设备</label>
							</div>
						</td>
					</tr>
					<tr class="ui-table-row">
						<td class="col-first">
							<div class="intro-pic">
								<label>家庭日用品</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>家用电器</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>教育培训</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>节能环保</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>金融服务</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>礼品</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>旅游住宿</label>
							</div>
						</td>
					</tr>
					<tr class="ui-table-row">
						<td class="col-first">
							<div class="intro-pic">
								<label>美容化妆</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>母婴护理</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>农林牧渔</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>软件</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>商务服务</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>生活服务</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>视频保健品</label>
							</div>
						</td>
					</tr>
					<tr class="ui-table-row">
						<td class="col-first">
							<div class="intro-pic">
								<label>手机数码</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>通讯服务设备</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>网络服务</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>医疗服务</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>游戏</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>运动休闲娱乐</label>
							</div>
						</td>
						<td>
							<div class="intro-pic">
								<label>招商加盟</label>
							</div>
						</td>
					</tr>
				</tbody>
			</table>
		</div>
	</div>
</template>

<script>
import VSelection from '../../components/base/selection'
import VChooser from '../../components/base/chooser'
export default{
	components:{
		VSelection,
		VChooser
	},
	data(){
		return{
			buyTypes:[
	    		{
	    			label:'红色版',
	    			value:0
	    		},
	    		{
	    			label:'绿色版',
	    			value:1
	    		},
	    		{
	    			label:'紫色版',
	    			value:2
	    		}
    		],
    		districts:[
	    		{
	    			label:'北京',
	    			value:0
	    		},
	    		{
	    			label:'上海',
	    			value:1
	    		},
	    		{
	    			label:'广州',
	    			value:2
	    		},
	    		{
	    			label:'天津',
	    			value:3
	    		},
	    		{
	    			label:'武汉',
	    			value:4
	    		},
	    		{
	    			label:'重庆',
	    			value:5
	    		}
    		]
		}
	}
}	
</script>