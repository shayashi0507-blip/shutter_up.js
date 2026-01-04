module.exports = async (context) => {
  await context.ble.write({
    peripheralId: "EC:47:0C:FB:27:07",
    serviceUUID: "2141e110-213a-11e6-b67b-9e71128cae77",
    characteristicUUID: "2141e114-213a-11e6-b67b-9e71128cae77",
    value: "0203"
  });
};
