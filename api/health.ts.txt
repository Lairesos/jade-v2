export default function handler(req: any, res: any) {
  res.status(200).json({
    status: "online",
    nome: "Jade V2",
    versao: "0.1.0"
  });
}