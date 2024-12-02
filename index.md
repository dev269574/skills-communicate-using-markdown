# That's some huge heading there
![stupid ahh cats image](https://habrastorage.org/getpro/habr/upload_files/69d/0a1/7a2/69d0a17a2a96ecc8406ca5cd12d5d586.jpg)

basic `main.ts` file for NestJS
``` typescript
import { NestFactory } from '@nestjs/core';
import { AppModule } from './app.module';

async function bootstrap() {
	const app = await NestFactory.create(AppModule);
	await app.listen(3000);
}
bootstrap();
```
