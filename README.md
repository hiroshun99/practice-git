# AWS 3-Tier Architecture Portfolio

## プロジェクト概要
AWS Solutions Architect Associate (SAA) の学習成果として、可用性とセキュリティを考慮したWebアプリケーション基盤を構築しました。

## アーキテクチャ構成図
*(現在、構成図を作成中です)*

## 使用技術
* **AWS**: VPC, EC2, RDS, ALB, S3
* **OS**: Amazon Linux 2023
* **Middleware**: Apache, MySQL

## こだわったポイント (SAAの知識)
1. **可用性**: Multi-AZ構成により、データセンター障害時も稼働を継続
2. **セキュリティ**: パブリック/プライベートサブネットによる階層化
3. **コスト**: 開発環境のため、NAT Gatewayは必要な時のみ起動する運用フローを確立

## 今後の展望
* TerraformによるIaC化
* CloudFrontによるコンテンツ配信の高速化