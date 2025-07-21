<script>
    import { Card } from "$lib/components/ui/card";
    import CardContent from "$lib/components/ui/card/card-content.svelte";
    import CardHeader from "$lib/components/ui/card/card-header.svelte";
    import CardTitle from "$lib/components/ui/card/card-title.svelte";

</script>

<div class="container mx-auto p-4 md:p-8">
    <div class="text-center mb-12">
        <h1 class="text-4xl font-extrabold tracking-tighter lg:text-5xl">3분만에 AI기반 비즈니스 모델 캔버스를 생성해보세요</h1>
        <p class="mt-4 text-lg text-gray-500">아이디어를 명확하게 설정하고 실행 가능한 비즈니스 모델로 전환하세요, 뚝딱이는. 빠른 MVP모델과 1인기업과 모두를 위해 시간을 절약하고 중요한 포인트를 찾아내줄수있습니다.</p>
    </div>

    <div class="flex flex-col itmes-center jusify-center">
        <button class="bg-blue-500 hover:bg-blue-600 text-white font-medium rounded-lg text-sm px-5 py-2.5 text-center">시작하기</button>
    </div>

    <p class="text-center mt-4 text-gray-500 px-6 py-2">(결제가 필요하지 않습니다. 무료 미리보기)</p>

    <div class="container mx-auto p-4 md:p-8">
        <div class="flex">
            <div class="flex-1">
                <img class="w-full h-auto" src="" alt="">
            </div>
            <div class="flex-1">
                <span>즉각적인 비즈니스 캔버스를 받으세요</span>
                <p>빠른 MVP모델과 1인기업 모두를 위해 시간을 절약하고 중요한 포인트를 찾아줄수있습니다</p>
                <button class="mt-4 justify-center items-center bg-blue-500 text-white px-6 py-2 rounded-lg hover:bg-blue-700 transition-colors duration-300">바로 시작하기</button>
            </div>
        </div>
    </div>

    <Card>
        <CardHeader>
            <CardTitle class="text-2xl">아이디어 입력</CardTitle>
        </CardHeader>
        <CardContent>
            <form method="POST">
                <div class="grid gap-4">
                    <label for="idea" class="font-semibold">아이디어</label>
                    <input type="text" id="idea" name="idea" />
                </div>
            </form>
        </CardContent>

    </Card>
</div>