# Agents for Amazon Bedrock - Features examples
원본 페이지
[https://catalog.us-east-1.prod.workshops.aws/workshops/4c28c535-249d-44dc-939b-9f0942078336/en-US]
```
git clone https://github.com/aws-samples/amazon-bedrock-samples.git
mv amazon-bedrock-samples/agents-for-bedrock/features-examples/ agents-for-bedrock-workshop
rm -rf amazon-bedrock-samples

```

In this folder we provide you example implementations for the main Agents for Amazon Bedrock functionality:

이 폴더에서는 Agents for Amazon Bedrock 기능에 대한 구현 예제를 제공합니다:


1. [Create Agent with Function Definition](01-create-agent-with-function-definition): 액션 그룹 함수와 파라미터를 액션 그룹 호출과 연결된 JSON 객체로 정의하는 HR 어시스턴트 에이전트를 만드는 예제입니다. [AWS Lambda](https://aws.amazon.com/lambda/) 함수와 연결하여 작업을 실행합니다.
2. [Create Agent with API Schema](02-create-agent-with-api-schema): 수 및 파라미터 정의에 대한 API 스키마를 이용하여 보험금 청구 핸들러 에이전트를 생성하는 예제입니다. API 스키마는 [OpenAPI Specificiation](https://swagger.io/specification/) 형식을 따르며, 액션 실행을 위해 AWS Lambda 함수와 연결합니다. 
3. [Create Agent with Return of Control](03-create-agent-with-return-of-control): 액션 그룹 함수와 파라미터를 액션 그룹 호출과 연관된 JSON 객체로 정의하는 HR 지원 에이전트를 만드는 방법의 예시입니다. 이 예에서는 사용자의 애플리케이션에 제어를 반환하기 위해 AWS Lambda 함수 정의를 건너뜁니다. 
4. [Create Agent with a Single Knowledge](04-create-agent-with-single-knowledge-base): 하나의 [Knowledge Base for Amazon Bedrock](https://aws.amazon.com/bedrock/knowledge-bases/)으로 연결하여 성인용과 어린이용 메뉴에 대한 정보를 찾아주는 레스토랑 어시스턴트 에이전트를 만드는 예제입니다.
5. [Create Agent with Knowledge Base and Action Group](05-create-agent-with-knowledge-base-and-action-group): 보험금 청구의 핸들러를 확장하여 Knowledge Base에 연결하고 누락된 서류에 대한 요구 사항을 얻는 방법에 대한 예시입니다.
6. [Using Agent's Prompt and Session Parameters](06-prompt-and-session-parameters): agent의 Knowledge를 확장하기 위해 Agent 호출에 프롬프트 및 세션 파라미터를 전달하는 방법에 대한 예제입니다. 
7. [Changing Agent's Advanced Prompts and creating custom Lambda Parsers](07-advanced-prompts-and-custom-parsers): Agent의 고급 프롬프트를 변경하는 방법과 고급 상담원 사용 사례를 위한 custom 람다 파서를 만드는 방법에 대한 예제입니다.