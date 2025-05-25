<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>防水补漏材料全体系电商执行方案</title>
    <script src="https://cdn.tailwindcss.com/3.3.3"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/3.9.1/chart.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mermaid/11.5.0/mermaid.min.js"></script>
    <style>
        body {
            font-family: 'Noto Sans SC', sans-serif;
            background: linear-gradient(135deg, #f5f7fa 0%, #e4edf5 100%);
            color: #2d3748;
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.7);
            backdrop-filter: blur(10px);
            border-radius: 16px;
            border: 1px solid rgba(255, 255, 255, 0.3);
            box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.15);
            transition: all 0.3s ease;
        }
        .glass-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 28px 0 rgba(31, 38, 135, 0.2);
        }
        .highlight {
            background: rgba(99, 102, 241, 0.1);
            padding: 2px 8px;
            border-radius: 6px;
            color: #4f46e5;
        }
        .nav-item {
            position: relative;
        }
        .nav-item::after {
            content: '';
            position: absolute;
            bottom: -2px;
            left: 0;
            width: 0;
            height: 2px;
            background-color: #4f46e5;
            transition: width 0.3s ease;
        }
        .nav-item:hover::after {
            width: 100%;
        }
        .chart-container {
            height: 320px;
            width: 100%;
        }
        .timeline-dot {
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background-color: #4f46e5;
        }
        .timeline-line {
            width: 2px;
            background-color: #e5e7eb;
        }
    </style>
</head>
<body class="min-h-screen">
    <!-- 导航栏 -->
    <nav class="sticky top-0 z-50 bg-white bg-opacity-80 backdrop-blur-md shadow-sm py-4 px-6">
        <div class="container mx-auto flex items-center justify-between">
            <div class="text-xl font-bold text-indigo-600">
                <i class="fas fa-water mr-2"></i>数据来源：yuntu.oceanengine
            </div>
            <div class="hidden md:flex space-x-8">
                <a href="#market" class="nav-item text-gray-600 hover:text-indigo-600">市场规模</a>
                <a href="#user-profile" class="nav-item text-gray-600 hover:text-indigo-600">用户画像</a>
                <a href="#ad-plan" class="nav-item text-gray-600 hover:text-indigo-600">投流计划</a>
                <a href="#strategy" class="nav-item text-gray-600 hover:text-indigo-600">执行策略</a>
            </div>
            <button class="md:hidden text-gray-600 focus:outline-none" id="mobileMenuBtn">
                <i class="fas fa-bars text-xl"></i>
            </button>
        </div>
        <!-- 移动端菜单 -->
        <div class="md:hidden hidden bg-white mt-2 rounded-lg shadow-lg py-2" id="mobileMenu">
            <a href="#market" class="block px-4 py-2 text-gray-600 hover:bg-indigo-50 hover:text-indigo-600 rounded-md">市场规模</a>
            <a href="#user-profile" class="block px-4 py-2 text-gray-600 hover:bg-indigo-50 hover:text-indigo-600 rounded-md">用户画像</a>
            <a href="#ad-plan" class="block px-4 py-2 text-gray-600 hover:bg-indigo-50 hover:text-indigo-600 rounded-md">投流计划</a>
            <a href="#strategy" class="block px-4 py-2 text-gray-600 hover:bg-indigo-50 hover:text-indigo-600 rounded-md">执行策略</a>
        </div>
    </nav>

    <!-- 主要内容 -->
    <main class="container mx-auto py-8 px-4 md:px-8">
        <!-- 标题区 -->
        <section class="text-center mb-16">
            <h1 class="text-4xl md:text-5xl font-bold text-gray-800 mb-4">防水补漏材料全体系电商执行方案</h1>
            <p class="text-xl text-gray-600 max-w-3xl mx-auto">涵盖东南亚市场分析、泰国本土化运营、直播标准化及国内电商平台运营策略</p>
        </section>

        <!-- 市场规模部分 -->
        <section id="market" class="mb-16">
            <div class="glass-card p-8 mb-8">
                <h2 class="text-3xl font-bold text-gray-800 mb-6 flex items-center">
                    <div class="w-10 h-10 rounded-full bg-indigo-100 flex items-center justify-center text-indigo-600 mr-4">
                        <i class="fas fa-chart-line"></i>
                    </div>
                    市场规模与增长趋势
                </h2>
                
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div>
                        <h3 class="text-xl font-semibold text-gray-700 mb-4">东南亚市场</h3>
                        <p class="text-gray-600 mb-4">2025年东盟防水市场规模预计为<span class="highlight">5.1728亿美元</span>，预计到2030年将达到<span class="highlight">7.2788亿美元</span>，2025-2030年的复合年增长率为<span class="highlight">7.07%</span>。</p>
                        
                        <h3 class="text-xl font-semibold text-gray-700 mb-4 mt-6">泰国市场</h3>
                        <p class="text-gray-600">泰国防水市场预计在2025-2034年间将以<span class="highlight">7.90%</span>的复合年增长率增长。随着泰国对基础设施投资的增加以及对水资源管理的重视，防水钢板等材料的需求逐渐上升。</p>
                    </div>
                    
                    <div class="chart-container">
                        <canvas id="marketChart"></canvas>
                    </div>
                </div>
            </div>
            
            <div class="glass-card p-8">
                <h3 class="text-2xl font-semibold text-gray-700 mb-4 flex items-center">
                    <i class="fas fa-shopping-bag text-indigo-500 mr-3"></i>
                    TikTok和虾皮平台产品需求情况
                </h3>
                <p class="text-gray-600 mb-4">常见防水补漏材料有防水卷材、防水涂料、防水密封材料、堵漏材料等。不同类型材料价格有所差异：</p>
                
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-6">
                    <div class="bg-indigo-50 p-4 rounded-lg">
                        <p class="text-indigo-700 font-medium"><i class="fas fa-paint-roller mr-2"></i>防水涂料</p>
                        <p class="text-gray-600">每桶几十元到几百元不等</p>
                    </div>
                    <div class="bg-purple-50 p-4 rounded-lg">
                        <p class="text-purple-700 font-medium"><i class="fas fa-ruler-combined mr-2"></i>防水卷材</p>
                        <p class="text-gray-600">每平方米十几元到几十元之间</p>
                    </div>
                </div>
                
                <div class="bg-yellow-50 border-l-4 border-yellow-400 pl-4 py-2 rounded-r-lg">
                    <p class="text-yellow-800"><i class="fas fa-info-circle mr-2"></i>暂未找到TikTok和虾皮平台上东南亚特别是泰国防水补漏材料的产品种类、销量、价格区间等产品需求的直接信息。</p>
                </div>
            </div>
        </section>

        <!-- 用户画像部分 -->
        <section id="user-profile" class="mb-16">
            <div class="glass-card p-8">
                <h2 class="text-3xl font-bold text-gray-800 mb-6 flex items-center">
                    <div class="w-10 h-10 rounded-full bg-indigo-100 flex items-center justify-center text-indigo-600 mr-4">
                        <i class="fas fa-user-tie"></i>
                    </div>
                    当地用户画像
                </h2>
                
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div>
                        <h3 class="text-xl font-semibold text-gray-700 mb-4">年龄与消费能力</h3>
                        <p class="text-gray-600 mb-4">泰国中年人口较多，<span class="highlight">25-53岁</span>的人口占比<span class="highlight">43%</span>，平均人口年龄<span class="highlight">40.5岁</span>。</p>
                        <p class="text-gray-600">泰国中产阶段的崛起意味着人均可支配支出增加，推动当地消费力提升。不过各地区发展差异较大，中心城市电商发展快，消费能力相对更强。</p>
                        
                        <h3 class="text-xl font-semibold text-gray-700 mb-4 mt-6">消费习惯与偏好</h3>
                        <ul class="list-disc pl-5 text-gray-600 space-y-2">
                            <li>对国际品牌与商品需求旺盛，近一半消费者购买过跨境商品，更愿意为知名国际品牌花钱</li>
                            <li>对防水补漏材料的需求受当地气候影响，泰国属热带气候，分为雨季、凉季、热季，对防水性能要求高</li>
                        </ul>
                    </div>
                    
                    <div>
                        <h3 class="text-xl font-semibold text-gray-700 mb-4">购买渠道</h3>
                        <p class="text-gray-600 mb-6">泰国互联网用户社交媒体粘性大，<span class="highlight">92%</span>的网购者通过社交媒体购物，电商卖家可利用社交媒体进行品牌打造。</p>
                        
                        <div class="bg-blue-50 p-6 rounded-xl">
                            <h4 class="text-lg font-semibold text-blue-700 mb-3 flex items-center">
                                <i class="fas fa-lightbulb text-blue-500 mr-2"></i>
                                市场洞察
                            </h4>
                            <p class="text-gray-700">泰国消费者对国际品牌接受度高，同时受热带气候影响，对防水性能要求严格。社交媒体是重要的购物渠道入口。</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 投流计划部分 -->
        <section id="ad-plan" class="mb-16">
            <div class="glass-card p-8">
                <h2 class="text-3xl font-bold text-gray-800 mb-6 flex items-center">
                    <div class="w-10 h-10 rounded-full bg-indigo-100 flex items-center justify-center text-indigo-600 mr-4">
                        <i class="fas fa-bullseye"></i>
                    </div>
                    投流计划
                </h2>
                
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div>
                        <h3 class="text-xl font-semibold text-gray-700 mb-4">投流目标</h3>
                        <ul class="list-disc pl-5 text-gray-600 space-y-2 mb-6">
                            <li>提高品牌知名度</li>
                            <li>增加产品销量</li>
                            <li>吸引潜在客户</li>
                        </ul>
                        
                        <h3 class="text-xl font-semibold text-gray-700 mb-4">投流渠道</h3>
                        <div class="space-y-4">
                            <div class="bg-purple-50 p-4 rounded-lg">
                                <h4 class="text-purple-700 font-medium flex items-center">
                                    <i class="fab fa-tiktok mr-2"></i>TikTok
                                </h4>
                                <p class="text-gray-600 mt-2">利用其庞大的用户群体和强大的社交传播能力，通过短视频、直播等形式进行产品推广。</p>
                            </div>
                            <div class="bg-orange-50 p-4 rounded-lg">
                                <h4 class="text-orange-700 font-medium flex items-center">
                                    <i class="fas fa-store mr-2"></i>虾皮
                                </h4>
                                <p class="text-gray-600 mt-2">作为东南亚知名电商平台，具有较高的流量和用户活跃度，可通过平台广告、促销活动等吸引消费者。</p>
                            </div>
                        </div>
                    </div>
                    
                    <div>
                        <h3 class="text-xl font-semibold text-gray-700 mb-4">投流策略</h3>
                        
                        <div class="space-y-4">
                            <div class="bg-green-50 p-4 rounded-lg">
                                <h4 class="text-green-700 font-medium flex items-center">
                                    <i class="fas fa-ad mr-2"></i>广告内容制作
                                </h4>
                                <p class="text-gray-600 mt-2">针对泰国消费者偏好，突出产品的国际品牌背景、优质的防水性能、环保特性等优势。可采用对比实验、用户案例分享等形式。</p>
                            </div>
                            
                            <div class="bg-pink-50 p-4 rounded-lg">
                                <h4 class="text-pink-700 font-medium flex items-center">
                                    <i class="fas fa-user-tag mr-2"></i>网红营销
                                </h4>
                                <p class="text-gray-600 mt-2">与TikTok上的当地网红合作，邀请他们试用产品并进行推荐。选择网红时，要考虑其粉丝群体与目标客户的匹配度。</p>
                            </div>
                            
                            <div class="bg-blue-50 p-4 rounded-lg">
                                <h4 class="text-blue-700 font-medium flex items-center">
                                    <i class="fas fa-calendar-alt mr-2"></i>促销活动
                                </h4>
                                <p class="text-gray-600 mt-2">结合泰国的节日和消费热点，开展促销活动。例如在泰国泼水节期间，推出防水手机壳、防水背包等相关产品的优惠活动。</p>
                            </div>
                            
                            <div class="bg-yellow-50 p-4 rounded-lg">
                                <h4 class="text-yellow-700 font-medium flex items-center">
                                    <i class="fas fa-chart-bar mr-2"></i>数据分析与优化
                                </h4>
                                <p class="text-gray-600 mt-2">定期分析投流数据，了解广告的曝光量、点击率、转化率等指标，根据数据调整投流策略。</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="mt-8 bg-indigo-50 p-6 rounded-xl">
                    <h3 class="text-xl font-semibold text-indigo-700 mb-4 flex items-center">
                        <i class="fas fa-coins mr-2"></i>
                        投流预算建议
                    </h3>
                    <p class="text-gray-700">根据目标和渠道，合理分配预算。可先进行小范围测试，根据测试效果调整预算分配。例如，初期可将大部分预算投入到TikTok的网红合作和平台广告上，同时在虾皮平台进行一定的广告投放。</p>
                </div>
            </div>
        </section>

        <!-- 执行策略部分 -->
        <section id="strategy" class="mb-16">
            <div class="glass-card p-8">
                <h2 class="text-3xl font-bold text-gray-800 mb-6 flex items-center">
                    <div class="w-10 h-10 rounded-full bg-indigo-100 flex items-center justify-center text-indigo-600 mr-4">
                        <i class="fas fa-tasks"></i>
                    </div>
                    全体系电商执行策略
                </h2>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div>
                        <h3 class="text-xl font-semibold text-gray-700 mb-4 flex items-center">
                            <i class="fas fa-globe-asia text-indigo-500 mr-3"></i>
                            业务线规划
                        </h3>
                        <div class="space-y-4">
                            <div class="bg-blue-50 p-4 rounded-lg">
                                <h4 class="text-blue-700 font-medium">东南亚市场</h4>
                                <p class="text-gray-600 mt-2">以TikTok出海为主要平台，虾皮为辅助平台，深耕东南亚防水补漏材料市场。</p>
                            </div>
                            <div class="bg-green-50 p-4 rounded-lg">
                                <h4 class="text-green-700 font-medium">国内市场</h4>
                                <p class="text-gray-600 mt-2">运营国内1688、天猫、拼多多等电商平台，充分利用各平台的优势和流量。</p>
                            </div>
                        </div>

                        <h3 class="text-xl font-semibold text-gray-700 mb-4 mt-6 flex items-center">
                            <i class="fas fa-video text-indigo-500 mr-3"></i>
                            直播策略
                        </h3>
                        <div class="space-y-4">
                            <div class="bg-purple-50 p-4 rounded-lg">
                                <h4 class="text-purple-700 font-medium">视频号直播</h4>
                                <p class="text-gray-600 mt-2">采用真人直播的方式，通过与观众的实时互动，增强用户粘性和购买意愿。</p>
                            </div>
                            <div class="bg-pink-50 p-4 rounded-lg">
                                <h4 class="text-pink-700 font-medium">抖音直播</h4>
                                <p class="text-gray-600 mt-2">采用无人录播的方式，提前录制好高质量的产品宣传视频，在抖音平台进行循环播放。</p>
                            </div>
                        </div>
                    </div>

                    <div>
                        <h3 class="text-xl font-semibold text-gray-700 mb-4 flex items-center">
                            <i class="fas fa-users text-indigo-500 mr-3"></i>
                            团队组建与运营
                        </h3>
                        <div class="space-y-4">
                            <div class="bg-yellow-50 p-4 rounded-lg">
                                <h4 class="text-yellow-700 font-medium">全体系电商渠道搭建</h4>
                                <p class="text-gray-600 mt-2">在6月30号前完成全体系电商渠道的搭建，包括各个平台的店铺开设、页面装修、产品上架等工作。</p>
                            </div>
                            <div class="bg-teal-50 p-4 rounded-lg">
                                <h4 class="text-teal-700 font-medium">视频营销组组建</h4>
                                <p class="text-gray-600 mt-2">组建视频营销组，负责海外和国内电商IP营销视频的制作和推广。</p>
                            </div>
                            <div class="bg-red-50 p-4 rounded-lg">
                                <h4 class="text-red-700 font-medium">核心岗位AB角培训</h4>
                                <p class="text-gray-600 mt-2">对核心岗位采用AB角培训的方式，确保人员的稳定性和业务的连续性。</p>
                            </div>
                        </div>

                        <h3 class="text-xl font-semibold text-gray-700 mb-4 mt-6 flex items-center">
                            <i class="fas fa-briefcase text-indigo-500 mr-3"></i>
                            B端业务运营
                        </h3>
                        <div class="space-y-4">
                            <div class="bg-indigo-50 p-4 rounded-lg">
                                <h4 class="text-indigo-700 font-medium">个人IP打造</h4>
                                <p class="text-gray-600 mt-2">主打张锦诚个人IP，通过在行业内的专业形象和影响力，吸引B端客户。</p>
                            </div>
                            <div class="bg-orange-50 p-4 rounded-lg">
                                <h4 class="text-orange-700 font-medium">电话销售转化</h4>
                                <p class="text-gray-600 mt-2">河北电话销售团队负责B端客户的电话销售转化工作。</p>
                            </div>
                            <div class="bg-green-50 p-4 rounded-lg">
                                <h4 class="text-green-700 font-medium">大B端获客变现</h4>
                                <p class="text-gray-600 mt-2">大B端获客渠道由张精诚负责接待变现。</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="mt-8">
                    <h3 class="text-2xl font-semibold text-gray-700 mb-4 flex items-center">
                        <i class="fas fa-table text-indigo-500 mr-3"></i>
                        执行表
                    </h3>
                    <div class="overflow-x-auto">
                        <table class="min-w-full bg-white rounded-lg overflow-hidden">
                            <thead class="bg-indigo-100">
                                <tr>
                                    <th class="px-6 py-3 text-left text-xs font-medium text-indigo-700 uppercase tracking-wider">任务名称</th>
                                    <th class="px-6 py-3 text-left text-xs font-medium text-indigo-700 uppercase tracking-wider">责任人</th>
                                    <th class="px-6 py-3 text-left text-xs font-medium text-indigo-700 uppercase tracking-wider">开始时间</th>
                                    <th class="px-6 py-3 text-left text-xs font-medium text-indigo-700 uppercase tracking-wider">结束时间</th>
                                    <th class="px-6 py-3 text-left text-xs font-medium text-indigo-700 uppercase tracking-wider">任务描述</th>
                                </tr>
                            </thead>
                            <tbody class="divide-y divide-gray-200">
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">全体系电商渠道搭建</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[具体负责人]</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[开始日期]</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">6月30日</td>
                                    <td class="px-6 py-4 text-sm text-gray-700">完成各个平台的店铺开设、页面装修、产品上架等工作</td>
                                </tr>
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">视频营销组组建</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[具体负责人]</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[开始日期]</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[结束日期]</td>
                                    <td class="px-6 py-4 text-sm text-gray-700">招聘视频营销组人员，进行培训和分工</td>
                                </tr>
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">核心岗位AB角培训</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[具体负责人]</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[开始日期]</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[结束日期]</td>
                                    <td class="px-6 py-4 text-sm text-gray-700">对核心岗位人员进行AB角培训</td>
                                </tr>
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">张锦诚个人IP打造</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">广州营销总部</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[开始日期]</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[持续进行]</td>
                                    <td class="px-6 py-4 text-sm text-gray-700">创作内容、策划活动，提升个人IP影响力</td>
                                </tr>
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">河北电话销售转化</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">河北电话销售团队</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[开始日期]</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[持续进行]</td>
                                    <td class="px-6 py-4 text-sm text-gray-700">进行B端客户的电话销售转化工作</td>
                                </tr>
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">大B端获客变现</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">张精诚</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[开始日期]</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[持续进行]</td>
                                    <td class="px-6 py-4 text-sm text-gray-700">接待大B端客户，实现业务变现</td>
                                </tr>
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">TikTok和虾皮投流</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[具体负责人]</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[开始日期]</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[持续进行]</td>
                                    <td class="px-6 py-4 text-sm text-gray-700">根据投流计划进行广告投放和优化</td>
                                </tr>
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">视频号真人直播</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[具体负责人]</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[开始日期]</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[持续进行]</td>
                                    <td class="px-6 py-4 text-sm text-gray-700">开展视频号真人直播活动</td>
                                </tr>
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">抖音无人录播</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[具体负责人]</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[开始日期]</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">[持续进行]</td>
                                    <td class="px-6 py-4 text-sm text-gray-700">录制并投放抖音无人录播视频</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>
        </section>

        <!-- 泰国本土化运营部分 -->
        <section class="mb-16">
            <div class="glass-card p-8">
                <h2 class="text-3xl font-bold text-gray-800 mb-6 flex items-center">
                    <div class="w-10 h-10 rounded-full bg-indigo-100 flex items-center justify-center text-indigo-600 mr-4">
                        <i class="fas fa-flag"></i>
                    </div>
                    泰国本土化运营
                </h2>
                <p class="text-gray-600 mb-6">考虑泰国的文化、消费习惯、法律法规等因素，进行本土化运营。例如，在广告内容中融入泰国元素，使用当地语言进行沟通；了解当地的消费节日和热点，开展针对性的促销活动；遵守当地的法律法规，确保业务的合规运营。</p>
                
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="bg-blue-50 p-4 rounded-lg">
                        <h4 class="text-blue-700 font-medium flex items-center">
                            <i class="fas fa-language mr-2"></i>语言本地化
                        </h4>
                        <p class="text-gray-600 mt-2">使用泰语进行产品描述和客户沟通，确保信息准确传达。</p>
                    </div>
                    <div class="bg-green-50 p-4 rounded-lg">
                        <h4 class="text-green-700 font-medium flex items-center">
                            <i class="fas fa-calendar-day mr-2"></i>节日营销
                        </h4>
                        <p class="text-gray-600 mt-2">结合泼水节、水灯节等泰国传统节日开展促销活动。</p>
                    </div>
                    <div class="bg-purple-50 p-4 rounded-lg">
                        <h4 class="text-purple-700 font-medium flex items-center">
                            <i class="fas fa-balance-scale mr-2"></i>合规运营
                        </h4>
                        <p class="text-gray-600 mt-2">遵守泰国电商法规，确保产品认证和税务合规。</p>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- 页脚 -->
    <footer class="bg-gray-50 py-8 mt-16">
        <div class="container mx-auto px-4 text-center text-gray-500">
            <p>created by <a href="https://business.oceanengine.com/brand/index" class="text-indigo-600 hover:text-indigo-800">Ocean Engine</a></p>
            <p class="mt-2">页面内容抓取business.oceanengine数据来源</p>
        </div>
    </footer>

    <script>
        // 移动端菜单切换
        document.getElementById('mobileMenuBtn').addEventListener('click', function() {
            const menu = document.getElementById('mobileMenu');
            menu.classList.toggle('hidden');
        });

        // 平滑滚动
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // 市场规模图表
        const marketCtx = document.getElementById('marketChart').getContext('2d');
        new Chart(marketCtx, {
            type: 'bar',
            data: {
                labels: ['2025年', '2030年'],
                datasets: [{
                    label: '东南亚市场规模(亿美元)',
                    data: [5.1728, 7.2788],
                    backgroundColor: 'rgba(99, 102, 241, 0.6)',
                    borderColor: 'rgba(99, 102, 241, 1)',
                    borderWidth: 1
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                scales: {
                    y: {
                        beginAtZero: true,
                        grid: {
                            color: 'rgba(0, 0, 0, 0.05)'
                        }
                    },
                    x: {
                        grid: {
                            display: false
                        }
                    }
                },
                plugins: {
                    legend: {
                        position: 'top',
                    },
                    tooltip: {
                        callbacks: {
                            label: function(context) {
                                return context.dataset.label + ': ' + context.raw + '亿美元';
                            }
                        }
                    }
                }
            }
        });
    </script>
</body>
</html># omg
